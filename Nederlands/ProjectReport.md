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
- [Hoe is Stofloos situatie verbeterd sinds Datapanel is opgezet?](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/StofloosVerbeteringSindsDatapanel.md)
- [Hoe kan een gebruiksvriendelijke UI die het proces voor het creëren van Datapanel configuraties optimaliseert worden gemaakt?](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/UIVoorOptimalisatieDatapanelConfiguraties.md)

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

### Leerdoelen
__[Professional duties]__  
You carry out the professional duties on a junior bachelor level resulting in professional products in line with the IT-area you are working in.

Mijn inzet voor professionele taken op junior bachelorniveau wordt duidelijk weerspiegeld in mijn activiteiten, in lijn met het HBO-I framework. Ik heb methodisch bijgedragen aan Analysis, Design, Realization, Advisory, en Manage & Control. Bijvoorbeeld, de ontwikkeling van de backend-service illustreert mijn systematische aanpak, waarbij ik gestandaardiseerde procedures volgde om efficiëntie en gebruiksvriendelijkheid te waarborgen. Het opstellen van functionele requirements voor de backend en het implementeren van de service voor het automatisch aanmaken van pagina's zijn concrete voorbeelden van mijn bijdragen aan Analysis en Realization.

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

## Conslusie

## Aanbevelingen

## Persoonlijke Reflectie



