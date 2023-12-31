# Project Report

INTERNSHIP PORTFOLIO HBO-ICT

FONTYS UNIVERSITY OF APPLIED SCIENCES

|Student:||
|:--------:|:-:|
|Family name , initials:|Meijvogel, T|
|Student number:|462739|
|project period: (from – till)|04/09/2023 - 26/01/2023|
|**Company:**||
|Name company/institution:|Stofloos|
|Department:|Software|
|Address:|Klokgebouw 269, 5716 AC Eindhoven|
|**Company tutor:**||
|Family name, initials:|Spijker, J.J.|
|Position:|Software Developer|
|**University tutor:**||
|Family name , initials:|Coenen, F.W.J.|
|**Final portfolio:**||
|Title:|S5 Portfolio Tim Meijvogel|
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
- [Conclusie en Aanbevelingen:](#conslusie-en-aanbevelingen)  
  Samenvatting van de belangrijkste bevindingen en resultaten die voortvloeien uit het project en suggesties voor mogelijke acties of volgende stappen op basis van de bevindingen van het project. 
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
### [Hoe kan een gebruiksvriendelijke UI die het proces voor het creëren van Datapanel configuraties optimaliseert worden gemaakt?](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIVoorOptimalisatieDatapanelConfiguraties.md) 
In mijn rol tijdens de stage heb ik me gericht op het optimaliseren van het creatieproces van Datapanel configuraties, met als primaire doelstelling het ontwerpen van een gebruiksvriendelijke user interface (UI). Om dit te realiseren heb ik dit onderzoek opgezet, met vragen die ik over de loop van mijn stage kan beantwoorden.

#### Wat zijn de huidige uitdagingen en beperkingen bij het creëren van Datapanel configuraties?  
Het identificeren van de huidige uitdagingen en beperkingen bij het creëren van Datapanel configuraties was een cruciale stap. Door middel van een survey en interviews met stakeholders kon ik specifieke punten in kaart brengen die aandacht vereisten. Deze bevindingen dienden als uitgangspunt voor verdere inspanningen om optimalisaties door te voeren.

#### Wat zijn de belangrijkste functionaliteiten en interacties die vereist zijn in de UI voor het maken van Datapanel configuraties?  
Samen met technische experts en eindgebruikers (de stakeholders) heb ik de belangrijkste functionaliteiten en interacties vastgesteld die essentieel waren voor de UI. Dit proces omvatte, zoals eerder beschreven, een survey, interviews en het maken van wireframes en prototypes, waarbij ik voortdurend iteraties doorliep om de interface te verfijnen. Het resultaat was een intuïtieve UI die gericht was op efficiëntie en gebruiksgemak.

#### Hoe worden de in de UI gemaakte configuraties geëxporteerd naar JSON?  
Het onderzoek naar de exportfunctionaliteit werd uitgevoerd om een beter inzicht te krijgen van de technische aspecten en het proces achter het exporteren van configuraties naar JSON. Door te focussen op dit specifieke onderdeel kon ik een beter begrip ontwikkelen van hoe de data wordt omgezet en overgedragen, wat bijdroeg aan een diepgaande kennis van het programma als geheel.

#### Hoe worden de opgeslagen configuraties geïmporteerd naar de UI?  
Het onderzoek naar het importeren van opgeslagen configuraties had als doel de integratieprocessen beter te begrijpen en te analyseren. Ondanks dat de functionaliteit al geïmplementeerd was, bood het onderzoek de mogelijkheid om dieper in te gaan op de wijze waarop configuraties worden opgehaald, geparsed en geïntegreerd in de gebruikersinterface. Hierdoor kon ik mijn algehele begrip van de technische kant van het programma verbeteren.

#### Hoe wordt ervoor gezorgd dat de UI gebruiksvriendelijk blijft?  
Om de gebruiksvriendelijkheid van de UI te waarborgen, zijn uitgebreide usability-tests uitgevoerd voor zowel het prototype als de uiteindelijke UI. Tijdens de Scrum-opleveringen is feedback verzameld. De optimalisatie van de UI is voortgekomen uit aanpassingen en verbeteringen die zijn doorgevoerd op basis van beschikbare input. Deze aanpak maakte het mogelijk om de UI dynamisch aan te passen aan de actuele behoeften van gebruikers.

### [Hoe is Stofloos situatie verbeterd sinds Datapanel is opgezet?](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/StofloosVerbeteringSindsDatapanel.md)  
Het onderzoek naar de verbeteringen sinds Datapanel is opgezet is van belang om inzicht te verkrijgen in de impact die het heeft gehad op de situatie bij Stofloos. Dit houdt in het identificeren van specifieke verbeteringen, zoals verhoogde efficiëntie, snellere toegang tot gegevens en verbeterde functionaliteiten. Het begrijpen van deze verbeteringen dient als basis voor verdere optimalisaties en groei binnen de organisatie.

#### Welke uitdagingen waren er voordat Datapanel was opgezet? 
Onderzoek naar de uitdagingen die Stofloos vóór de oprichting van Datapanel heeft ervaren is noodzakelijk om de aanleiding achter het ontstaan van het platform te begrijpen. Het richt zich op de specifieke knelpunten die Stofloos heeft gemotiveerd om een oplossing te creëren. Dit inzicht biedt waardevolle context voor het begrijpen van de initiële behoeften en doelstellingen van Datapanel.

#### Wat waren de voorafgaande verbeteringen aan Datapanel en waarom waren deze nodig? 
Het onderzoek naar eerdere verbeteringen aan Datapanel is gericht op het begrijpen van het voorafgaande verbeteringen aan het platform. Dit omvat wijzigingen en aanpassingen die zijn doorgevoerd sinds het is opgezet. Het identificeert de specifieke aspecten die zijn verbeterd en de redenen daarachter. Deze analyse helpt bij het vaststellen van behoeften die de verdere ontwikkeling van Datapanel sturen.

#### Hoe ziet de huidige situatie eruit? 
Een gedetailleerde blik op de huidige situatie van Stofloos met betrekking tot het gebruik van Datapanel biedt een actueel beeld van de impact van het platform op dagelijkse bedrijfsactiviteiten. Het omvat de functionaliteiten, prestaties en het algehele gebruiksgemak van Datapanel. Dit inzicht is cruciaal voor het beoordelen van de effectiviteit van het huidige systeem.

#### Is de huidige situatie de ideale situatie? 
Het onderzoek naar de vraag of de huidige situatie als ideaal wordt beschouwd, richt zich op het evalueren van de prestaties van Datapanel in vergelijking met de gestelde doelen en verwachtingen. Het omvat feedback van gebruikers om te bepalen welke aanpassingen of verbeteringen nodig zijn om de optimale functionaliteit en waarde te bereiken. 

Met deze onderzoeken wil ik er achter komen wat de huidige uitdagingen en beperkingen zijn bij het creëren van Datapanel configuraties en hoe ik dit kan oplossen op een manier waarbij alle end users hier profijt van hebben.
Voor het beantwoorden van deze onderzoeksvragen maak ik gebruik van meerdere kleine onderzoeken die door het proces van dit project ontstaan.

## Aanpak
### Agile methode:  
In de dynamische wereld van softwareontwikkeling is een flexibele en iteratieve aanpak van cruciaal belang. Dit project omarmt de principes van Agile, met name het gebruik van het Scrum-framework, om een adaptieve ontwikkelingsbenadering te waarborgen. Binnen deze context vormen verschillende aspecten van de Agile methode de basis van mijn stage-ervaring.

Het ontwikkelproces is gestructureerd in Scrum Sprints, waarin specifieke taken en doelstellingen binnen een afgebakende periode van twee weken worden aangepakt. Deze korte en gerichte sprints bieden niet alleen een efficiënte voortgang, maar stellen mij in staat om snel te reageren op veranderende prioriteiten en vereisten.

Aan het einde van elke sprint vindt een Scrum Oplevering plaats, een cruciaal moment waarop de behaalde resultaten worden gedemonstreerd en besproken. Hier delen we niet alleen de voortgang met belanghebbenden, maar bieden we ook de mogelijkheid voor directe feedback. Bovendien deel ik tijdens deze sessies mijn sprint planning voor de volgende sprint, waardoor de belanghebbenden een vooruitblik krijgen op de te verwachten ontwikkelingen en prioriteiten.

Een waardevolle praktijk die na elke sprint wordt toegepast, is de Retrospective. Deze reflectieve sessies bieden de gelegenheid om successen te vieren, uitdagingen te identificeren en verbeterpunten te bespreken. Het continue streven naar optimalisatie van het ontwikkelingsproces is van essentieel belang voor mijn stage-ervaring.

Om de voortgang en taken gestructureerd bij te houden, maak ik gebruik van het ticketsysteem van Stofloos. Deze centrale hub fungeert als een onmisbare schakel voor het registreren en monitoren van taken gedurende het gehele project.

Een aspect dat de wendbaarheid versterkt, is de actieve betrokkenheid van continu feedback en ondersteuning van zowel de stagebegeleider als andere ervaren developers bij Stofloos. Deze samenwerking waarborgt niet alleen de juiste koers tijdens de sprints, maar zorgt er ook voor dat eventuele obstakels snel en effectief worden aangepakt.

Deze adaptieve Agile methode, met een centrale focus op Scrum, biedt de flexibiliteit en transparantie die essentieel zijn voor een succesvolle ontwikkeling. Het stelt mij in staat om snel te schakelen, efficiënt te reageren op veranderingen en voortdurend waarde toe te voegen aan het project.

  
### coderen:  
In het domein van coderen vormt een gestructureerde aanpak de ruggengraat van ons project, met projectmanagement als essentieel ingrediënt voor succesvolle ontwikkeling. Hier maken we gebruik van verschillende methoden en best practices, elk met een specifieke rol en bijdrage aan het geheel.

Het coderingsproces begint op lokaal niveau, een doordachte aanpak waarmee ik in een gecontroleerde omgeving werk voordat mijn wijzigingen naar de hoofdcode worden overgebracht. Dit biedt niet alleen een veilige speelplaats voor experimenten, maar garandeert ook een solide basis voordat mijn bijdragen de bredere code basis beïnvloeden.

We volgen de Gitflow, een systematische implementatie als ontwikkelingsstrategie. Dit stelt mij in staat om parallel aan nieuwe functies te werken, bugs op te lossen en wijzigingen door te voeren, terwijl we de stabiliteit van de productiecode behouden. Mijn digitale werkplek bevindt zich in een eigen branch genaamd "feature/configuratie-ui", waar mijn feature zorgvuldig wordt gevormd voordat deze aan het geheel wordt toegevoegd.

Binnen mijn coderingspraktijk volg ik nauwgezet de Git Commits en Commit Message Conventies. Ik initieer mijn commits met specifieke woorden zoals "Add", "Fix", "Update", en andere. Korte, krachtige berichten, beperkt tot maximaal 50 karakters, belichamen mijn streven naar code-integriteit. Ik houd de inhoud van de commit messages eveneens beknopt, met een maximum van 72 karakters, om helderheid en focus te behouden.

In mijn toewijding aan de veiligheid van de productiecode speelt Gitflow een cruciale rol als betrouwbare bewaker, die ervoor zorgt dat onopzettelijke wijzigingen de kern van de productiecode niet beïnvloeden. Het ontwikkelingsproces volgt een gestructureerd traject, waarbij fouten tot een minimum worden beperkt en de integriteit van de code behouden blijft.

Zowel de frontend als de backend ondergaan een zorgvuldige inspectie. De frontend wordt onderworpen aan kritische code- en peer reviews, waar de code en de algehele kwaliteit ervan nauwlettend worden gecontroleerd. Usability tests voegen een menselijk perspectief toe aan deze technologische evaluatie, waarbij niet alleen de gebruiksvriendelijkheid maar ook de efficiëntie van de interface wordt beoordeeld.

Aan de backend-zijde wordt de betrouwbaarheid en consistentie van de functionaliteit gegarandeerd door middel van unit tests. Deze kleine proefstukken van functionaliteit worden zorgvuldig getest, waardoor de robuustheid van het gehele systeem wordt versterkt.

Deze gecoördineerde benadering van projectmanagement stelt me in staat om op een georganiseerde en gestructureerde manier aan het project te werken. In deze ontwikkelingsfase blijft de code-integriteit behouden, en zowel frontend als backend ondergaan grondige tests, wat resulteert in kwaliteit in ons ontwikkelingsproces.


### Onderzoeken:  
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
### Analyse
#### UI
In de startfase van mijn stage heb ik gewerkt aan documenten die het resultaat zijn van mijn onderzoek naar de requirements van mijn project en mijn strategie voor de vervulling van deze opdracht. Gedurende deze fase heb ik zorgvuldig gewerkt aan het opstellen van cruciale documenten, waaronder mijn projectplan, requirements document en een survey.  

Het projectplan schetst een uitgebreide strategie voor de implementatie van het project, waarbij ik rekening houd met de gestelde doelen, mijlpalen en benodigde middelen.  

Het requirements document biedt een gedetailleerde analyse van de functional en non-functional requirements die essentieel zijn voor het succesvol voltooien van mijn project. Hierin worden zorgvuldig geformuleerde specificaties en criteria uiteengezet, waarmee ik de basis leg voor een gestructureerde en doelgerichte development fase.  

De survey is gemaakt om te peilen wat er nodig is voor mijn opdracht. Deze survey is bedoeld om een goed beeld te krijgen van wat er wordt verwacht, wat de uitdagingen zijn en welke specifieke requirements belangrijk zijn binnen het project. De antwoorden die ik heb gekregen helpen me om beter geïnformeerde beslissingen te nemen terwijl het project zich verder ontwikkelt.

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Projectplan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Projectplan.md)|Expert interview|Explore user requirements, Problem analysis| | |Requirements prioritization|
|[Research (Kwaliteits)eisen](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/Kwaliteitseisen.md)|Expert interview|Survey| | | |
|[Requirements Document](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/RequirementsDocument.md)| | | | |Requirements prioritization|

