# Welke aanpassingen moeten worden gemaakt om de huidige “cards” generiek te maken?
Voor mijn overview pagina’s wil ik gebruik maken van bestaande “cards” binnen Stofloos Datapanel. Deze “cards” zijn op het moment niet herbruikbaar 
en als ik deze in de huidige staat wil gebruiken moet ik alle html en css kopiëren naar alle overview pagina’s. Aangezien dit onhandig is moet ik 
een component en later configuratie maken van deze "cards".

## Hoe heb ik dit gedaan?
Ik ben begonnen met het maken van 2 Lit componenten, “swc-view-card” en “swc-cards-overview”. “swc-view-card” genereert de html, css en logica voor 1 kaartje,
“swc-cards-overview” krijgt een array van alle items uit de database en gebruikt deze array om voor elk item een kaartje te genereren. Ik gaf alle informatie 
door aan de hand van properties, na het vragen van feedback bleek dat ik de “cards” verkeerd aan het implementeren was. Ik moest de informatie op de kaartjes laten 
zien aan de hand van een configuratie, dit is een array van objecten.
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/847bf801-9936-4a9b-be37-1b278d6a2b14" width=400px; />

en de titel van een kaartje moest worden geladen aan de hand van een “title config”, als deze beschikbaar was.
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/b06a5ba9-a94e-417c-afed-0b6adc78c36d" width=400px; />

Dit heb ik voor elkaar gekregen door hulp te vragen aan de developers bij Stofloos.

## Wat is het resultaat?
Ik heb nu een overview pagina voor de modelviews, pages, subpages en secties met “cards” die werken aan de hand van configuraties voor het laten zien van informatie. 
Ids worden nog niet correct weergegeven, dit ligt aan de custom functie van stofloos.
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/3723c185-53b7-46ff-80cb-ab6aa24c5ae5" width=400px; />


## Wat is de kwaliteit van het resultaat?
Ik heb tijdens het proces mijn stagebegeleider meerdere keren laten zien waar ik mee bezig was en hij heeft me geholpen waar nodig. Daardoor weet ik zeker dat de “cards” correct zijn opgebouwd en geïntegreerd.

## Wat is de volgende stap nu ik dit resultaat heb?
Nu ik de overviews af heb kan ik werken aan de tabjes, die gebruikt kunnen worden om te switchen tussen de overviews van modelviews, pages, subpages en secties.
