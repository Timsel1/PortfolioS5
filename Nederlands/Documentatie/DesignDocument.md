# Design Document
### Gebruikersinterface voor Datapanel configuraties


| Aanmaakdatum|10/10/2023|
|:-----------:|:--------:|
|Versie|0.1|
|Status|In progress|
|Auteur|Tim Meijvogel|


## Inhoudsopgave
- [Introduction]()
- [System Architecture]()
   - [C4 model]()
    - [Datapanel Webtoepassing]()
    - [API Gateway-toepassing]()
    - [No-Code API-toepassing]()
  - [C1 model]()
- [User Interface (UI) Design]()
  - [Wireframes]()
    - [De overzichtspagina’s]()
    - [Edit Pagina’s]()
    - [Pop-up]()
  - [UI Prototypes]()
    - [Overzichtspagina’s]()
    - [Pop-up]()
    - [Edit pagina’s]()
- [System Integration]()

## Introduction:
Dit design document bevat essentiële informatie voor dit project en omvat de volgende onderwerpen:
- Systeemarchitectuur: Details over de systeemstructuur, componenten en interacties.
- Ontwerp van de gebruikersinterface (UI): Informatie over de UI-layout en gebruikersinteractie.
- Systeemintegratie: Uitleg over hoe het systeem zal integreren met externe componenten en gegevensuitwisseling.

Dit dossier dient als leidraad voor het ontwerp en de implementatie van dit project en biedt een overzicht van de belangrijkste aspecten die moeten worden aangepakt. Het zal als referentie dienen voor alle betrokken partijen.

## System Architecture:
### C1 model
Het C1-model biedt een overzicht van de belangrijkste actoren en systemen die betrokken zijn bij het Datapanel systeem. Het model beschrijft de interacties en relaties tussen deze entiteiten:  
- **Admin** [Persoon]: Deze actor vertegenwoordigt beheerders of beheerders van het systeem. Ze hebben de mogelijkheid om het systeem te configureren en verschillende aspecten ervan aan te passen om aan de behoeften van de organisatie te voldoen.  - **User** [Persoon]: Gebruikers van het Datapanel kunnen verschillende rollen hebben. Ze maken gebruik van Datapanel om toegang te krijgen tot gegevens en met deze gegevens te interageren. De rollen van deze gebruikers kunnen variëren, afhankelijk van hun rechten en verantwoordelijkheden.  
- **Data Transformation System** [Software Systeem]: Dit systeem is verantwoordelijk voor de verwerking van gegevenstransformatie tussen de databases van klanten en de databases van  het Datapanel systeem. Het zorgt voor een naadloze uitwisseling en transformatie van gegevens om ervoor te zorgen dat de juiste gegevens beschikbaar zijn voor Datapanel.  

Alle actoren en systemen zijn verbonden met:  
- **Datapanel systeem** [Software Systeem]: Het Datapanel systeem is het centrale onderdeel van het systeem. Het stelt beheerders in staat om systemen in te stellen voor de verwerking van gegevens en gebruikers in staat om met deze gegevens te interageren. Beheerders kunnen configuraties aanpassen, terwijl gebruikers de gegevens kunnen raadplegen en ermee kunnen werken.  

Dit C1-model biedt een overzicht van de belangrijkste actoren en systemen in het Datapanel systeem en de manier waarop ze met elkaar communiceren. Het is de basis voor het begrijpen van de relaties en verantwoordelijkheden binnen het systeem.

### C4 model
#### Datapanel Webtoepassing
De Datapanel webtoepassing is een cruciaal onderdeel van het systeem en speelt een essentiële rol bij het verstrekken van gegevens- en configuratiefuncties aan gebruikers via een webbrowser. Deze toepassing wordt uitgevoerd in een containeromgeving met NPM, TypeScript, Lit, en Redux. Het vormt de kern van de user interface en fungeert als het belangrijkste punt van interactie tussen gebruikers en het systeem.
De Datapanel webtoepassing is nauw verbonden met twee andere belangrijke componenten:
API Gateway-toepassing: Dit component, uitgevoerd in TypeScript, fungeert als een tussenliggende laag tussen de Datapanel webtoepassing en de rest van het systeem. Het biedt gegevens- en configuratiefuncties aan via een JSON/HTTPS API, waardoor externe systemen en services toegang kunnen krijgen tot de benodigde gegevens en functionaliteit.
Authenticatietoepassing: Dit component, ook geïmplementeerd in TypeScript en ondersteund door Keycloak, beheert alle aspecten van gebruikersauthenticatie. Het garandeert de beveiliging van het systeem door middel van strikte authenticatieprotocollen en -services.
Samen vormen deze componenten de hoeksteen van het C4-model, waarbij de Datapanel webtoepassing fungeert als de toegangspoort tot de systeemfunctionaliteit, terwijl de API Gateway en de Authenticatietoepassing de gegevensdistributie en beveiligingsaspecten van het systeem verzorgen. Dit model is essentieel voor het begrijpen van de architectuur en interacties binnen het systeem.

