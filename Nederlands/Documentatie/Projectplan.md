# Projectplan

## Gebruikersinterface voor Datapanel configuraties
![alt text]([https://www.google.com/url?sa=i&url=https%3A%2F%2Fstofloos.nl%2F&psig=AOvVaw2neV89hRUO79PJy_ahPIpc&ust=1696411963360000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCMiAu5XJ2YEDFQAAAAAdAAAAABAJ])

Stofloos
Eindhoven







Datum			:	28/09/2023
Versie			:	0.4
Status			:	Finished
Auteur			:	Tim Meijvogel




Versie

Versie
Datum
Auteur(s)
Wijzigingen
Status
0.1
07/09/2023
Tim Meijvogel


in progress
0.2
19/09/2023
Tim Meijvogel
Alles is aangevuld, het grootste deel is af, op 1.3, 1.4, 1.6 en 2.3 na.
in progress
0.3
25/09/2023
Tim Meijvogel
Feedback toegepast op 1.1 t/m 1.7, 2.1 t/m 2.3 en 2.5, 3.2, 3.3 en 3.4
Finished (if no feedback is received)
0.4
28/09/2023
Tim Meijvogel
Backend eisen toegevoegd en feedback toegepast: 1.3, 1.4, 1.6, 1.7, 2.1.1,  2.3
Finished (if no feedback is received)


Verspreiding
Versie
Datum
Aan
0.1
07/09/2023
Frank Coenen
0.2
19/09/2023
Frank Coenen
0.3
25/09/2023
Frank Coenen
0.4
28/09/2023
Frank Coenen




Inhoudsopgave

1. Projectopdracht	4
1.1 Context	4
1.2 Doel van het project	4
1.3 De opdracht	5
1.4 Scope	5
1.5 Randvoorwaarden	5
1.6 Onderzoeksvragen	6
1.7 Eindproducten	7
2. Aanpak en Planning	8
2.1 Aanpak	8
2.2 Onderzoeksmethoden	9
2.3 Leeruitkomsten	10
2.4 Opdeling van het project	12
2.5 Tijdplan	12
3. Projectorganisatie	13
3.1 Teamleden	13
3.2 Communicatie	13
3.3 Testomgeving en benodigdheden	13
3.4 Configuratiemanagement	14
4. Financiën en Risico’s	15
4.1 Risico’s en uitwijkactiviteiten	15
Projectopdracht
Context
Stofloos brengt data tot leven door middel van het maken van dashboards, dataplatforms, datawarehouses en rapportages. Met deze oplossingen versterken ze bedrijven door het integreren van data, waardoor het onbenut potentieel benut wordt en organisaties data-gedreven kunnen werken.
Het proces dat Stofloos doorloopt bestaat uit 3 pijlers: strategie, infrastructuur, impact. Zo hebben ze binnen ‘strategie’ hun ervaring gebruikt voor het ontwikkelen van een simpel data framework, Extraction, Transformation and Load (ETL) proces en data governance documenten. Voor ‘infrastructuur’ en ‘impact’ geldt dat de meeste gevallen dezelfde componenten nodig hebben om de basis te leggen voor een data-oplossing. Door deze gemeenschappelijke componenten te gebruiken, kunnen ze zich concentreren op het ontwikkelen van maatwerk onderdelen met specifieke behoeften van bedrijven in gedachten.
Alle applicaties en bouwstenen die ze hebben ontwikkeld en inzetten noemen ze ‘Stofware’. De Stofware software is een verzameling van ETL en data-applicaties die worden gebruikt voor het beheren en analyseren van de gegevens die gebruikt worden binnen een organisatie. Stofware is ontwikkeld met behulp van de belangrijkste open source bibliotheken van de industrie, hieromheen hebben ze hun eigen schil gecreëerd. De Stofware componenten die voor mij van belang zijn zijn de nocode api, Stofloos gateway en Datapanel.
Bij Stofloos is er de mogelijkheid om te werken aan een ontwerp en implementatie van een gebruikersinterface voor Datapanel configuraties. 
Datapanel is een platform dat data overzichtelijk weergeeft en bestaat uit pages, subpages en secties. Datapanel is onderdeel van Stofware. De subpages en secties moeten worden geconfigureerd met json, op deze manier wordt de layout van een subpage en sectie bepaald.
Dit is voor Stofloos zelf, specifiek voor de software developers die moeten werken met Datapanel. Deze opdracht is ontstaan door de realisatie dat bij het proces van het maken van Datapanel configuraties veel tijd onnodig verloren gaat en dit dus geoptimaliseerd kan worden. Deze opdracht richt zich op het maken van een frontend voor deze specifieke taak binnen Datapanel en valt onder de software richting. 

Doel van het project
Het huidige probleem is: Op dit moment worden Datapanel configuraties handmatig in JSON geschreven, wat tijdrovend en vatbaar voor fouten is.
De gewenste situatie is een gebruiksvriendelijke user interface voor het configureren van Datapanel. Dit zal het proces minder foutgevoelig maken en de benodigde tijd verminderen. Ook moet het ervoor zorgen dat het configureren van Datapanel toegankelijk is voor gebruikers met een mindere technische kennis.
Wanneer deze processen gestroomlijnd zijn is er meer tijd om te werken aan de andere projecten, wanneer hier meer tijd voor is zal de kwaliteit die Stofloos biedt nog hoger worden.

Dit project is een succes wanneer de snelheid en de gebruiksvriendelijkheid van het maken van Datapanel configuraties is verbeterd. Dit is bereikt wanneer het software team van Stofloos Datapanel configuraties kunnen maken en aanpassen op 1 plek en deze meteen te zien zijn zonder de pagina te hoeven herladen. Op het moment wordt hiervoor table plus en data panel gebruikt en moet de pagina herladen worden voordat er veranderingen te zien zijn.
Wanneer dit wordt gecombineerd met een duidelijke UI dan zal het bedrijf tevreden zijn. Zelf ben ik tevreden als iemand die nog nooit een configuratie in Datapanel heeft gemaakt dit zou kunnen doen, nadat er één 
keer is laten zien hoe het werkt (op het moment is het hier te onduidelijk voor).








De opdracht
Op dit moment worden deze configuraties handmatig in JSON geschreven, wat tijdrovend en vatbaar voor fouten is. De opdracht is om binnen Datapanel een gebruikersinterface (UI) te ontwikkelen voor het maken van Datapanel configuraties. Het doel is om dit proces te stroomlijnen met een UI die de juiste JSON genereert. Deze interface moet ontwikkeld worden met behulp van Lit Components.
Eisen en wensen zijn:
Omdat er steeds doorontwikkeld wordt (nieuwe soorten secties e.d.) moet de interface makkelijk uitbreidbaar zijn, of generiek opgezet zijn.
De interface moet in eerste instantie voor de ontwikkelaars gemaakt worden (stakeholder). Maar moet ook toegankelijk zijn voor de eindklant.
"Op locatie" pagina's en secties kunnen editen
Inputs die de json genereren voor het maken van pages, subpages en sections.
Als de interface klaar is zou een extra wens zijn om een standaard configuratie met 1 druk op de knop te kunnen genereren a.d.h.v. nocode modellen / modelviews.
Backend service voor het automatisch aanmaken van pages en subpages.

Scope

Tot het project behoort:
Tot het project behoort niet:
Werkende UI in Datapanel dat gebruikt kan worden in een van de projecten
Volledig uitwerken van low priority features
Service om json files te genereren in Datapanel
Opzetten van CI/CD
User testing (valideren van prototypes en producten met behulp van end users)


Prototypes en wireframes van de UI


Research documenten (onderzoeken die zijn verricht, voorbeelden staan bij 1.6 in dit document)


Backend service voor het aanmaken van pages en subpages





Randvoorwaarden

Bij stofloos wordt er aan de frontend gewerkt met typescript en Lit. Deze technologieën dienen in dit project gebruikt te worden. 
Voor wireframes en prototypes wordt gebruikgemaakt van Figma. Dit zal dus ook voor dit project gebruikt worden.
Voor versiebeheer wordt Bitbucket gebruikt, met gitflow als branching model.
De UI moet ingebakken zijn in Datapanel, dus er is geen configuratie buiten Datapanel nodig om het werkend te krijgen.
De backend wordt geschreven in typescript.

Onderzoeksvragen
Tijdens deze stage zullen er onderzoeken verricht moeten worden. Dit is om erachter te komen hoe het huidige project werkt, wat het probleem is, hoe hier al aan is gewerkt en wat er nog verwacht wordt. Verder moeten er misschien ook nog technische onderzoeken worden verricht. De belangrijkste onderzoeken voor dit project zijn op dit moment: 

Hoe is Stofloos situatie verbeterd sinds Datapanel is opgezet?
Welke uitdagingen waren er voordat Datapanel was opgezet? 
Wat waren de voorafgaande verbeteringen aan Datapanel en waarom waren deze nodig? 
Hoe ziet de huidige situatie eruit? 
Is de huidige situatie de ideale situatie? 

Aangezien dit een lopend project is, is het belangrijk om er achter te komen hoe de situatie is veranderd. Dit moet vergeleken kunnen worden met eerdere situaties, want dit laat de verbeteringen zien en kan laten zien waar Stofloos naartoe wil werken. De huidige situatie is nodig om te zien hoe ver het project op het moment is, op deze manier kan er gezien worden hoeveel de situatie is verbeterd en wat er nog aan gedaan moet worden.

Hoe kan een gebruiksvriendelijke UI die het proces voor het creëren van Datapanel configuraties optimaliseert worden gemaakt?
Wat zijn de huidige uitdagingen en beperkingen bij het creëren van Datapanel configuraties?
Wat zijn de belangrijkste functionaliteiten en interacties die vereist zijn in de UI voor het maken van Datapanel configuraties?
Hoe worden de in de ui gemaakte configuraties geëxporteerd naar json?
Hoe worden de opgeslagen configuraties geïmporteerd naar de ui?
Hoe wordt ervoor gezorgd dat de UI gebruiksvriendelijk blijft?


Met dit onderzoek wil ik er achter komen wat de huidige uitdagingen en beperkingen zijn bij het creëren van Datapanel configuraties en hoe ik dit kan oplossen op een manier dat alle end users hier profijt van hebben.

De manier waarop de (deel)vragen worden aangepakt m.b.t. de DOT framework is te zien bij kop 2.2 in dit document.


Eindproducten
Het eindproduct van dit project zal bestaan uit verschillende onderdelen, deze onderdelen zijn hieronder ingedeeld in 2 categorieën en hebben een korte uitleg wat hierbij verwacht wordt. Verder is er een overzicht waarin alle producten te zien zijn.
Software
De software zal bestaan uit technische producten. Denk hierbij aan de front- en backend van het project. (Mogelijk kan de bestaande backend gebruikt worden en hoeft hier geen aanpassingen aan gemaakt te worden. In dit geval wordt er geen backend opgeleverd)
Documentatie: De documentatie zal bestaan uit alles dat geen code bevat. Elk document is te koppelen aan een leerdoel, deze connectie is te zien in kop 2.3 van dit document. 
Portfolio: Een verzameling van alle professionele producten en het projectrapport.
projectrapport: Beschrijving van de opdracht, beschrijving van het proces, conclusie en persoonlijke reflectie.
Prototypes: Wireframes en prototypes die zijn gemaakt met Figma.
Projectplan: Dit document.
Research documenten: Alle onderzoeken die zijn uitgevoerd binnen dit project.
Design documenten: Geeft de architectuur van het project weer.
Scrumboard: Dit geeft mijn manier van werken weer.
Requirements document: Beschrijft de verwachtingen en behoeften van de gebruiker, het doel achter die oplossing en eventuele hoog-niveau beperkingen.

Aanpak en Planning
Aanpak

Er zal tijdens deze stage gewerkt worden met scrum. Met behulp van een planning board wordt er bijgehouden wat er welke sprint gedaan moet worden. Hiervoor wordt er gebruik gemaakt van Stofloos eigen ticketsysteem op team.stofloos.nl. De lengte van de sprints zal 2 weken zijn, dit zorgt ervoor dat er genoeg tijd is om meerdere taken af te ronden en research te doen wanneer nodig. Stand ups zullen dagelijks plaatsvinden. Aan het einde van een sprint zal een demo met sprint review en retrospective plaatsvinden. Verder wordt wekelijks progressie bijgehouden, hiermee kunnen ik, mijn stagebegeleider en ass1 zien hoe het project ervoor staat die sprint en of de geplande taken af komen. 


Testaanpak
Om de kans op fouten te minimaliseren, moet de geschreven code getest worden. Dit kan op verschillende manieren gebeuren. 
code/peer reviews:
Door collega’s naar geschreven code te laten kijken kunnen fouten die eerder misschien gemist waren worden opgelost en er kunnen ook nieuwe ideeën ontstaan. 

Handmatig testen:
Als er snel iets gecheckt moet worden, kan er bijvoorbeeld gebruikgemaakt worden van een "console.log". Op deze manier kan er snel gezien worden of de nieuwe code die geschreven is werkt zoals verwacht.

Unit tests:
Wanneer de nocode backend aangepast moet worden, kunnen deze aanpassingen getest worden met unit test. Wanneer een bestaand stuk code wordt aangepast kan er snel gezien worden of dit effect zal hebben op de rest van het project.

Automatische testen:
Dit zijn testen die in de CI pipeline worden uitgevoerd wanneer nieuwe code wordt gepusht. De testen die ik uit wil laten voeren in de pipeline zijn de unit tests die hierboven beschreven staan.

Usability test:
Dit is een goede manier om de UX te testen en te zien of mijn ontwerp duidelijk is.
Identificeer mogelijke bruikbaarheidsproblemen, begrijp het gebruikersgedrag en verzamel feedback die ontwerp aanpassingen kan informeren.
Laat gebruikers taken uitvoeren met behulp van het product en verzamel op deze manier feedback en ontdek eventuele fouten in het product.
Onderzoeksmethoden


Methode
Uitvoering
Onderzoeksvraag (kop 1.6)
Library




Literature study
Deze methode gaat gebruikt worden om meer te leren over de functionaliteiten van Lit en problemen met typescript en of Lit op te lossen.
2.2, 2.3
Design pattern research
Er wordt gekeken naar de manier waarop Stofloos code schrijft en opbouwd. Dezelfde principes worden gehanteerd tijdens het coderen.
n.v.t. voor onderzoeksvraag bij 1.6, maar wel voor wanneer er gecodeerd gaat worden.
Available product analysis
Deze methode gaat gebruikt worden om te onderzoeken of dit of een soortgelijk probleem al eerder is opgelost en of dit op eenzelfde of andere manier opgelost kan worden.
2.2, 2.3
Expert interview
Stel vragen aan de experts bij Stofloos om problemen op te lossen of nieuwe informatie te krijgen over de opdracht.
1, 2
Field




Problem analysis
Stel vragen aan de experts van Stofloos over hun huidige probleem en krijg zo een beter begrip van het probleem.
1.3, 2.1
Survey
Er wordt gebruik gemaakt van een survey om achter de specifieke (kwaliteits-)eisen te komen.
1.3, 1.4, 2.1, 2.2
Explore user requirements
Door gebruik te maken van een survey en vragen te stellen worden de requirements die de gebruikers verwachten van een UI duidelijk.
2
Workshop




Brainstorm 
Door onderzoek te doen en vragen te stellen ontstaan er misschien ideeën waar de experts van Stofloos nog niet aan hadden gedacht.
2.2
Prototyping
Wireframes en werkende prototypes moeten maken als onderdeel van mijn opdracht. Ze worden gebruikt om UI (features) te testen.
2.2, 2.4
Lab




Usability testing
Wanneer een feature af is wordt er een nieuwe branch en een pull request gecreëerd. Hierna kan deze op een live testomgeving worden gezet. Wanneer deze op de testomgeving staat hebben alle developers de kans om de feature te testen.
2.4
A/B Testing
Er worden verschillende prototypes gemaakt, om te testen welke layouts/features het beste werken voor de target audience.
2.4


Leeruitkomsten

Professional duties] You carry out the professional duties on a junior bachelor level resulting in professional products in line with the IT-area you are working in.

Producten die bijdragen: research documenten, wireframes en prototypes en source code

“All or a subset of the activities Analysis, Design, Realize, Advise, Manage & Control”. Analyseren zal worden gedaan door middel van de onderzoeken die worden verricht. “Design” wordt aangetoond door de wireframes en prototypes die worden gemaakt. De realisatie van het werk wordt laten zien in het eindproduct, door middel van sourcecode. Advies wordt in notion gezet, dit advies zal bevatten hoe er gebruikgemaakt moet worden van mijn product en of er bepaalde libraries zijn die nodig zijn om aanpassingen te maken.
[Situation-orientation] You apply your previously acquired knowledge and skills in an authentic context to deliver relevant results for the project and company.
	Producten die bijdragen: Scrumboard, stakeholder analyse 
Om te laten zien dat er gestructureerd gewerkt wordt, wordt er gebruikgemaakt van een scrumboard. Dit laat de planning, progress en  werkwijze zien. Om de relevantie van dit project weer te geven kan er gebruikgemaakt worden van een stakeholderanalyse, dit laat zien dat er meerdere belanghebbende zijn voor het project.
[Future-Oriented Organisation] You explore the organizational context of your project, make business, sustainable and ethical considerations and manage all aspects of the execution of the project.
Producten die bijdragen: projectplan, research, stakeholderanalyse, scrumboard
Om aan dit leerdoel te voldoen zal ik naar het hele plaatje moeten kijken, wat wil de klant? Is de oplossing die ik heb bedacht de juiste (op gebied van business, ethiek en onderhoudbaarheid)? En hoe beheer ik dit allemaal. Met de hierboven genoemde producten kan ik dit allemaal aantonen.

[Investigative Problem Solving] You take a critical look at your project from different perspectives, identify problems, find an effective approach and arrive at appropriate solutions.
Producten die bijdragen: projectplan, research documenten, ontvangen feedback
In mijn projectplan worden problemen en wensen van de klant vastgesteld, daarnaast staan hier ook onderzoeksvragen die zijn vastgesteld. Problemen waar ik in de loop van het project tegenaan loop, zullen worden opgelost door middel van onderzoeken. De DOT methoden die zijn toegepast voor deze onderzoeken staan benoemd in de research documenten. Om mijn onderzoeken te valideren wordt er feedback gevraagd aan de belanghebbende.                  
[Personal Leadership] You are entrepreneurial around your projects and personal development, you pay attention to your own learning ability and keep in mind what kind of IT professional and/or what type of positions you aspire to.
Producten die bijdragen: scrumboard, logboek, weekly updates (feedpulse), retrospective, presentaties
Ik kan gebruik maken van mijn scrumboard om aan te tonen hoe ik mijn tijd voor een bepaalde sprint wil besteden. Om mijn learning ability bij te houden, houd ik dagelijks bij wat ik heb gedaan en vul ik wekelijks een samenvatting in van de afgelopen week in feedpulse. Ik heb zelf professionele doelen waar ik naartoe wil werken (presenteren en gesprekken (meer) leiden), hier wordt aan gewerkt tijdens de sprint reviews. Ook wordt er na elke sprint een retrospective bijgehouden, die ik kan gebruiken om dit leerdoel aan te tonen. 
[Targeted Interaction] You determine which partners play a role in your project, collaborate constructively with them and communicate appropriately to achieve the desired impact.
	Producten die bijdragen: stakeholderanalyse, feedpulse
Door middel van een stakeholderanalyse laat ik zien aan welke partners ik aandacht besteed en hoeveel. Door regelmatig met deze partners te communiceren bereiken we de gewenste uitkomst.

Opdeling van het project

Sprint 0: Gedurende sprint 0 zullen de nodige documentatie en programma’s worden opgezet/gedownload. Daarnaast wordt er geoefend met de Datapanel van Stofloos,  

Sprint 1: Tijdens sprint 1 zullen de puntjes op de ‘i’ worden gezet voor het projectplan (als deze nog niet af is) en wordt er gewerkt aan de onderzoeken en prototypes.

Sprint 1-7: Er wordt gezorgd dat alle requirements met een hoge prioriteit in het product verwerkt zitten.

Sprint 1-8: Het portfolio zal regelmatig worden bijgewerkt. Op deze manier wordt er niet vergeten wat er is gebeurd de afgelopen dagen/weken en welke stappen er zijn doorlopen om tot een oplossing te komen.

Sprint 8: Afronding van het project en portfolio.

Deze indeling houdt geen rekening met vakanties en kan dus één sprint minder bevatten dan ik daadwerkelijk ga gebruiken

Tijdplan


Fasering
Doelstellingen
Effort 
Start
Gereed
sprint 0
Projectplan: (zo goed als) af
Bekend worden met Datapanel
15 dagen
week 1
week 3
sprint 1
Wireframes af en bijna prototypes
af
10 dagen
week 4
week 5
sprint 2
begin aan de UI, zonder styling
prototypes af
10 dagen
week 6
week 7
sprint 3
UI zonder styling, minimale
functionaliteit
10 dagen
week 8
week 9
sprint 4
Werkende UI die json configuraties
kan maken
10 dagen
week 10
week 11
sprint 5
begin aan de backend
10 dagen
week 12
week 13
sprint 6
functionele backend
10 dagen
week 14
week 15
sprint 7
Styling voor de UI
10 dagen
week 16
week 17
sprint 8
Alle (kwaliteis-)eisen zijn verwerkt  
in het project en bijbehorende
documentatie is af
10 dagen
week 18
week 19


Projectorganisatie
Teamleden


Naam + tel + e-mail
Afk.
Rol/taken
Beschikbaarheid
Tim Meijvogel
+31 6 57953609
Stofloos: tim@stofloos.nl
fontys: 462739@student.fontys.nl


Developer
5 dagen per week
Jim Spijker
+31 6 31993946
jim@stofloos.nl


stage begeleider
5 dagen per week
Michael Rademaker
+31 6 27073729
michael@stofloos.nl
PO
Product owner 
Internship mentor
4 dagen per week (kantoor)
1 dag per week (online)
Frank Coenen
+31 6 53804451
f.coenen@fontys.nl
ass1
1e assesor


Mark Mestrom
+31 6 51261585
m.mestrom@fontys.nl
sc
stagecoördinator





Communicatie

Binnen Stofloos zal tijdens de stage voornamelijk gecommuniceerd worden via Slack. Meetings zoals stand-ups zullen op kantoor plaatsvinden of via Slack wanneer mensen vanuit huis werken. Verder vindt communicatie op kantoor mondeling plaats. Contact richting Fontys zal via Microsoft Teams, mail of mondeling gaan. Als er meetings moeten worden georganiseerd tussen Fontys en Stofloos is de stagiair degene die deze meeting afstemt. Ook zijn er wekelijkse updates via feedpulse (canvas), hierin staat beschreven wat er de afgelopen week is gebeurd. Verder wordt er dagelijks een logboek bijgehouden dat gebruikt kan worden voor mijn wekelijkse updates.  



Testomgeving en benodigdheden

Bij Stofloos wordt er lokaal gewerkt aan features, wanneer een feature af is wordt er een nieuwe branch en een pull request gecreëerd. Hierna kan deze op een live testomgeving worden gezet. Wanneer deze op de testomgeving komt te staan, wordt het gechecked door een senior developer.
Verder kunnen in de pipeline automatisch unit tests worden uitgevoerd wanneer iets wordt gepusht.




Configuratiemanagement


Voor versiebeheer wordt bitbucket gebruikt met gitflow. Wanneer er aan een nieuwe feature wordt gewerkt, wordt hiervoor een branch gemaakt die is afgeleid van de “develop” branch. Wanneer mijn feature af is zal er een pull request worden gemaakt, zodat deze nieuwe feature op de “develop” branch komt.
Een voorbeeld is:
Master branch (Productieserver)
Development branch (Staging server)
Feature branch (Ontwikkelomgeving lokaal)
Hotfix branch (Ontwikkelomgeving lokaal)

Voor het bijhouden van documentatie voor het portfolio, research, etc. wordt google docs gebruikt. Op deze manier kan de stagebegeleider makkelijk comments plaatsen, kan het makkelijk worden geëxporteerd (naar bv. Fontys portfolio tool en notion) en kan het vanaf meerdere machines worden geopend en bewerkt.
Financiën en Risico’s

Risico’s en uitwijkactiviteiten

Risico
Activiteiten ter voorkoming opgenomen in plan
Uitwijkactiviteiten
Ass1 niet beschikbaar.
communiceer bij het einde van een gesprek/sprint oplevering wanneer de volgende meeting zal zijn.
Is het dringend of is ass1 voor een lange tijd niet beschikbaar, neem contact op met de sc.
PO/internship mentor niet beschikbaar.
Bespreek wie zijn rol over kan nemen binnen Stofloos.
Zoek contact met de persoon die de rol tijdelijk over kan nemen.
Stage begeleider is voor een lange periode niet beschikbaar.
Bespreek wie zijn rol over kan nemen binnen Stofloos.
Zoek contact met de persoon die de rol tijdelijk over kan nemen.
Te weinig tijd om het project af te ronden.
overleg met PO en stagebegeleider om juiste begrenzingen af te spreken.
Werk verder aan de taken met de hoogste prioriteit die ik nog denk af te kunnen krijgen.



