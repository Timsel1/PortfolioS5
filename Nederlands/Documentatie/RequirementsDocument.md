# Requirements document

## Inhoudsopgave
- [Introductie](#introductie)	
- [Project Overview](#project-overview)
- [Functional Requirements](#functional-requirements)
- [Non-Functional Requirements](#non-functional-requirements)
- [System Architecture](#system-architecture)
- [User Interfaces](#user-interfaces)
- [Testing Requirements](#testing-requirements)


## Introductie
Dit document heeft tot doel de vereisten en verwachtingen van het project vast te leggen. Het dient als een blauwdruk die de richting en scope van het project definieert en biedt een gedetailleerde beschrijving 
van wat het uiteindelijke product moet bereiken.   
Dit document bevat de volgende belangrijke informatie:  
- Een beschrijving van het project en de context waarin het plaatsvindt.
- De doelstellingen en doelen van het project.
- Functional requirements, die beschrijven wat het systeem moet doen.
- Non-functional requirements, die de kwaliteit en prestaties van het systeem definiëren.
- Testvereisten en acceptatiecriteria om de kwaliteit van het eindproduct te waarborgen.

Dit document dient als een belangrijk referentiepunt gedurende de gehele levenscyclus van het project, van planning en ontwikkeling tot acceptatie en implementatie. Het nauwkeurig vastleggen en begrijpen van deze
vereisten is van cruciaal belang voor het succes van het project en het leveren van een product dat voldoet aan de verwachtingen van alle belanghebbenden.
 
## Project Overview
Stofloos specialiseert zich in het transformeren van data door middel van het maken van dashboards, dataplatforms, datawarehouses en rapporten. Het project richt zich op het verbeteren van het proces om Datapanel configuraties te maken, te stroomlijnen en fouten te verminderen. Het doel is om een gebruiksvriendelijke UI te ontwikkelen voor het configureren van Datapanel configuraties.
De target audience hiervoor bestaat uit:  
- Developers van Stofloos: De medewerkers die op het moment deze configuraties handmatig schrijven (configurators van Datapanel).
- Stofloos klanten: De klanten van Stofloos zijn de uiteindelijke eindgebruikers van Datapanel.

De doelstellingen zijn:
- Het elimineren van handmatige JSON-configuratie om fouten te verminderen en tijd te besparen.
- Verbeter de bruikbaarheid, waardoor Datapanel configuraties toegankelijk worden voor minder technische gebruikers.
- Verbeter de algehele project efficiëntie en kwaliteit. 

## Functional Requirements

|FR|Gebruikersinterface|
|:-:|:----------------:|
|1|De user kan pagina’s en secties “op locatie” bewerken.|
|2|De user kan d.m.v. input json voor modelviews, pages, subpages en secties genereren.|
|3|De user kan de UI gebruiken binnen Datapanel.|
||Configuratie generatie|
|4|De user moet standaard configuraties kunnen genereren met één klik in de UI, op basis van no-code modellen.|

## Non-Functional Requirements
|NFR|Technology stack|
|:-:|:--------------:|
|1|Gebruik Lit Web Components voor ontwikkeling van de UI componenten.|
|2|Maak gebruik van Figma voor wireframes en prototypes.|
|3|Gebruik Bitbucket met Gitflow voor versiebeheer.|
|4|Ontwikkel de backend in Typescript.|
||Efficiëntie|
|5|De user hoeft niet handmatig json configuraties te schrijven.|
|6|De user kan zich makkelijk navigeren binnen de UI.|
|7|De user hoeft niets anders dan de UI te gebruiken om configuraties te maken.|
||Gebruiksvriendelijkheid|
|8|De user dient minimale technische kennis te hebben om gebruik te kunnen maken van de UI.|

## User Interfaces
__User Interactions:__ 
Gebruikers zullen stap voor stap de configuratie invullen. Hierbij valt te denken aan een soort wizard. Dit proces zal als volgt gaan, binnen Datapanel.  
- De gebruiker maakt een modelview aan. 
- De gebruiker maakt pagina’s aan die gebruikmaken van deze modelview.
- Subpagina’s worden toegevoegd aan de pagina’s.
- Secties worden toegevoegd aan de subpagina’s.  
Tijdens dit proces wordt er gedacht aan:

__Gebruiksvriendelijkheid__  
- De gebruikersinterface moet uiterst gebruiksvriendelijk zijn om zowel ontwikkelaars als eindklanten te bedienen, zelfs zonder technische expertise.
- Gebruiksvriendelijkheid moet de nadruk krijgen bij het ontwerpen van de UI.
- 
__Efficiëntie Configuratieproces__
- Het belangrijkste doel is het verbeteren van de efficiëntie van het proces van het maken van Datapanel configuraties.
- Gebruikers moeten in staat zijn om configuraties snel en nauwkeurig te maken zonder onnodige vertragingen of fouten.

## Testing Requirements
#### Testscenario's
Voor het valideren van de functionaliteiten van de Datapanel Configuratie Gebruikersinterface moeten gedetailleerde test scenario's worden gedefinieerd. Deze test scenario's omvatten:  
- Validatietests voor de gebruikersinterface om ervoor te zorgen dat de Datapanel configuraties correct worden gegenereerd.
- Usability tests om de toegankelijkheid voor eindgebruikers te beoordelen.
#### Acceptatiecriteria
De acceptatiecriteria stellen de voorwaarden vast waaraan het systeem moet voldoen om als succesvol te worden beschouwd. Deze criteria omvatten:  
- Alle testscenario's moeten succesvol worden doorlopen zonder kritieke fouten.
- De Datapanel Configuratie Gebruikersinterface moet efficiënt en gebruiksvriendelijk zijn, zodat zelfs gebruikers met beperkte technische kennis ermee kunnen werken.

De acceptatiecriteria zullen worden beoordeeld om te bepalen of het project met succes is afgerond en het systeem klaar is voor implementatie.


