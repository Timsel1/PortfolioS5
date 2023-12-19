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
Binnen de werkomgeving van Stofloos wordt Stofware ingezet, een geïntegreerde verzameling van gemeenschappelijke componenten die flexibel kunnen worden aangepast aan de specifieke behoeften van verschillende bedrijven. Stofware vormt de basis voor de ontwikkeling van maatwerkonderdelen, waarmee Stofloos zich kan concentreren op het leveren van oplossingen die naadloos aansluiten bij de unieke vereisten van hun klanten.

Een van de kernapplicaties binnen Stofware is Datapanel, dat fungeert als een cruciale schakel in het beheren en analyseren van gegevens binnen organisaties. Echter, het huidige proces binnen Stofloos om configuraties voor Datapanel handmatig in JSON te schrijven, presenteert een aanzienlijk probleem. Deze aanpak is niet alleen tijdrovend, maar introduceert ook het risico op fouten, wat de efficiëntie van het ontwikkelingsproces belemmert.

De kans in dit scenario is duidelijk: door een meer geoptimaliseerde en gebruiksvriendelijke methode te introduceren voor het genereren van Datapanel-configuraties, kan het ontwikkelingsproces aanzienlijk worden versneld. Deze verbetering zal niet alleen de productiviteit verhogen, maar ook de nauwkeurigheid en betrouwbaarheid van de configuraties verbeteren. Het doel is om een gestroomlijnde workflow te creëren die de ontwikkelaars in staat stelt zich te concentreren op de essentiële aspecten van maatwerk, zonder gehinderd te worden door omslachtige en foutgevoelige configuratieprocessen.  

