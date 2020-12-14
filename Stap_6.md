**[Inhoud](ToC.md)**

### :six: Stap 6: Ontsluit de data

Data kan op verschillende manieren ontsloten worden.

De meest gebruikte manier is het aanbieden van een downloadbaar bestand, bijvoorbeeld een CSV- of GeoJSON-file. Het nadeel is dat de gebruiker steeds opnieuw het bestand moet downloaden als er een nieuwe versie beschikbaar komt. Veel toepassingen halen eenmalig de data op, slaan die zelf op en gebruiken die om een dashboard of kaart te maken. Het is in die situatie lastig te beoordelen of de meest actuele versie van de data worden gebruikt. En voor de aanbieder/eigenaar van de data is er geen zicht op de toepassingen die gebruik maken van een dataset.

### API´s en webservices
Een andere manier is het bieden van een API (Application Programming Interface) of webservices [^1]. Dit is als het ware een online stopcontact om permanent data op te vragen. Het grote voordeel is dat het gebruik van de data beter te monitoren is, dat de gebruiker altijd beschikt over de meest recente data en die data niet zelf hoeft op te slaan. Voor beleidsmonitoring zijn API’s of webservices daarom meer geschikt. Zo wordt in het Digitaal Stelsel Omgevingswet sterk ingezet op de ontwikkeling van open API´s (conform de OpenAPI-specificatie) en komt er een ontwikkelaarsportaal waar alle beschikbare API’s gevonden kunnen worden (inclusief documentatie).

> In de publicatie "Harmonised Smart City APIs - A Cook Book for Cities ([zie bibliotheek](Bibliotheek.md)) worden voordelen van standaard API´s goed beschreven.

Naast een API zijn er nog enkele manieren om data te ontsluiten. Een aantal voorbeelden van (standaard) services zijn:
1.	Geo-services, zoals vastgesteld door het Open Geo Consortium (OGC) [^2]
2.	NGSI API vann FIWARE

Voor geo-informatie (en direct van belang in het kader van de Omgevingswet), is de INSPIRE-plicht. INSPIRE is een Europese richtlijn voor het beschikbaar stellen van geo-informatie. Dat gebeurt nu op verschillende niveaus, onder meer via het Nationaal Geo Register. Een deel van de gegevens en informatieproducten die in de context van de Omgevingswet beschikbaar moeten komen, vallen onder INSPIRE en zullen conform die standaarden beschikbaar moeten worden gesteld. Een reden te meer om goed na te denken over een catalogus om de (interne) informatie te registeren en beheren.

Het doel van data ontsluiting is o.a. dat de gegevens gebruikt worden voor nieuwe toepassingen. Zoals een klimaatatlas, 3D-model of app. Door de ontsluiting van data te scheiden van de toepassingen, wordt ook aangesloten bij de visie die VNG Realisatie heeft geformuleerd onder de naam "Common Ground" (https://vng.nl/samen-organiseren/common-ground). 

[^1]: Difference between API and Webservice: https://medium.com/@programmerasi/difference-between-api-and-web-service-73c873573c9d
[^2]: OGC-standaarden - http://www.opengeospatial.org/docs/is

**[Inhoud](ToC.md)**
