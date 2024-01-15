# Hoe kan de kwaliteit van de code van de backend worden gewaarborgd?
De backend service die is gecreëerd kan over de tijd veranderen, wanneer dit gebeurt moet er een manier zijn om te checken of deze service nog steeds functioneert zoals verwacht.

## Hoe heb ik dit opgelost?
Binnen Stofloos wordt er binnen Datapanel gebruikgemaakt van unit tests met behulp van het Jest-framework. Dit draagt bij aan het waarborgen van de kwaliteit van de code door de functionaliteit van afzonderlijke eenheden in isolatie te testen. Op basis van deze gevestigde aanpak heb ik ervoor gekozen om dezelfde methode te hanteren bij het testen van mijn code. Door Jest te gebruiken voor mijn testscenario's, kan ik vertrouwen op een gestructureerde en solide aanpak voor het testen van functionaliteiten, waardoor zowel de nauwkeurigheid als de betrouwbaarheid van de code worden geoptimaliseerd.

Om tijd te besparen heb ik voor het proces van het schrijven chat gtp gebruikt, ik hoefde op deze manier alleen mijn code blok te sturen en te zeggen wat voor een test ik wilde hebben. Vervolgens hoefde ik alleen nog het verwachtte resultaat aan te passen op de testdata die ik van tevoren had gemaakt.

|Prompt|ChatGPT reactie|
|:----:|:-------------:|
|![ChatgptPrompt](https://github.com/Timsel1/PortfolioS5/assets/90602424/e9d6be44-2c5a-4043-a668-32d45e8a4f31)|![ChatGPTErrorTest](https://github.com/Timsel1/PortfolioS5/assets/90602424/ba324058-14a1-4e7e-9180-8b0a6a9637dd)|

## Wat is het resultaat?
Voor al mijn relevante codeblokken heb ik uitgebreide testscenario's opgesteld. Deze tests omvatten zowel situaties waarin de code succesvol wordt afgehandeld als scenario's waarin de code fouten kan vertonen. Uit de resultaten van deze tests blijkt dat mijn code zich gedraagt zoals ik had verwacht en de beoogde functionaliteit correct uitvoert.

|Test resultaten|
|:-------------:|
|![UnitTests](https://github.com/Timsel1/PortfolioS5/assets/90602424/f753bc41-06c0-42b5-a738-c2c40a0711c9)|

Wat misschien opvalt wanneer er wordt gekeken naar mijn tests is dat ik geen specifieke tests heb hoeven uitvoeren voor de informatieoverdracht naar de database. Dit komt doordat deze functionaliteit al bestond in het project, en dus eerder uitgebreid is getest.
Aangezien mijn code de functionaliteit van het aanmaken van de componenten en het overdragen van deze componenten eerst in dezelfde functie deed, moest ik mijn code aanpassen, om dit te scheiden. Dit heb ik gedaan na feedback te hebben ontvangen van mijn stagebegeleider, die dit heeft aangeraden.

## Wat is de kwaliteit van het resultaat?
De kwaliteit van dit resultaat spreekt voor zich, alle nieuwe code die ik heb toegevoegd is met succes getest op zowel succesvolle als gefaalde afhandelingen. Dit valideert mijn werk aan de backend service die ik voor dit project heb moeten maken.

## Wat is de volgende stap nu ik dit resultaat heb?
Nu de code werkt en is gevalideerd, kan ik beginnen met het valideren van mijn volledige project, door middel van usability testing.

