# Hoe worden componenten conditioneel geladen op basis van een json schema? (1)
Een sectie binnen Datapanel heeft verschillende content types, op basis hiervan moeten verschillende properties worden laten zien. Aangezien bijna alle properties worden geladen op basis van json schemas, moet ik een manier vinden om een generiek json schema te maken dat alleen de properties laat zien die bij het content type horen.

## Hoe heb ik dit opgelost?
Ik heb gebruik gemaakt van chat gpt en gevraagd of er een mogelijkheid was om alleen een deel van een schema te gebruiken, gebaseerd op een type dat eerder in hetzelfde schema staat. Ik kreeg 
een voorbeeld terug en een naam voor dit principe, conditional json schemas. 
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/3e239015-7258-4212-bd61-00755802d258" style=" width=500px;" />

Hierna heb ik gezocht naar conditional json schemas, om te zien hoe het wordt gebruikt. Door dit op te zoeken, vond ik meerdere manieren voor conditional schemas. Door de voorbeelden die ik heb gevonden bleek de manier van “if, then, else”
de beste oplossing te zijn voor mijn probleem.       
Deze oplossing werkte niet meteen, de json-configurator component kon deze conditional statements nog niet uitlezen. Hiervoor heb ik hulp gevraagd van een van de Stofloos developers en hierna werkte de conditional json schema.  
De site die ik heb gebruikt als voorbeeld voor de verschillende methodes is [hier](https://json-schema.org/understanding-json-schema/reference/conditionals) te vinden.

## Wat is het resultaat?
Er kan nu een content type worden gekozen door een user en de bijbehorende properties worden hierbij laten zien. De user kan deze hierna aanpassen. De user kan nog niet in de mapjes voor object en arrays.
<img src="https://github.com/Timsel1/PortfolioS5/assets/90602424/617092fe-c3e0-426b-bb25-da2f60c1f2cd" style=" width=200px;" />

## Wat is de kwaliteit van het resultaat?
Ik heb dit gemaakt samen met een van de developers van Stofloos, dit heeft ervoor gezorgd dat alles op de juiste manier is geïmplementeerd en de kwaliteit van de code voldoet aan de standaard die hier wordt aangehouden.

## Wat is de volgende stap nu ik dit resultaat heb?
De volgende stap zal zijn om de mapjes van objecten en arrays functioneel te maken en te checken of dit ook correct wordt toegepast in de database.