#### Backend
In een van de laatste stadia van het project heb ik mij toegewijd aan de ontwikkeling van de backend. Dit proces begon met een kort maar grondig analyse stadium. In nauwe samenwerking met mijn stagebegeleider hebben we de opdracht uitgebreid besproken en de benodigde requirements vastgesteld. Na deze bespreking heb ik de vastgestelde requirements gedocumenteerd om een helder en gestructureerd overzicht te creëren van de te implementeren functionaliteiten. Deze gedocumenteerde requirements vormden de handleiding voor de verdere stappen in het ontwikkelingsproces, en dienen als referentiepunt voor mijzelf tijdens de uitvoering van de backend-ontwikkeling.

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Projectplan Uitbreiding Backend](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/5.%20Opzet%20Backend/ProjectplanUitbreidingBackend.md)|Expert interview|Explore user requirements| | |Requirements prioritization|

### Design
Deze documenten bieden een diepgaand inzicht in mijn ontwerpproces voor de gebruikersinterface (UI). In samenwerking met gespecificeerde eisen en verzamelde feedback heb ik de UI geconceptualiseerd, met een focus op intuïtieve gebruikerservaring. Wireframes en prototypes zijn ontwikkeld om functionaliteiten te visualiseren en gebruikersinteracties te verkennen. De documenten bevatten gedetailleerde uitleg van ontwerpkeuzes en lay-out overwegingen. Iteraties en evolutie zijn vastgelegd op basis van interne beoordelingen en feedback van belanghebbenden, waaronder ontwikkelaars. De prototyping fase omvatte interactieve modellen die niet alleen het ontwerp valideerden, maar ook dienden als referentie voor mij tijdens de ontwikkelfase.

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Gebruiksvriendelijke UI (1)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI1.md)|Expert interview|Survey| | | |
|[Gebruiksvriendelijke UI (2)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI2.md)|Expert interview||||Prototyping|
|[Gebruiksvriendelijke UI (3)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI3.md)|Available Product Analysis, Expert interview| | | |Prototyping|
|[Gebruiksvriendelijke UI (4)](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIDesign/GebruiksvriendelijkeUI4.md)|Expert interview |Survey|Usability testing |Peer review | |
|[Design Document](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/DesignDocument.md)| | |A/B testing| |IT architecture sketching, Prototyping|

