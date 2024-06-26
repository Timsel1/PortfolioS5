# Hoe is Stofloos situatie verbeterd sinds Datapanel is opgezet?
Dit onderzoek biedt inzicht in de specifieke manieren waarop Datapanel de bedrijfssituatie heeft verbeterd. Op deze manier begrijp ik het doel van Datapanel en heb ik een beter inzicht gekregen van de requirements voor mijn project. Ook ben ik beter in staat om mogelijke optimalisaties voor te stellen en deze ook daadwerkelijk te implementeren. 

## Welke uitdagingen waren er voordat Datapanel was opgezet?
Voor de implementatie van Datapanel maakte Stofloos handmatig custom beheeromgevingen voor elk project waar ze aan werkten. Deze aanpak vroeg niet alleen aanzienlijke tijdsinvesteringen, maar stelde ook klanten voor het dilemma van het betalen voor een custom beheeromgeving, dit was niet iets waar klanten graag voor betaalde. Deze uitdagingen brachten dus twee lasten met zich mee, op het gebied van zowel efficiëntie als financiële haalbaarheid. Het gebrek aan een generieke beheeromgeving hinderde de mogelijkheid om snel en kosteneffectief te werken aan de behoeften van verschillende klanten, dit benadrukte de noodzaak voor een meer schaalbare en generieke benadering.

**(Field - Interview)**
 
## Wat waren de voorafgaande verbeteringen aan Datapanel en waarom waren deze nodig?
De ontwikkeling van Datapanel is een langdurig proces met geleidelijke verbeteringen, beginnend met de implementatie van generieke beheeromgevingen. In de eerste fase van dit proces lag de focus op het generiek maken van de frontend, waardoor een inlogomgeving ontstond, gekoppeld aan een API, waarmee gegevens konden worden bekeken en bewerkt. Dit initieerde de creatie van de generieke componenten die Stofloos op het moment gebruikt.

De volgende stap was de ontwikkeling van een backend-library die endpoints kan omzetten naar projecten. Deze stap legde het fundament voor de No Code API en gateway die bij verschillende projecten ingezet kon worden, dit kon gezien worden als een boilerplate.
Na de integratie van deze verbeteringen ontstond er één configuratie voor de gehele Datapanel omgeving. De grootte van deze gecentraliseerde configuratie groeide enorm, waardoor het beheer ervan een uitdaging werd. De toename in complexiteit en omvang hinderde het overzicht en onderhoud, waardoor er een behoefte ontstond om de configuratie op te splitsen in meerdere modellen. Deze aanpassing was cruciaal om de beheerbaarheid en efficiëntie te garanderen in de Datapanel omgeving.

De opsplitsing van de Datapanel configuratie in meerdere modellen bracht een uitdaging met zich mee. De UI was niet langer compatibel met de vernieuwde configuratiestructuur. Deze herstructurering beperkte de beschikbare mogelijkheden tot een overzichts- en detailpagina. Met de mogelijkheid om alleen deze type pagina’s te maken was er weinig flexibiliteit voor verdere aanpassingen, waardoor de behoefte ontstond om de interface te verbeteren en uit te breiden. Dit is hoe mijn stageopdracht is ontstaan.

**(Field - Interview)**
 
## Hoe ziet de huidige situatie eruit?
De huidige situatie van Datapanel ziet er zoals eerder beschreven uit. De configuratie van Datapanel is opgesplitst in meerdere modellen, wat het beheer van deze configuraties heeft verbeterd. Het compatibility probleem dat was ontstaan was dus aanwezig. Om dit probleem op te lossen, was er een opdracht ontstaan om een nieuwe UI te ontwikkelen binnen Datapanel die wel volledig compatibel is met de huidige configuratiestructuur. Op het moment van schrijven is de nieuwe UI functioneel af, maar er ontbreken nog enkele kwaliteitsfuncties die de gebruikservaring nog meer zouden verbeteren. 

Voor meer informatie over de huidige situatie kan [hier](../01.%20Opzet%20van%20het%20Project/Projectplan.md#projectopdracht) in het projectplan worden gekeken. Dit gaat niet specifiek in op de huidige situatie, maar beschrijft wel het probleem met de huidige situatie in meer detail.

## Is de huidige situatie de ideale situatie? 
De huidige situatie kan nog niet als ideaal worden beschouwd, omdat er enkele verbeteringen en optimalisaties zijn die nog moeten worden toegepast. De door mij ontwikkelde UI bevat nog enkele optimalisaties en features die moeten worden geïmplementeerd om de gebruikservaring nog verder te verbeteren. Daarnaast is er een conceptueel ideaal, waarbij het gebruik van AI wordt overwogen in combinatie met een configuratie genererende service bij het maken van configuraties. Hierbij zou de service de configuratie genereren en de AI zou in de database bepalen welke tabellen belangrijk zijn en bepaald wat er wordt laten zien, hierna zou de door mij gemaakte UI nog kunnen worden gebruikt om dit te finetunen. Op dit moment staat dit concept niet direct op de agenda en vereist het nog verdere overweging en planning. Met voortdurende inspanningen zal de huidige situatie transformeren naar een ideale staat waarin alle geplande verbeteringen zijn geïmplementeerd.

**(Field - Interview)**

## Conclusie
Dit onderzoek laat de transformatie van Stofloos' bedrijfssituatie met de implementatie van Datapanel zien. Van de voorgaande problemen met tijdsintensieve handmatige configuraties, naar de huidige situatie. Datapanel heeft de bedrijfsprocessen gestroomlijnd, met een geleidelijke evolutie. Mijn bijdrage aan het ontwikkelen van een nieuwe, compatibele UI binnen Datapanel is weer een extra stap in deze progressie. Hoewel de huidige situatie nog verdere optimalisaties kan gebruiken, is de richting duidelijk: Datapanel functioneert als een essentieel component voor efficiëntie, waardoor Stofloos in staat is om flexibel en tijd efficiënt te werken.
