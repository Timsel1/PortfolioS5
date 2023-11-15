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
Meer informatie en onderbouwing is [hier](https://github.com/Timsel1/PortfolioS5/blob/main/Nederlands/Documentatie/Research/Kwaliteitseisen.md) te vinden.

## Hoe worden de in de ui gemaakte configuraties geëxporteerd naar json?

## Hoe worden de opgeslagen configuraties geïmporteerd naar de UI?

## Hoe wordt ervoor gezorgd dat de UI gebruiksvriendelijk blijft?
Om de UI voor deze configuraties gebruiksvriendelijk te maken en houden is feedback van de end users nodig. Deze feedback is vanaf het begin nodig. Om te zorgen dat het design is wat de end user in gedachte had, is er eerst een wireframe gemaakt. Na de feedback en goedkeuring van de product owner is er een prototype gemaakt. Met dit prototype is de UI gemaakt zoals die er uiteindelijk uit moet komen te zien en met de functionaliteiten die de UI zal bieden. Na goedkeuring van het prototype kon er begonnen worden aan de UI binnen Datapanel.
Om de onderzoeken van dit proces in meer detail door te nemen kan [hier](https://github.com/Timsel1/PortfolioS5/new/main/Nederlands/Documentatie/Research/UIDesign) gekeken worden.