### Realisatie
#### UI
In mijn streven naar een verbeterde gebruikersinterface voor het Datapanel-project heb ik diverse features toegevoegd, elk gedocumenteerd in afzonderlijke rapporten. Deze documentatie biedt niet alleen een gedetailleerde beschrijving van de implementatie, maar geeft ook inzicht in de motivatie achter elke toevoeging, waarbij de focus ligt op het 'waarom' achter de ontwikkeling keuzes. Visuele representaties in de vorm van afbeeldingen en gifs worden ingezet om de impact van elke feature te demonstreren.

Elk rapport omvat een evaluatie van de kwaliteit van de behaalde resultaten, waarbij de nadruk ligt op het voldoen aan gestelde eisen en het handhaven van normen voor een optimale gebruikservaring. 

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Generieke Cards](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIRealisatie/GeneriekeCards.md)|Design pattern research, Expert interview| | | |Code review |
|[Navigation Tabs](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIRealisatie/NavigationTabs.md)| | | | | |
|[Conditional Json Schema](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIRealisatie/ConditionalJsonSchema.md)| | | | | |

#### Backend
Met de toevoeging van mijn configuratie service aan het Datapanel-project heb ik diverse functionaliteiten geïmplementeerd en gedocumenteerd in afzonderlijke rapporten. Deze documentatie biedt niet alleen een diepgaande beschrijving van de implementatie, maar werpt ook licht op de motivatie achter elke toevoeging, met de nadruk op de overwegingen die hebben geleid tot specifieke ontwikkelingskeuzes. Visuele representaties, zoals afbeeldingen en gifs, worden ingezet om de impact van elke nieuwe functie helder te presenteren.

