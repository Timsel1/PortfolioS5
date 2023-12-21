# Uitbreiding Projectplan voor de Backend

## De opdracht
Er moet een service worden gemaakt voor het syncen van de models en modelviews. Alle models met bestaande modelviews, moeten worden bijgewerkt, zonder dat de custom settings die eerder gezet kunnen zijn verloren gaan. 
Voor alle models waarvoor nog geen modelviews bestaan moeten modelviews met 2 pages (table en details) met bijbehorende subpages en secties worden gegenereerd met standaardwaarden.   
Hiervoor moeten ook tests worden geschreven, er kan hierbij getest worden of alle componenten correct worden aangemaakt en aan elkaar gekoppeld worden, of er geen oude data verloren gaat, etc.  
Het zou eventueel ook nog fijn zijn als je kunt zien welke modelviews en bijbehorende componenten nog alle standaardwaarden hebben, zodat je weet dat je deze veilig kunt verwijderen, zonder dat er iets verloren gaat, aangezien deze weer automatisch worden aangemaakt met deze standaardwaarden.

## Doel van het project
Op het moment is er een UI met de minimaal nodige functionaliteit om op een plek modelviews, pages, subpages en secties aan te maken. Op het moment moet er zelf nog worden gekeken naar of deze modelviews 
zijn gekoppeld aan bestaande models en als dit niet het geval is moet dit handmatig in de UI worden gedaan. Om dit simpele proces nog makkelijker en efficiënter te maken moet er een service komen die dit automatisch 
doet. Op deze manier kan er wanneer er een model is aangemaakt, met een druk op een knop een overview en details pagina worden gegenereerd voor dit model door middel van een standaardconfiguratie.

## Stappenplan
- Voeg een service toe voor het ophalen en vergelijken van models:
  - Implementeer een service in de gebruikersinterface om alle beschikbare models op te halen.
  - Vergelijk de opgehaalde models met bestaande modelviews en log de modellen zonder modelviews.
- Definieer een standaardconfiguratie voor een modelview:
  - Bepaal de standaardconfiguratie voor een modelview, inclusief de standaardpagina's, subpages en secties.
  - Overweeg ook de standaardwaarden voor elk veld binnen de modelview.
- Update de service voor het aanmaken van modelviews:
  - Breid de service uit om een modelview aan te maken voor de modellen zonder modelviews, gebruikmakend van de standaardconfiguratie.
- Implementeer standaardconfiguraties voor pages, subpages en sections:
  - Definieer standaardconfiguraties voor elke pagina, subpagina en sectie binnen een modelview.
  - Zorg ervoor dat deze standaardconfiguraties kunnen worden toegepast bij het aanmaken van de bijbehorende componenten.
- Breid de service uit voor het aanmaken van pages, subpages en sections:
  - Werk de service bij om automatisch pagina's, subpagina's en secties aan te maken voor de modelviews zonder deze componenten, gebruikmakend van de standaardconfiguraties.
- Implementeer een functie voor het koppelen van componenten:
  - Creëer een functie die automatisch de verschillende componenten aan elkaar koppelt, zoals modelview aan page, page aan subpage, en subpage aan section.
  - Deze functie moet controleren of de koppelingen al zijn gemaakt en zo niet, deze tot stand brengen.
- Voeg een controle toe voor gekoppelde models:
  - Implementeer een controlemechanisme om te identificeren of models al zijn gekoppeld aan een modelview.
  - Voorkom dat een nieuw modelview wordt aangemaakt voor een model dat al is gekoppeld.
- Maak een updatefunctie voor modelviews en componenten:
  - Ontwikkel een functie die modelviews en bijbehorende componenten bijwerkt wanneer er nieuwe velden worden toegevoegd aan de modellen.
  - Zorg ervoor dat de bestaande gegevens behouden blijven bij het updaten van de modelviews.
- Maak tests:
  - Maak tests om de nieuwe functionaliteiten te dekken, inclusief het ophalen van models, aanmaken van modelviews, en koppelen van componenten.
  - Zorg ervoor dat de tests de juiste werking van het bijwerken en toevoegen van nieuwe velden testen.
- Documenteer de uitbreidingen:
  - Documenteer de nieuwe functionaliteiten, inclusief de service, standaardconfiguraties, controlemechanismen en updatefuncties.

## Scope

|Tot het project behoort:|Tot het project behoort niet:|
|:---------------------:|:----------------------------:|
|Een service voor het synchroniseren van de database, m.b.t. models en modelviews.|Volledig uitwerken van low priority features|
|Het schrijven van unit tests voor de gemaakte code.|Opzetten van CI/CD|
|Documentatie over de nieuwe functionaliteiten.||







