# Design Document
### Gebruikersinterface voor Datapanel configuraties


| Aanmaakdatum|10/10/2023|
|:-----------:|:--------:|
|Versie|0.2|
|Status|Done|
|Auteur|Tim Meijvogel|


## Inhoudsopgave
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
  - [C1 model](#c1-model)
  - [Container Diagram](#container-diagram)
    - [Datapanel Webtoepassing](#datapanel-web-application)
    - [API Gateway-toepassing](#api-gateway-application)
    - [No-Code API-toepassing](#no-code-api-application)
    - [Authentication Application](#authentication-application)
    - [No-Code Database](#no-code-database)
- [User Interface Design](#user-interface-design)
  - [Wireframes](#wireframes)
    - [Overzichtspagina’s](#overzichtspaginas)
    - [Edit Pagina’s](#edit-paginas)
    - [Pop-up](#pop-up)
  - [UI Prototypes](#ui-prototype)
    - [Overzichtspagina’s](#overzichtspaginas-1)
    - [Pop-up](#pop-up-1)
    - [Edit pagina’s](#edit-paginas-1)
- [System Integration](#system-intergration)

## Introduction
Dit design document bevat essentiële informatie voor dit project en omvat de volgende onderwerpen:
- Systeemarchitectuur: Details over de systeemstructuur, componenten en interacties.
- Ontwerp van de gebruikersinterface (UI): Informatie over de UI-layout en gebruikersinteractie.
- Systeemintegratie: Uitleg over hoe het systeem zal integreren met externe componenten en gegevensuitwisseling.

Dit dossier dient als leidraad voor het ontwerp en de implementatie van dit project en biedt een overzicht van de belangrijkste aspecten die moeten worden aangepakt. Het zal als referentie dienen voor alle betrokken partijen.

## System Architecture
### C1 model
Het C1-model biedt een overzicht van de belangrijkste actoren en systemen die betrokken zijn bij het Datapanel systeem. Het model beschrijft de interacties en relaties tussen deze entiteiten:  
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/33a23e8a-1c71-4712-8ee4-89c46dc1d3e3" width=400px/>

- **Admin** [Persoon]: Deze actor vertegenwoordigt beheerders of beheerders van het systeem. Ze hebben de mogelijkheid om het systeem te configureren en verschillende aspecten ervan aan te passen om aan de behoeften van de
organisatie te voldoen.  
- **User** [Persoon]: Gebruikers van het Datapanel kunnen verschillende rollen hebben. Ze maken gebruik van Datapanel om toegang te krijgen tot gegevens en met deze gegevens te interageren. De rollen van deze gebruikers kunnen variëren, afhankelijk van hun rechten en verantwoordelijkheden.  
- **Data Transformation System** [Software Systeem]: Dit systeem is verantwoordelijk voor de verwerking van gegevenstransformatie tussen de databases van klanten en de databases van  het Datapanel systeem. Het zorgt voor een naadloze uitwisseling en transformatie van gegevens om ervoor te zorgen dat de juiste gegevens beschikbaar zijn voor Datapanel.  

Alle actoren en systemen zijn verbonden met:  
- **Datapanel systeem** [Software Systeem]: Het Datapanel systeem is het centrale onderdeel van het systeem. Het stelt beheerders in staat om systemen in te stellen voor de verwerking van gegevens en gebruikers in staat om met deze gegevens te interageren. Beheerders kunnen configuraties aanpassen, terwijl gebruikers de gegevens kunnen raadplegen en ermee kunnen werken.  

Dit C1-model biedt een overzicht van de belangrijkste actoren en systemen in het Datapanel systeem en de manier waarop ze met elkaar communiceren. Het is de basis voor het begrijpen van de relaties en verantwoordelijkheden binnen het systeem.

### Container Diagram
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/d68e773a-9cfe-4de5-91b8-8e278aa512af" width=400px/>

#### Datapanel Weba Application
De Datapanel webtoepassing is een cruciaal onderdeel van het systeem en speelt een essentiële rol bij het verstrekken van gegevens- en configuratiefuncties aan gebruikers via een webbrowser. Deze toepassing wordt uitgevoerd in een containeromgeving met NPM, TypeScript, Lit, en Redux. Het vormt de kern van de user interface en fungeert als het belangrijkste punt van interactie tussen gebruikers en het systeem.
De Datapanel webtoepassing is nauw verbonden met twee andere belangrijke componenten:  
- API Gateway-toepassing
- Authenticatietoepassing

Samen vormen deze componenten de hoeksteen van  de container diagram, waarbij de Datapanel webtoepassing fungeert als de toegangspoort tot de systeemfunctionaliteit, terwijl de API Gateway en de Authenticatietoepassing de gegevensdistributie en beveiligingsaspecten van het systeem verzorgen. Dit model is essentieel voor het begrijpen van de architectuur en interacties binnen het systeem.

#### API Gateway Application
De API Gateway-toepassing speelt een cruciale rol in het systeem door alle gegevens- en configuratiefuncties aan te bieden via een JSON/HTTPS API. Deze toepassing wordt uitgevoerd in een containeromgeving met TypeScript en fungeert als een brug tussen gebruikers en het systeem.
De API Gateway-toepassing staat in verbinding met drie andere containers:  
- Authenticatietoepassing  
- No-Code API Toepassing
- No-Code Database

Deze samenhang tussen de API Gateway, Authenticatietoepassing, No-Code API Toepassing en No-Code Database is van cruciaal belang om te begrijpen hoe gegevens en configuraties worden verwerkt en gedistribueerd binnen het systeem. Het API Gateway-model vormt de kern van onze architectuur, en deze containers werken samen om de functionaliteit van het systeem te ondersteunen en te beveiligen.

#### No-Code API Application
De No-Code API-toepassing speelt een cruciale rol in het systeem door alle gegevens- en configuratiefuncties aan te bieden via een JSON/HTTPS API. Deze toepassing wordt uitgevoerd in een containeromgeving met TypeScript en stelt gebruikers in staat om gegevens te benaderen en configuraties uit te voeren zonder diepgaande programmeerkennis.
De No-Code API-toepassing is verbonden met twee andere containers:  
- No-Code Database 
- Authenticatietoepassing
  
Deze verbindingen tussen de No-Code API-toepassing, de No-Code Database en de Authenticatietoepassing vormen een integraal onderdeel van het systeem. Ze zorgen ervoor dat gegevens en configuraties veilig en efficiënt worden verwerkt en gedistribueerd, en dat gebruikers toegang hebben tot de benodigde functionaliteit zonder de noodzaak van diepgaande programmeerkennis.

#### Authentication Application
Dit component, ook geïmplementeerd in TypeScript en ondersteund door Keycloak, beheert alle aspecten van gebruikersauthenticatie. Het garandeert de beveiliging van het systeem door middel van strikte authenticatieprotocollen en -services.

#### No-Code Database 
Deze container is geïmplementeerd als een Postgres database en functioneert  als de opslagplaats voor alle modelgegevens, no-code elementen en gateway-configuraties. Het speelt een essentiële rol bij het bewaren van de systeeminformatie en ondersteunt de functionaliteit van de API Gateway-toepassing.



## User Interface Design:
De UI bestaat uit 3 type pagina’s, de overzichtspagina’s, de edit pagina's en de pop-ups. Deze 3 types zijn de basis voor het proces van het maken van de Datapanel configuraties.  

### Wireframes
#### Overzichtspagina’s
Na het bekijken van Datapanel bleek het dat er  2 passende opties waren voor de overzichtspagina’s. Beide opties waren al in gebruik in Datapanel. De eerste was een overview met ‘cards’, elke modelview, page, subpage en sectie heeft een eigen kaartje met de belangrijkste informatie weergegeven. Verder bevat dit kaartje een knop voor het bewerken of verwijderen van de bijbehorende  modelview, page, subpage of sectie.  
De andere optie was een tabel met de belangrijkste informatie en de verwijder knop in de kolommen.

|Cards overview|Table overview|
|:------------:|:------------:|
|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/3dc2dcd7-45b4-4d4a-95f1-29fc91157aed" width=500px />|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/ebbd37e5-ab09-42be-a601-11b5e9129b12" width=500px />  |
|Existing cards overview|Existing tables|
|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/f6ed3213-45a0-4ebe-98d7-134a8e93ac5f" width=500px />|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/96373db4-3756-47df-8d11-c13e63e05413" width=500px />|

Ik heb de cardview aangeraden, omdat het beter bij het uiterlijk van Datapanel past. Na het vragen van feedback op deze designs, bleek de voorkeur van de stakeholder ook naar de cardview  te gaan.

#### Edit Pagina’s
Het eerste design van een edit pagina was voor het maken van een modelview. De uitdaging zat bij properties die niet in één tekstveld kunnen worden genoteerd, denk aan arrays. De eerste wireframe hiervoor zag er als volgt uit.
|Eerste wireframe||
|:-----:|:---------|
|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/96a5eb29-41fb-4b5b-9418-ab1e84ec7e54" width=700px>|Deze wireframe bevat geen scroll functionaliteit, dit is de reden dat hij zo lang is. In deze wireframe zijn alle properties die te gebruiken zijn voor het maken van een modelview, de properties die met een tekstveld in te vullen zijn staan bij elkaar. Arrays die bestaan uit alleen strings kunnen worden ingevuld als een lijst die een veld toevoegt wanneer dit nodig is. De arrays die uit objecten bestaan worden hier weergegeven als een soort kaartje, op deze manier kun je een object volledig invullen en blijft het overzichtelijk. Een leeg kaartje wordt gegenereerd wanneer je op de ‘+’ knop drukt.|

‘Import settings’ heeft meerdere array properties, om dit overzichtelijk te maken hebben deze properties hun eigen mapjes. Wanneer een mapje wordt geopend zal deze de hele sectie overnemen. Het idee voor deze mapjes is gehaald uit Datapanel.  
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/a34bd9c2-ffe6-4efb-85c7-37765e4641e4" width=500px> 
 

Na feedback te hebben ontvangen over deze wireframe, zijn er tabjes toegevoegd in plaats van dat de user door alle secties moet scrollen. Dit maakt de UI een stuk duidelijker en zorgt ervoor dat de users niet continu hoeven te zoeken naar de sectie die ze nodig hebben.
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/6e7fe00d-b792-4468-9b64-d5a539e9d017" width=500px>


#### Pop-up
Het design en het idee van de pop-up voor het aanmaken van pages, subpages, secties, komt ook van datapanel. Door een pop-up te gebruiken kan de user de belangrijkste informatie snel invullen en daarna de keus maken of hij het onderdeel verder aan wil passen. Door de user niet meteen naar een ‘edit pagina’ te sturen kan de user ook snel meerdere onderdelen aanmaken, zonder continu terug te gaan naar de overzichtspagina. 
|Wireframe|Datapanel|
|:-------:|:-------:|
|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/4738226b-8075-4e29-8de6-d4acfa6095f7" width=500px>|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/5a3be3e5-463b-4396-8c2c-ea5a9765835b" width=500px>|

### UI Prototypes
#### Overzichtspagina’s
Het design van de UI prototypes komt net als de wireframes van Datapanel zelf. Om Datapanel na te maken in Figma, zijn de assets van Stofloos gebruikt. Alles behalve de kaartjes komt uit de Stofloos assets, wel zijn de tekst en icons aangepast. De kaartjes bestaan ook uit assets van stofloos, deze assets zijn gebruikt om ze na te maken zoals ze al in Datapanel stonden. 
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/72bed2aa-f727-4921-9a15-3fbb815716fa" width=500px />

#### Pop-up
De pop-up moest ook nagemaakt worden in Figma, natuurlijk is dit gedaan met de assets van Stofloos. Na feedback te hebben ontvangen staan in deze pop-ups alleen nog tekstvelden en geen mapjes meer, de reden hiervoor is dat met de mapjes en de grootte van de pop-ups, de pop-ups snel onoverzichtelijk worden.
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/ebb758a9-148e-46ce-928b-bb8305a4fa6c" width=500px />

#### Edit pagina’s
 De edit pagina’s bestaan voornamelijk uit tekstvelden, checkboxes, en mapjes. De reden hiervoor is overzichtelijkheid. De mapjes zijn properties die bestaan uit meerdere strings, numbers, objecten, etc. 

|Edit page|Inhoud mapje|
|:-------:|:----------:|
|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/c85eebd7-30d6-4bdc-a0dd-7c84c85e5405" width=500px />|<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/015309bf-d8fd-4dad-8232-dc9ec14553a4" width=500px />|

Een array van object moest er ook anders uit komen te zien, aangezien een object uit verschillende velden kan bestaan. Het idee hiervoor was om weer een soort card view te maken voor deze objecten. Een array van objecten bestaat dus uit kaartjes met de benodigde velden, zoals hier te zien is.  
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/8c2ebb4e-e55a-4f59-8002-7724afb086e1" width=500px />  
**(Library - Available Product Analysis, Expert Interview | Workshop - Prototyping)**