Ieder rapport bevat een beoordeling van de behaalde resultaten, met speciale aandacht voor het voldoen aan vooraf gestelde eisen en het handhaven van normen voor een optimale backend-ervaring. 

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
| | | | | | |


### Validatie
#### UI
Voor de validatie van de gebruikersinterface (UI) binnen het Datapanel-project zijn specifieke procedures en documenten opgesteld. Deze omvatten het Usability Test Plan, Test Tasks, en het Usability Test Report. Elk van deze documenten speelt een cruciale rol in het waarborgen van de effectiviteit, efficiëntie en gebruikersvriendelijkheid van de ontwikkelde UI. Ze bieden een gestructureerde aanpak voor het evalueren van de UI-prestaties en geven inzicht in hoe gebruikers interageren met de interface. Door deze documenten wordt een gefocuste en methodische benadering gegarandeerd om de kwaliteit van de gebruikerservaring te valideren.

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Usability Test Plan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/4.%20UI%20Validatie/UsabilityTestPlanUI.md)| | | | | |
|[Test Tasks](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/4.%20UI%20Validatie/UsabilityTestTasks.md)| | | | | |

#### Backend
Voor de backend-validatie in het Datapanel-project wordt er gebruikgemaakt van unit tests, waarover wordt gedocumenteerd. Elk testgeval beschrijft niet alleen wat de test precies doet, maar geeft ook inzicht in de redenen achter het uitvoeren van die specifieke test. Deze documentatie biedt een helder begrip van de functionaliteiten die worden getest en waarom deze tests van belang zijn voor het waarborgen van de betrouwbaarheid en consistentie van de backend-functionaliteiten. Het doel is om een transparante en goed gemotiveerde validatieprocedure te hanteren, waardoor de kwaliteit van de backend wordt geoptimaliseerd.

