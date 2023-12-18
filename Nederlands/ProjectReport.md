# Project Report

INTERNSHIP PORTFOLIO HBO-ICT

FONTYS UNIVERSITY OF APPLIED SCIENCES

|Student:||
|:--------:|:-:|
|Family name , initials:|Meijvogel, T.M.|
|Student number:|462739|
|project period: (from – till)|04/09/2023 - 26/01/2023|
|**Company:**||
|Name company/institution:|Stofloos|
|Department:|Software|
|Address:|Klokgebouw 269, 5716 AC Eindhoven|
|**Company tutor:**||
|Family name, initials:|Spijker, J.S.|
|Position:|Software Engineer|
|**University tutor:**||
|Family name , initials:|Coenen, F.W.J.C.|
|**Final portfolio:**||
|Title:||
|Date: ||

## Introduction
Deze introductie dient als opening van dit projectrapport. Het schetst het doel en de doelstellingen van het project en biedt een uitgebreid overzicht van de inhoud van dit rapport.  
- [Probleem en Kans:](#probleem-en-kans)   
  Deze sectie presenteert de context en achtergrondinformatie die heeft geleid tot de start van het project. Het benadrukt het probleem, de kans of de behoefte die het project beoogt aan te pakken.
- [Doelstelling:](#doelstelling)  
  Duidelijke en meetbare doelstellingen worden uiteengezet, waaruit blijkt wat het project wil bereiken. Deze doelstellingen fungeren als leidende principes gedurende de uitvoering van het project.
- [Onderzoeksvragen:](#onderzoeksvragen)  
  Beschrijft de specifieke vragen die het onderzoek zal beantwoorden. Deze vragen begeleiden de richting van het onderzoek.
- [Aanpak:](#aanpak)  
  Legt kort de benadering, methoden en technieken uit die worden gebruikt om het project uit te voeren. Het biedt een overzicht van de werkstroom van het project.
- [Logische Beschrijving van het Proces en de Resultaten:](#logische-beschrijving-van-het-proces-en-de-resultaten)  
  Geeft een gedetailleerde chronologische beschrijving van de stappen die zijn genomen tijdens het project, evenals de verkregen resultaten.
- [Conclusie:](#conclusie)  
  Samenvatting van de belangrijkste bevindingen en resultaten die voortvloeien uit het project.
- [Aanbevelingen:](#aanbevelingen)  
  Suggesties voor mogelijke acties of volgende stappen op basis van de bevindingen van het project.  
- [Persoonlijke Reflectie:](#persoonlijke-reflectie)  
  Reflectie op persoonlijke ervaringen, uitdagingen en leermomenten tijdens het uitvoeren van het project.


## Probleem en kans
Op dit moment worden bij Stofloos Datapanel configuraties handmatig in JSON geschreven, dit is tijdrovend en vatbaar voor fouten. Er is hier een kans om de efficiëntie van het ontwikkelingsproces te versnellen en gebruiksvriendelijker te maken. Voor meer informatie kan [hier](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md#de-opdracht) in het projectplan worden gekeken.

## Doelstelling
Het doel van dit project is om een gebruiksvriendelijke user interface voor het configureren van Datapanel te maken. Dit zal het proces minder foutgevoelig maken en de benodigde tijd verminderen. Ook moet het ervoor zorgen dat het configureren van Datapanel toegankelijk is voor gebruikers met een mindere technische kennis.
Wanneer deze processen gestroomlijnd zijn is er meer tijd om te werken aan de andere projecten, wanneer hier meer tijd voor is zal de kwaliteit die Stofloos biedt nog hoger worden.
Meer informatie hierover is te vinden in het [projectplan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md).

## Onderzoeksvragen
Tijdens deze stage zullen er onderzoeken verricht moeten worden. Dit is om erachter te komen hoe het huidige project werkt, wat het probleem is, hoe hier al aan is gewerkt en wat er nog verwacht wordt. Verder moeten er misschien ook nog technische onderzoeken worden verricht. De belangrijkste onderzoeken voor dit project zijn op dit moment: 
- Hoe is Stofloos situatie verbeterd sinds Datapanel is opgezet?
- Hoe kan een gebruiksvriendelijke UI die het proces voor het creëren van Datapanel configuraties optimaliseert worden gemaakt?

Met deze onderzoeken wil ik er achter komen wat de huidige uitdagingen en beperkingen zijn bij het creëren van Datapanel configuraties en hoe ik dit kan oplossen op een manier waarbij alle end users hier profijt van hebben.
Voor het beantwoorden van deze onderzoeksvragen maak ik gebruik van meerdere kleine onderzoeken die door het proces van dit project ontstaan. Deze onderzoeken zijn [hier](https://github.com/Timsel1/PortfolioS5/tree/main/Nederlands/Documentatie/Research) te vinden.

## Aanpak
Voor een volledige beschrijving van de aanpak voor dit project kan [hier](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md#aanpak-en-planning) worden gekeken in het [projectplan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md). Om dit kort samen te vatten:  
#### Agile methode:  
Tijdens deze stage wordt er gewerkt met scrum, progres en taken worden bijgehouden met Stofloos’ ticketsysteem. Met scrum werk je in sprints, mijn sprints zijn 2 weken lang, aan het eind van elke sprint is er een sprint oplevering, na deze sprint oplevering wordt een retrospective ingevuld. Tijdens dit project zal er continu feedback en hulp worden gevraagd aan de stagebegeleider en andere developers bij Stofloos, om te garanderen dat tijdens de sprints ook correct.  
#### coderen:  
Er wordt lokaal gecodeerd, er wordt gebruikgemaakt van gitflow, op deze manier gaat er niets kapot in de productiecode wanneer er wordt gewerkt aan het project.
De frontend wordt getest met code/peer reviews en usability tests, voor de backend zullen unit tests worden gebruikt. 
#### Onderzoeken:  
De onderzoeken die worden gedaan, zullen worden uitgevoerd aan de hand van de [DOT methode](https://ictresearchmethods.nl/).

## Logische beschrijving van het proces en de resultaten
Dit is mijn volledige proces op chronologische volgorde met bijbehorende onderzoeksmethodes.

### Opzetten van het project 
In de startfase van mijn stage heb ik gewerkt aan documenten die het resultaat zijn van mijn onderzoek naar de requirements van mijn project en mijn strategie voor de vervulling van deze opdracht. Gedurende deze fase heb ik zorgvuldig gewerkt aan het opstellen van cruciale documenten, waaronder mijn projectplan, requirements document en een survey.  
Het projectplan schetst een uitgebreide strategie voor de implementatie van het project, waarbij ik rekening houd met de gestelde doelen, mijlpalen en benodigde middelen.  
Het requirements document biedt een gedetailleerde analyse van de functional en non-functional requirements die essentieel zijn voor het succesvol voltooien van mijn project. Hierin worden zorgvuldig geformuleerde specificaties en criteria uiteengezet, waarmee ik de basis leg voor een gestructureerde en doelgerichte development fase.  
De survey is gemaakt om te peilen wat er nodig is voor mijn opdracht. Deze survey is bedoeld om een goed beeld te krijgen van wat er wordt verwacht, wat de uitdagingen zijn en welke specifieke requirements belangrijk zijn binnen het project. De antwoorden die ik heb gekregen helpen me om beter geïnformeerde beslissingen te nemen terwijl het project zich verder ontwikkelt.


|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Projectplan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md)|Expert interview|Explore user requirements, Problem analysis| | |Requirements prioritization|
|[Research (Kwaliteits)eisen](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/Kwaliteitseisen.md)|Expert interview|Survey| | | |
|[Requirements Document](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/RequirementsDocument.md)| | | | |Requirements prioritization|

### Designing en Prototyping
Deze documenten bieden een diepgaand inzicht in mijn ontwerpproces voor de gebruikersinterface (UI). In samenwerking met gespecificeerde eisen en verzamelde feedback heb ik de UI geconceptualiseerd, met een focus op intuïtieve gebruikerservaring. Wireframes en prototypes zijn ontwikkeld om functionaliteiten te visualiseren en gebruikersinteracties te verkennen. De documenten bevatten gedetailleerde uitleg van ontwerpkeuzes en lay-out overwegingen. Iteraties en evolutie zijn vastgelegd op basis van interne beoordelingen en feedback van belanghebbenden, waaronder ontwikkelaars. De prototyping fase omvatte interactieve modellen die niet alleen het ontwerp valideerden, maar ook dienden als referentie voor mij tijdens de ontwikkelfase.

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Gebruiksvriendelijke UI (1)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI1.md)|Expert interview|Survey| | | |
|[Gebruiksvriendelijke UI (2)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI2.md)|Expert interview||||Prototyping|
|[Gebruiksvriendelijke UI (3)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI3.md)|Available Product Analysis, Expert interview| | | |Prototyping|
|[Gebruiksvriendelijke UI (4)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI4.md)|Expert interview |Survey|Usability testing |Peer review | |
|[Design Document](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/DesignDocument.md)| | |A/B testing| |IT architecture sketching, Prototyping|

### Ontwikkeling van de UI
In de documenten die betrekking hebben op de ontwikkeling van de gebruikersinterface (UI), volg ik een gestructureerde aanpak, waarbij elke fase gericht is op het beantwoorden van cruciale vragen en het leveren van waardevolle inzichten:

__1. Hoofdvraag en Doelstellingen:__  
- Hier stel ik de hoofdvraag op, die dienst doet als leidende richtlijn voor het gehele ontwikkelingsproces. Onder deze hoofdvraag verduidelijk ik het 'waarom' achter de feature en de beoogde doelstellingen.

__2. Hoe heb ik dit opgelost:__  
- Ik beschrijf gedetailleerd hoe ik de hoofdvraag heb aangepakt, met speciale aandacht voor mijn onderzoeksmethoden. 

__3. Wat is het resultaat:__  
- In deze sectie laat ik de daadwerkelijke resultaten zien in de vorm van afbeeldingen en gifs. Hiermee wil ik de lezer een visueel inzicht geven in de ontwikkelde UI-componenten en functionaliteiten.

__4. Wat is de kwaliteit van het resultaat:__  
- Ik beoordeel de kwaliteit van de behaalde resultaten en beschrijf hoe ik dit heb gevalideerd. Dit omvat tests en evaluaties die zijn uitgevoerd om te waarborgen dat de UI voldoet aan gestelde vereisten en gebruiksscenario's.

__5. Wat is de volgende stap nu ik dit resultaat heb:__  
- Tot slot, beschrijf ik de volgende stappen nu het resultaat is behaald. Dit omvat mogelijke optimalisaties, toekomstige functionaliteiten, of aanvullende stappen die genomen moeten worden om het project verder te ontwikkelen.

Door deze structuur te volgen, bieden de documenten niet alleen een duidelijk chronologisch overzicht van het ontwikkelingsproces, maar benadrukken ze ook de essentiële aspecten van de aanpak, de resultaten, hun kwaliteit, validatie, en de stappen die volgen na het behalen van het resultaat.


|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Generieke Cards](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIRealisatie/GeneriekeCards.md)|Design pattern research, Expert interview| | | |Code review |
|[Navigation Tabs](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIRealisatie/NavigationTabs.md)| | | | | |
|[Conditional Json Schema](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIRealisatie/ConditionalJsonSchema.md)| | | | | |