#### API Gateway-toepassing
De API Gateway-toepassing speelt een cruciale rol in het systeem door alle gegevens- en configuratiefuncties aan te bieden via een JSON/HTTPS API. Deze toepassing wordt uitgevoerd in een containeromgeving met TypeScript en fungeert als een brug tussen gebruikers en het systeem.
De API Gateway-toepassing staat in verbinding met drie andere containers:
Authenticatietoepassing: Deze container, ook geïmplementeerd in TypeScript en ondersteund door Keycloak, biedt alle authenticatiediensten binnen het systeem. Het waarborgt de veiligheid en de integriteit van het systeem door gebruik te maken van de kracht van Keycloak.
No-Code API Toepassing: Deze container, eveneens geïmplementeerd in TypeScript, biedt gegevens- en configuratiefuncties aan via een JSON/HTTPS API. Het stelt externe systemen en services in staat om toegang te krijgen tot de gewenste gegevens en functionaliteit zonder de noodzaak van diepgaande programmeerkennis.
No-Code Database: Deze container is geïmplementeerd als een Postgres database en fungeert als de opslagplaats voor alle modelgegevens, no-code elementen en gateway-configuraties. Het speelt een essentiële rol bij het bewaren van de systeeminformatie en ondersteunt de functionaliteit van de API Gateway-toepassing.
Deze samenhang tussen de API Gateway, Authenticatietoepassing, No-Code API Toepassing en No-Code Database is van cruciaal belang om te begrijpen hoe gegevens en configuraties worden verwerkt en gedistribueerd binnen het systeem. Het API Gateway-model vormt de kern van onze architectuur, en deze containers werken samen om de functionaliteit van het systeem te ondersteunen en te beveiligen.
No-Code API-toepassing
De No-Code API-toepassing speelt een cruciale rol in het systeem door alle gegevens- en configuratiefuncties aan te bieden via een JSON/HTTPS API. Deze toepassing wordt uitgevoerd in een containeromgeving met TypeScript en stelt gebruikers in staat om gegevens te benaderen en configuraties uit te voeren zonder diepgaande programmeerkennis.
De No-Code API-toepassing is verbonden met twee andere containers:
No-Code Database: Deze container is geïmplementeerd als een Postgres-database en fungeert als de centrale opslagplaats voor alle modelgegevens, no-code-elementen en gateway-configuraties. Het speelt een essentiële rol bij het bewaren van gegevens en configuraties die nodig zijn voor de werking van het systeem.
Authenticatietoepassing: Deze container, geïmplementeerd in TypeScript en ondersteund door Keycloak, biedt alle authenticatiediensten binnen het systeem. Het waarborgt de veiligheid en beveiliging van de No-Code API-toepassing en zorgt ervoor dat alleen geautoriseerde gebruikers toegang hebben tot de gegevens en functionaliteit.
Deze verbindingen tussen de No-Code API-toepassing, de No-Code Database en de Authenticatietoepassing vormen een integraal onderdeel van het systeem. Ze zorgen ervoor dat gegevens en configuraties veilig en efficiënt worden verwerkt en gedistribueerd, en dat gebruikers toegang hebben tot de benodigde functionaliteit zonder de noodzaak van diepgaande programmeerkennis.




## User Interface (UI) Design:
De UI bestaat uit 3 type pagina’s, de overzichtspagina’s, de edit pagina's en de pop-ups. Deze 3 types zijn nodig voor een intuïtieve 

