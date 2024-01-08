# Hoe kan een gebruiksvriendelijke UI die het proces voor het creëren van Datapanel configuraties optimaliseert worden gemaakt?
Binnen dit project zijn er 2 non-functional requirements waar voornamelijk op gelet moet worden. Deze requirements zijn gebruiksvriendelijkheid en efficiëntie. Om ervoor te zorgen dat deze requirements zo goed mogelijk worden toegepast, zal er onderzoek gedaan moeten worden naar de manier waarop dit het best gedaan kan worden. 

## Wat zijn de huidige uitdagingen en beperkingen bij het creëren van Datapanel configuraties?
Op dit moment zijn er meerdere uitdagingen bij het maken van Datapanel configuraties. Deze configuraties worden op het moment handmatig in JSON geschreven. Dit brengt 2 problemen met zich mee, de eerste is dat dit vatbaar is voor fouten, de tweede is dat dit tijdrovend is. Deze problemen gaan hand in hand. Als er een fout wordt gemaakt in de handmatig geschreven json bestanden, kost het extra tijd om 
dit op te lossen.  
Naast het schrijven van json voor deze configuratie is het belangrijk dat de user begrijpt hoe alles met elkaar in verbinding staat (modelview, page, subpage, sectie). Dit is op het moment niet duidelijk en kan voor problemen zorgen, zeker wanneer de user geen technische ervaring heeft.

## Wat zijn de belangrijkste functionaliteiten en interacties die vereist zijn in de UI voor het maken van Datapanel configuraties?
Voor het maken van configuraties is het belangrijk dat er wordt gekeken naar de huidige problemen en de wensen van de end users. Uit  de huidige problemen is te halen dat de configuratie geautomatiseerd moet worden op basis van de input van een user en dat de flow van dit proces logisch moet zijn zodat het voor de user duidelijk is welke onderdelen (modelview, page, subpage, sectie) met elkaar zijn verbonden. Om achter de wensen van de end user te komen is er gebruikgemaakt van een survey. De antwoorden op deze survey is [hier](https://docs.google.com/spreadsheets/d/11wupAy5dy6jKsM4jbiJb1dX1Lb-ta0AkrlacHzkITfs/edit?usp=sharing) te vinden.  
De belangrijkste functionaliteiten zijn dus:
- Inputs die de json genereren voor het maken van pages, subpages en sections.
- "Op locatie" pagina's en secties kunnen editen
- Automatisch verbinden van de onderdelen wanneer deze in de flow worden aangemaakt.
- Intuïtieve navigatie

Meer informatie en onderbouwing is [hier](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/1.%20Opzet%20van%20het%20Project/Kwaliteitseisen.md) te vinden.

## Hoe worden de in de ui gemaakte configuraties geëxporteerd naar json?
Om inzicht te verkrijgen in hoe Datapanel configuraties vanuit de gebruikersinterface naar JSON exporteert, heb ik mijn vragen gericht aan mijn semester coach. Met zijn diepgaande kennis en expertise op dit gebied, wordt verwacht dat de processen die betrokken zijn bij het omzetten van UI-configuraties naar JSON-formaat duidelijk worden toegelicht.

Om configuraties vanuit de UI naar JSON te exporteren, volgt Datapanel een gestructureerd proces:

__Dataformaat Conversie:__
- De configuraties die in de UI zijn gemaakt, worden eerst omgezet van de interne representatie in de gebruikersinterface (als JavaScript-objecten) naar JSON-formaat. Dit omvat het vastleggen van alle relevante configuratiegegevens.

__Dataoverdracht naar NoCode:__
- De geconverteerde JSON-gegevens worden vervolgens verstuurd naar een NoCode-platform, dat mogelijkheden biedt voor verder beheer en analyse. Dit kan worden bereikt door de JSON-gegevens over te dragen via API-aanroepen of een vergelijkbaar mechanisme.

__Opslag in de Database:__
- Het NoCode-platform analyseert en verwerkt de ontvangen JSON-gegevens en slaat deze uiteindelijk op in de database van Datapanel. Hierdoor worden de configuraties veilig en duurzaam bewaard.

## Hoe worden de opgeslagen configuraties geïmporteerd naar de UI?
In mijn streven om het importproces van opgeslagen configuraties naar de gebruikersinterface van Datapanel te begrijpen, heb ik wederom gerichte vragen gesteld aan mijn semester coach, een expert op dit gebied. Door zijn ervaring en kennis te benutten, verwacht ik inzicht te krijgen in de specifieke stappen die worden genomen om opgeslagen JSON-configuraties uit de database op te halen, te parseren en naadloos weer te geven in de UI.

Voor het importeren van opgeslagen configuraties naar de UI, worden de volgende stappen gevolgd:

__Uitvragen van de Database:__  
- Bij het ophalen van configuraties uit de database, worden de opgeslagen JSON-gegevens geïdentificeerd en opgevraagd via relevante database query's.

__JSON-parsing:__
- De opgehaalde JSON-gegevens worden geparsed, wat betekent dat de gestructureerde JSON wordt omgezet naar bruikbare JavaScript-objecten. Dit proces is van cruciaal belang om de configuraties in een formaat te krijgen dat begrijpelijk is voor de frontend van de UI.

__Toewijzing aan UI-componenten:__
- De geparseerde JavaScript-objecten worden vervolgens toegewezen aan de juiste UI-componenten. Dit omvat het invullen van formulieren, het bijwerken van visualisaties en andere relevante stappen om de configuratie op een bruikbare manier weer te geven in de gebruikersinterface.


## Hoe wordt ervoor gezorgd dat de UI gebruiksvriendelijk blijft?
Om de UI voor deze configuraties gebruiksvriendelijk te maken en houden is feedback van de end users nodig. Deze feedback is vanaf het begin nodig. Om te zorgen dat het design is wat de end user in gedachte had, is er eerst een wireframe gemaakt. Na de feedback en goedkeuring van de product owner is er een prototype gemaakt. Met dit prototype is de UI gemaakt zoals die er uiteindelijk uit moet komen te zien en met de functionaliteiten die de UI zal bieden. Na goedkeuring van het prototype kon er begonnen worden aan de UI binnen Datapanel.
Om de onderzoeken van dit proces in meer detail door te nemen kan [hier](https://github.com/Timsel1/PortfolioS5/tree/main/Nederlands/Documentatie/2.%20UI%20Design) gekeken worden.

Conclusie
Dit onderzoek heeft inzicht geboden in de ontwikkeling van een gebruiksvriendelijke UI voor het optimaliseren van het Datapanel configuratieproces. Door het identificeren van uitdagingen bij handmatig schrijven van JSON, het begrijpen van user flows en het vaststellen van essentiële requirements, biedt het een duidelijk beeld over hoe een effectieve UI tot stand moet komen.

Belangrijk hierbij is de export en import van configuraties, waarbij een gestructureerd proces van dataconversie, overdracht naar NoCode-platform en database opslag is vastgesteld. Het continu betrekken van eindgebruikers voor feedback zorgt voor een gebruiksvriendelijke UI die voldoet aan hun behoeften.

In antwoord op de hoofdvraag: Een gebruiksvriendelijke UI voor het optimaliseren van het Datapanel configuratieproces kan worden gerealiseerd door het adresseren van uitdagingen, implementeren van essentiële functionaliteiten en voortdurende gebruikersbetrokkenheid in het ontwikkelingsproces.