Voor meer informatie kan [hier](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md#de-opdracht) in het projectplan worden gekeken.

## Doelstelling
Het hoofddoel van dit project is het ontwikkelen van een gebruiksvriendelijke user interface voor de configuratie van Datapanel. De focus ligt op het verminderen van fouten in het configuratieproces en het verkorten van de benodigde tijd om configuraties te maken. Een bijkomend doel is het vergroten van de toegankelijkheid, waardoor ook gebruikers met beperkte technische kennis in staat zijn om Datapanel te configureren.

Dit project streeft naar de optimalisatie van het configuratieproces, waardoor het minder foutgevoelig wordt en de efficiëntie toeneemt. Een succesvolle afronding van dit project betekent dat het configureren van Datapanel sneller, intuïtiever en minder complex wordt. Het uiteindelijke resultaat moet de ontwikkelaars in staat stellen om zich te concentreren op andere projecten, aangezien het configuratieproces van Datapanel gestroomlijnd en geoptimaliseerd is. Het succes wordt gemeten aan de hand van verbeterde snelheid en gebruiksvriendelijkheid bij het creëren van Datapanel-configuraties.

Meer informatie hierover is te vinden in het [projectplan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md).

## Onderzoeksvragen
Tijdens deze stage zullen er onderzoeken verricht moeten worden. Dit is om erachter te komen hoe het huidige project werkt, wat het probleem is, hoe hier al aan is gewerkt en wat er nog verwacht wordt. Verder moeten er misschien ook nog technische onderzoeken worden verricht. De belangrijkste onderzoeken voor dit project zijn op dit moment: 
- Hoe is Stofloos situatie verbeterd sinds Datapanel is opgezet?
- Hoe kan een gebruiksvriendelijke UI die het proces voor het creëren van Datapanel configuraties optimaliseert worden gemaakt?

Met deze onderzoeken wil ik er achter komen wat de huidige uitdagingen en beperkingen zijn bij het creëren van Datapanel configuraties en hoe ik dit kan oplossen op een manier waarbij alle end users hier profijt van hebben.
Voor het beantwoorden van deze onderzoeksvragen maak ik gebruik van meerdere kleine onderzoeken die door het proces van dit project ontstaan. Deze onderzoeken zijn [hier](https://github.com/Timsel1/PortfolioS5/tree/main/Nederlands/Documentatie/Research) te vinden.

## Aanpak
#### Agile methode:  
Dit project hanteert een Agile benadering, met name het Scrum-framework, om een flexibele en iteratieve ontwikkelingsaanpak te waarborgen. Hier zijn de belangrijkste aspecten van de Agile methode binnen deze stage:  
__Scrum Sprints:__
- Het ontwikkelproces is opgedeeld in sprints, waarin specifieke taken en doelstellingen binnen een afgebakende periode worden aangepakt. De sprints in dit project hebben een duur van twee weken.
__Scrum Oplevering:__
- Aan het einde van elke sprint vindt er een sprint oplevering plaats. Hier worden de opgeleverde resultaten gedemonstreerd en besproken, zodat de belanghebbenden op de hoogte zijn van de voortgang.
__Retrospective:__
- Na elke sprint oplevering wordt een retrospective gehouden. Tijdens deze sessie worden successen, uitdagingen en verbeterpunten besproken om voortdurende optimalisatie van het ontwikkelingsproces te waarborgen.
__Progress Tracking:__
- Voor het bijhouden van voortgang en taken wordt het ticketsysteem van Stofloos gebruikt. Dit systeem fungeert als een centrale hub voor het registreren en monitoren van taken gedurende het gehele project.
__Continue Feedback en Hulp:__
- Er wordt actief gebruikgemaakt van continue feedback en ondersteuning van de stagebegeleider en andere developers bij Stofloos. Dit garandeert dat ik tijdens de sprints op het juiste pad blijf en eventuele obstakels effectief worden aangepakt.
    
Deze Agile methode, met een focus op Scrum, biedt de flexibiliteit en transparantie die essentieel zijn voor een succesvolle ontwikkeling, waarbij een adaptieve aanpak wordt gehanteerd om snel en efficiënt te reageren op veranderende vereisten.
  
#### coderen:  
Voor dit project wordt een gestructureerde aanpak gehanteerd, waarbij projectmanagement cruciaal is voor een succesvolle ontwikkeling. De volgende methoden en praktijken worden toegepast:  
__Lokale Ontwikkeling:__  
- Het coderen gebeurt lokaal, waardoor ontwikkelaars in een gecontroleerde omgeving kunnen werken voordat wijzigingen naar de hoofdcode worden overgebracht.
__Gitflow:__  
- Gitflow wordt geïmplementeerd als ontwikkelingsstrategie. Dit maakt het mogelijk om parallel aan nieuwe functies te werken, bugs op te lossen en wijzigingen door te voeren, terwijl de stabiliteit van de productiecode behouden blijft.  
__Git Commits en Commit Message Conventies:__
- Start commits met specifieke woorden zoals "Add", "Fix", "Update", enz. bijvoorbeeld: "Add new feature" of "Fix bug in data processing".
- Alle commit messages worden in het Engels geschreven.
- Houd het onderwerp van de commit kort en bondig, met maximaal 50 karakters.
- Beperk de inhoud van de commit message tot maximaal 72 karakters.
__Veiligheid in Productiecode:__  
- Door gebruik te maken van Gitflow wordt gewaarborgd dat er geen onbedoelde wijzigingen in de productiecode terechtkomen tijdens het ontwikkelingsproces. De ontwikkeling verloopt georganiseerd en fouten worden geminimaliseerd.
__Frontend Testing:__  
- De frontend van de user interface wordt grondig gecontroleerd, Dit wordt gedaan door middel van code- en peer reviews om de kwaliteit van de code te waarborgen. Usability tests worden uitgevoerd om de gebruiksvriendelijkheid van de interface te evalueren.
__Backend Testing:__
- Voor de backend worden unit tests gebruikt om de functionaliteit van afzonderlijke eenheden code te controleren. Dit garandeert de betrouwbaarheid en consistentie van de backend-functionaliteit.

Deze projectmanagement benadering stelt het ontwikkelingsteam in staat om op een georganiseerde en gestructureerde manier aan het project te werken, waarbij code-integriteit wordt behouden en zowel frontend als backend uitvoerig worden getest.

#### Onderzoeken:  
De onderzoeken die worden gedaan, zullen worden uitgevoerd aan de hand van de [DOT methode](https://ictresearchmethods.nl/). Voor meer informatie hierover heb ik in de tabellen van ["Logische Beschrijving van het Proces en de Resultaten:"](#logische-beschrijving-van-het-proces-en-de-resultaten) gelinkt naar de bijbehorende secties van de methodes (library, field, lab, showroom en workshop).

__Hoe heb ik gebruik gemaakt van de DOT methode:__  
In mijn research/dev logs hou ik een structuur aan die goed past bij deze methode, deze structuur bestaat uit 5 kopjes:
- Een hoofdvraag
  - Dit gaat meestal over de feature waar ik aan ga werken, hier wordt ook beschreven waarom hier aan wordt gewerkt.
- Hoe heb ik dit opgelost
  - beschrijft het onderzoek dat ik heb gedaan naar een bepaald onderwerp en welke methode ik heb gebruikt voor dit onderzoek.
- Wat is het resultaat
  - Geeft het resultaat van mijn onderzoek en implementatie weer.
- Wat is de kwaliteit van het resultaat
  - Dit beschrijft hoe ik mijn resultaat heb gevalideerd en benoemd de bijbehorende methode.
- Wat is de volgende stap
  - Hier beschrijf ik de volgende stap die ik ga nemen nu ik dit resultaat heb.

Deze structuur past goed bij de DOT methode omdat, door dit aan te houden, ik altijd de aspecten van onderzoek, realisatie en validatie aantoon.

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