### Wireframes
#### De overzichtspagina’s
Ik had de keuze tussen 2 opties bij het maken van de overzichtspagina’s. Beide opties waren al in gebruik in Datapanel. De eerste was een overview met ‘cards’, elke modelview, page, subpage en sectie heeft een eigen kaartje met de belangrijkste informatie weergegeven. verder bevat dit kaartje een knop voor het bewerken of verwijderen van de bijbehorende  modelview, page, subpage of sectie.
De andere optie was een tabel met de belangrijkste informatie en de verwijder knop in de kolommen.

Mijn voorkeur ging naar de kaartjes, omdat dit er voor mij overzichtelijker en moderner uitzag. Ook vond ik dit beter bij het uiterlijk van Datapanel passen. Na het vragen van feedback op deze designs, bleek de voorkeur van de stakeholder ook naar het overzicht met de  ‘cards’ te gaan.

#### Edit Pagina’s
Mijn eerste design van een edit pagina was voor het maken van een modelview. De uitdaging zat bij properties die niet in één tekstveld kunnen worden genoteerd, denk aan arrays. Mijn eerste wireframe hiervoor zag er als volgt uit.

Deze wireframe bevat geen scroll functionaliteit, dit is de reden voor hoe lang hij is. In deze wireframe zijn alle properties die te gebruiken zijn voor het maken van een modelview, de properties die met een tekstveld in te vullen zijn staan bij elkaar. Arrays die bestaan uit alleen strings kunnen worden ingevuld als een lijst die een veld toevoegt wanneer dit nodig is. De arrays die uit objecten bestaan worden hier weergegeven als een soort kaartje, op deze manier kun je een object volledig invullen en blijft het overzichtelijk. Een leeg kaartje wordt gegenereerd wanneer je op de ‘+’ knop drukt. ‘Import settings’ heeft meerdere array properties, om dit overzichtelijk te maken hebben deze properties hun eigen mapjes. Wanneer een mapje wordt geopend zal deze de hele sectie overnemen. Het idee voor deze mapjes is gehaald uit Datapanel.





Na feedback te hebben ontvangen over deze wireframe, heb ik tabjes toegevoegd in plaats van dat je door alle secties moet scrollen. Dit maakt de UI een stuk duidelijker en zorgt ervoor dat de users niet continu hoeven te zoeken naar de sectie die ze nodig hebben.


#### Pop-up
Het design en het idee van de pop-up voor het aanmaken van pages, subpages, secties, komt ook van datapanel. Door een pop-up te gebruiken kan de user de belangrijkste informatie snel invullen en daarna de keus maken of hij het onderdeel verder aan wil passen. Door de user niet meteen naar een ‘edit pagina’ te sturen kan de user ook snel meerdere onderdelen aanmaken, zonder continu terug te gaan naar de overzichtspagina. 

### UI Prototypes
#### Overzichtspagina’s
Het design van de UI prototypes komt net als de wireframes van Datapanel zelf. Om Datapanel na te maken in Figma, heb ik assets van Stofloos gebruikt. Alles behalve de kaartjes heb ik uit Stofloos assets kunnen halen, wel heb ik tekst en icons aan moeten passen. De kaartjes bestaan wel uit assets van stofloos, deze assets heb ik gebruikt om ze na te maken zoals ze al in Datapanel stonden. 



#### Pop-up
Ik moest de pop-up ook zelf namaken in Figma, natuurlijk heb ik dit gedaan met de assets van Stofloos. Na feedback te hebben ontvangen staan in deze pop-ups alleen nog tekstvelden en geen mapjes meer, de reden hiervoor is dat met de mapjes en de grootte van de pop-ups, de pop-ups snel onoverzichtelijk worden.



#### Edit pagina’s
 De edit pagina’s bestaan voornamelijk uit tekstvelden, checkboxes, en mapjes. De reden hiervoor is overzichtelijkheid. De mapjes zijn properties die bestaan uit meerdere strings, numbers, objecten, etc. 

Een array dat in zo’n mapje zit, ziet er als volgt uit.

Een array van object moest er ook anders uit komen te zien, aangezien een object uit verschillende velden kan bestaan. Mijn idee hiervoor was om weer een soort card view te maken voor deze objecten. Een array van objecten bestaat dus uit kaartjes met de benodigde velden, zoals hier te zien is.

**(Library - Available Product Analysis, Expert Interview | Workshop - Prototyping)**

## System Integration:
Explain how the system will integrate with external services, APIs, or third-party components.
Describe data exchange formats and protocols.