|Document|[Library](https://ictresearchmethods.nl/library/)|[Field](https://ictresearchmethods.nl/Field/)|[Lab](https://ictresearchmethods.nl/Lab/)|[Showroom](https://ictresearchmethods.nl/Showroom/)|[Workshop](https://ictresearchmethods.nl/Workshop/)|
|:------:|:-----:|:---:|:-:|:------:|:------:|
|[Usability Test Plan](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/4.%20UI%20Validatie/UsabilityTestPlanUI.md)| | | | | |
|[Test Tasks](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/4.%20UI%20Validatie/UsabilityTestTasks.md)| | | | | |

## Conslusie en Aanbevelingen
In deze conclusie worden de resultaten van het stageproject samengevat, met de nadruk op de toegevoegde waarde voor het bedrijf en de stakeholders. De verworven inzichten, optimalisaties en ontwikkelingen binnen het project worden besproken, gevolgd door gerichte aanbevelingen voor verdere verbeteringen en groei. De conclusie biedt een overkoepelende evaluatie van de bereikte resultaten en benadrukt de relevantie van de bijdrage aan de organisatie en belanghebbenden.

### Resultaten:
Het optimaliseren van de gebruikersinterface (UI) voor het Datapanel-configuratieproces heeft geresulteerd in een gestroomlijnde workflow en verhoogde efficiëntie voor eindgebruikers. De ontwikkelde UI biedt een intuïtieve ervaring, wat de productiviteit van de gebruikers aanzienlijk heeft verbeterd. Het bestaande systeem, inclusief de exportfunctionaliteit naar JSON, draagt bij aan een naadloze gegevensuitwisseling tussen de geoptimaliseerde UI en de service die standaardconfiguraties genereert voor alle modellen in de database. Deze verbeteringen dragen bij aan een effectievere configuratiebeheer en gegevensuitwisseling binnen de organisatie.

De uitgevoerde onderzoeken hebben ook aanzienlijk bijgedragen aan het succes van het stageproject. De usability-tests, specifiek gericht op de geoptimaliseerde gebruikersinterface (UI) voor het Datapanel-configuratieproces, hebben waardevolle inzichten opgeleverd. Door middel van deze tests werd niet alleen de gebruiksvriendelijkheid van de UI geëvalueerd, maar werden ook specifieke knelpunten en verbeterpunten geïdentificeerd.

De resultaten van de usability-tests hebben directe invloed gehad op de verdere ontwikkeling van de UI. Aanpassingen en optimalisaties zijn doorgevoerd op basis van de feedback die is verkregen tijdens deze tests, wat heeft bijgedragen aan een nog intuïtievere en efficiëntere gebruikerservaring.

In het bijzonder heeft de aandacht voor gebruikerservaring en de implementatie van verbeteringen op basis van usability-tests niet alleen geleid tot een betere UI maar heeft het ook bijgedragen aan de algehele waarde van het project voor het bedrijf. Het vermogen om te reageren op de specifieke behoeften en verwachtingen van gebruikers is een cruciaal aspect geweest van het succes van het project tijdens deze stageperiode.

### Toegevoegde Waarde voor het Bedrijf:
Deze optimalisaties hebben een aanzienlijke impact gehad op de bedrijfsprocessen, waarbij de tijd die voorheen nodig was voor het creëren van Datapanel configuraties aanzienlijk is verminderd. Voorheen werd er geconfronteerd met uitdagingen met betrekking tot het handmatig schrijven van de configuraties, wat resulteerde in een langere doorlooptijd en een hogere belasting voor de gebruikers. De geoptimaliseerde gebruikersinterface (UI) heeft echter een aanzienlijke verbetering in de gebruiksvriendelijkheid gebracht, waardoor het configuratieproces gestroomlijnd en toegankelijker is geworden.

De tijdswinst in het configuratieproces vertaalt zich niet alleen naar operationele efficiëntie maar heeft ook bredere implicaties voor de productiviteit van het team en de algehele flexibiliteit van het bedrijf. Medewerkers kunnen nu sneller en intuïtiever Datapanel configuraties maken, wat resulteert in een aanzienlijke vermindering van de inspanning die nodig is voor deze taak. 

Daarnaast heeft de usability-test, die gericht was op het evalueren van de gebruikerservaring binnen de vernieuwde UI, substantiële inzichten geleverd. Deze test heeft niet alleen specifieke knelpunten blootgelegd, maar heeft ook geleid tot optimalisaties die voorheen niet aan bod kwamen. Door deze feedback direct te verwerken, kan ik vervolgstappen opstellen die deze UI verder zouden kunnen verbeteren, waardoor de bruikbaarheid en tevredenheid nog meer verbeterd zou kunnen worden.

### Aanbevelingen voor de Toekomst:
__Toevoegingen aan de configuratie UI:__  
Er zijn nog features die toegevoegd moeten worden om de ervaring met deze UI compleet te maken en features die boven water zijn gekomen nadat ik mijn demo had gegeven van mijn project, een aantal van deze features zijn:
#### Het json-editor component
Dit component moet nog worden toegevoegd aan de UI, dit heeft de hoogste prioriteit, maar is waarschijnlijk ook het makkelijkst toe te voegen, aangezien dit een bestaand component is binnen Datapanel. Dit heeft naar mijn mening de hoogste prioriteit, omdat dit ervoor zal zorgen dat table plus helemaal overbodig wordt. Op het moment kan het nog fijn zijn om table plus open te hebben staan, om de json te controleren, wanneer de json editor wordt geïmplementeerd is dit niet meer nodig en kun je daadwerkelijk alles op 1 plek configureren zonder andere hulpmiddelen.

#### Configuration initialization edit scherm
Op het moment maakt de configuration initialization service voor elke model een standaardconfiguratie, met een druk op een knop. Na de demo werd er bedacht om voor deze service een edit scherm te maken om de standaardconfiguratie snel aan te passen en ervoor te zorgen dat ongewilde models geen standaardconfiguratie krijgen. Het verschil met de huidige edit pagina’s zal zijn dat je voor een model een contenttype kunt selecteren en de pagina’s meteen op de juiste manier worden gegenereerd om bij dit contenttype te passen, op het moment zal de gebruiker deze pagina’s zelf aan moeten passen, nadat de standaardconfiguratie is gegenereerd.

#### Feedback en optimalisatie voor de configuration initialization service
In de huidige staat van deze service, kan het een paar seconden duren voordat de standaardconfiguratie zichtbaar wordt in de UI afhankelijk van hoeveel er gemaakt moeten worden. Dit komt omdat elk onderdeel van de configuratie afhankelijk is van elkaar, page is afhankelijk van modelview, subpage van page en sectie van subpage, page en modelview. Om deze reden kan het lijken dat wanneer je op de bijbehorende knop drukt er niets gebeurd. Een “toast” om te laten zien dat de service bezig is met het genereren van de configuraties zal dus al een grote verbetering zijn.

### Samenvatting van de Conclusie:
In essentie heeft het stageproject niet alleen bijgedragen aan de technische optimalisatie van Datapanel-configuraties maar heeft het ook tastbare voordelen opgeleverd voor de algehele bedrijfsvoering. De implementatie van verbeteringen heeft de gebruiksvriendelijkheid vergroot en de efficiëntie verbeterd. Deze conclusie weerspiegelt de positieve impact van het project en biedt een stevige basis voor verdere innovatie en groei.

## Persoonlijke Reflectie
### Leerdoelen
#### [Professional duties]  
You carry out the professional duties on a junior bachelor level resulting in professional products in line with the IT-area you are working in.

Mijn uitvoering van professionele taken op junior bachelorniveau tijdens deze stage wordt duidelijk weerspiegeld in mijn betrokkenheid bij diverse kernactiviteiten, zoals Analysis, Design, Realize, Advise, en Manage & Control. Mijn inzet binnen deze activiteiten volgt de richtlijnen van het HBO-I framework op competentieniveau 2.

Als bewijs van mijn betrokkenheid bij Analysis kan ik verwijzen naar mijn bijdrage aan het opstellen van requirements voor zowel de frontend als de backend. De bijbehorende documenten illustreren mijn vermogen om complexe analyses uit te voeren en vereisten helder te definiëren, waarmee ik voldoe aan het niveau dat van een junior bachelor wordt verwacht.

Binnen het domein van Realize heb ik concreet bijgedragen aan de ontwikkeling van de backend-service, waarbij ik gestandaardiseerde procedures heb gevolgd om efficiëntie en gebruiksvriendelijkheid te waarborgen. Het resultaat van deze inspanningen, gedocumenteerd in mijn implementatierapporten, weerspiegelt de professionele producten die ik heb voortgebracht.

Mijn rol in Advise komt tot uiting in het kopje aanbevelingen, waar ik advies geef over de volgende stappen die genomen kunnen worden binnen dit project, met de belangrijkste features, gesorteerd op relevantie.
Binnen Manage & Control heb ik actief deelgenomen aan projectmanagement activiteiten, zoals het gebruik van Gitflow en het bijhouden van voortgang in het ticketsysteem. Deze praktijken zijn getuigen van mijn vermogen om bij te dragen aan het beheer en de controle van het project op een niveau dat in lijn is met mijn junior bachelorniveau.

Als geheel tonen deze concrete voorbeelden van mijn betrokkenheid bij verschillende activiteiten aan dat mijn professionele taken tijdens deze stage voldoen aan het niveau van een junior bachelor, waarbij ik producten heb voortgebracht die passend zijn binnen het IT-gebied van het Datapanel-project.

#### [Situation-orientation]    
You apply your previously acquired knowledge and skills in an authentic context to deliver relevant results for the project and company.

Gedurende mijn stage heb ik succesvol mijn eerder opgedane kennis en vaardigheden toegepast in een realistische context, waarbij ik resultaten heb geleverd die relevant waren voor zowel het project als het bedrijf. De toepassing van mijn vaardigheden verliep methodologisch en gestructureerd, naadloos aansluitend bij de gevestigde processen en operationele werkwijzen van Stofloos.

Binnen het Datapanel-project, ingebed in een authentieke IT-omgeving, had ik een IT-probleem met meerdere belanghebbenden. Dit bood een werkelijke context voor de toepassing van mijn kennis. Het project vereiste een begrip van IT-processen, systemen en de interactie van verschillende onderdelen binnen de organisatie.

__Methodische en Gestructureerde Aanpak:__   
Tijdens mijn stage hanteerde ik een methodische aanpak door gebruik te maken van Scrum als projectmanagementmethode. Het scrum framework bood een gestructureerd kader waarmee ik mijn werk kon organiseren in sprints, regelmatige opleveringen kon houden voor planning en evaluatie, en flexibel kon inspelen op veranderende eisen van het project.

Daarnaast integreerde ik mijn werkzaamheden naadloos in het ticketsysteem van het bedrijf. Elk aspect van het project werd verwerkt naar kleine taken, die vervolgens werden gevolgd en bijgewerkt via het ticketsysteem. Deze benadering zorgde niet alleen voor een gestructureerde uitvoering van het project, maar bood ook transparantie over de voortgang.

Deze combinatie van Scrum en het ticketsysteem diende als concreet bewijs van mijn methodische aanpak, waardoor ik kon aantonen hoe ik mijn werk gestructureerd plande, uitvoerde en integreerde in de bredere bedrijfsprocessen. Dit resulteerde in een efficiënte en georganiseerde workflow, waardoor het project soepel kon verlopen.

__Relevantie voor Belanghebbenden:__  
De resultaten van mijn werk waren ontegenzeggelijk relevant voor verschillende belanghebbenden. Mijn inspanningen waren gericht op het adresseren van de behoeften van interne stakeholders, waardoor mijn werk bijdroeg aan zinvolle oplossingen en waarde toevoegde aan het bedrijfskader, zoals te zien in mijn [requirements document](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/1.%20Opzet%20van%20het%20Project/RequirementsDocument.md#project-overview), waarin ik kort mijn stakeholders beschrijf.

#### [Onderzoekend Probleemoplossend Vermogen] 
You take a critical look at your project from different perspectives, identify problems, find an effective approach and arrive at appropriate solutions.

Mijn vaardigheden op het gebied van onderzoekend probleemoplossen tijdens mijn stage blijkt uit mijn systematische aanpak bij het identificeren en aanpakken van problemen en implementeren van features. In de eerste fase van het project heb ik een projectplan opgesteld, waarin de scope, kansen en problemen duidelijk waren vastgelegd. Deze informatie heb ik verkregen door dit te bespreken met stakeholders, het opstellen van een survey en het ontwikkelen van wireframes en prototypes om tot een oplossing te komen.

Gedurende het project hield ik voortdurend rekening met verschillende perspectieven, aangezien het doel was om deze configuraties ook toegankelijker te maken voor minder technische mensen en hanteerde ik een effectieve aanpak bij het benaderen van problemen. Hierbij maakte ik gebruik van diverse methoden van het DOT framework, zoals eerder beschreven in dit document. Deze verschillende onderzoeksmethoden stelde me in staat om diepgaande analyses uit te voeren en antwoorden te vinden op gestelde onderzoeksvragen.

Mijn vaardigheid om geschikte oplossingen te formuleren werd verder versterkt door het valideren van deze oplossingen gedurende de sprints en sprint opleveringen. Ik voerde ook usability tests uit en schreef unit tests voor de backend. Deze constante validatie zorgde ervoor dat de voorgestelde oplossingen niet alleen effectief waren, maar ook voldeden aan de behoeften van de stakeholders en de geïdentificeerde problemen oplossen.

Kortom, mijn benadering van onderzoekend probleemoplossen omvatte een grondige analyse van problemen, het gebruik van diverse onderzoeksmethoden en het ontwikkelen van passende oplossingen die vervolgens werden gevalideerd door stakeholders gedurende het hele project. 

#### [Personal Leadership] 
You are entrepreneurial around your projects and personal development, you pay attention to your own learning ability and keep in mind what kind of IT professional and/or what type of positions you aspire to.

Mijn ondernemerschap en persoonlijke ontwikkeling tijdens deze stage, komt tot uiting in mijn aanpak. Ik neem zowel op het gebied van planning als inhoud de leiding in mijn project, waarbij ik initiatief toon en verantwoordelijkheid neem voor het succesvol verloop ervan.

Het aandacht besteden aan mijn eigen leervermogen is een cruciaal onderdeel van mijn persoonlijk leiderschap. Door regelmatig te reflecteren op mijn eigen handelingen, door middel van retrospectives en het wekelijks invullen van feedpulse en actief feedback te vragen en ontvangen, ben ik in staat mijn ontwikkeling als IT-professional nauwkeurig te volgen. Deze reflecties stellen me in staat om verdere verbeterpunten en mogelijkheden te identificeren die blijken uit de ontvangen feedback. Hierdoor ben ik me voortdurend bewust van mijn groei als IT-professional.

### Personal & Professional Goals
Aan het begin van mijn stage moest ik een proposal inleveren, hierin moest ik personal en professioal goals meenemen. De volgende kopjes zijn de goals die ik voor mezelf had bedacht en een reflectie op hoe ik denk dat ik dit heb meegenomen in mijn stage.

__Verbeteren van presentatie skills (voor een publiek van professionals):__   
Mijn ervaring tijdens de sprint opleveringen heeft me doen inzien dat ik comfortabel ben bij het presenteren van mijn vooruitgang en nieuwe features voor het Stofloos team. Aangezien ik me tijdens deze momenten niet nerveus voelde suggereert dit dat mijn vaardigheden aanwezig zijn of in ieder geval zijn verbeterd. Ik heb zelf gemerkt dat ik wordt beïnvloed door de specifieke setting, zoals bij formele presentaties voor bijvoorbeeld docenten. 

__Betere onderzoeksvragen opstellen (de juiste vraag bij een onderzoek gebruiken):__  
Tijdens mijn stage heb ik 2 onderzoeksvragen opgesteld, deze vragen zijn eerder voorbij gekomen in dit document. Om deze vragen op te stellen heb ik meerdere keren feedback ontvangen over hoe ik de vraag kan verbeteren en welke bijvragen missen of aangepast moeten worden. Daarnaast ben ik ook actief doorgegaan met het schrijven van devlogs, hierbij formuleer ik constant kleine onderzoeksvragen, op deze manier kan ik blijven oefenen. Door hier wederom feedback over te vragen, kon ik mijn vaardigheden in het stellen van de juiste vragen ook verbeteren. Het betrekken van deze feedback in mijn leerproces heeft geholpen bij het verbeteren van mijn formuleringen.
Kortom, het voortzetten van het schrijven van devlogs en het vragen van feedback tijdens mijn stage heeft bijgedragen aan mijn vermogen om onderzoeksvragen effectiever te formuleren.

__Verbeter vaardigheden op het gebied van timemanagement:__  
Tijdens deze stage heb ik waardevolle inzichten gekregen op het gebied van mijn timemanagement vaardigheden. Het feit dat mijn inschattingen van de tijd die nodig was voor het toevoegen van bepaalde features over het algemeen correct waren, is een positief aspect. Het herkennen van de noodzaak om ook tijd in te plannen voor portfolio-overwegingen is een belangrijk leermoment geweest. Ik heb meerdere malen meegemaakt dat ik mijn portfolio achterwege liet en dit niet goed in mijn planning betrok. Ik kan deze ervaring gebruiken om mijn timemanagement verder te verfijnen, waarbij ik niet alleen rekening houd met projecttaken maar ook met bredere aspecten zoals portfolio-onderhoud.





