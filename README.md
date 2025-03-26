> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Oncollaboration
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving

Ik heb een webinar overzichtspagina gemaakt voor mijn opdrachtgever Oncollaboration. De opdracht was om de huidige site opnieuw vorm te geven en de data te gebruiken van de database. Ik heb gekozen om te beginnen met een overzichtspagina van de webinars. Op deze pagina kan je alle webinars die in de database staan terug vinden. <br>

**Live site:** https://server-side-rendering-server-side-website-feus.onrender.com/ 

Voor mijn pagina heb ik gebruik gemaakt van het meegeleverde Figma design, de huidige live site en de studenten sites. De huisstijl is hier ook op gebasseerd, evenals de layout.

https://github.com/user-attachments/assets/607f00db-e960-4d93-b06d-ded291091981

De pagina is ook voor mobiel erg toegankelijk gemaakt, doormiddel van een scroll bar bij de categorie knoppen, en de toevoeging van een uitklapbaar hamburger menu. De gebruikers van deze site zullen namelijk vooral op hun mobiel de site bekijken, werd door de opdrachtgever benadrukt. 

https://github.com/user-attachments/assets/0d142699-af4f-4bc4-a5fe-c6da16fb4fea


<!-- In de Beschrijving staat kort beschreven wat voor project het is en wat je hebt gemaakt -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

## Gebruik
Als je op de overzichtspagina bent, zie je meteen alle webinars netjes uitgelijnd in beeld. Hier staat de titel van de webinar, de spreker, de datum wanneer hij is geupload en de categorie waarbij deze aansluit getoond onder de webinar thumbnail. Deze stukjes informatie geven de gebruiker een beter beeld wat de betreffende webinar inhoud. 

Ik heb mobile first gewerkt, voornamelijk ook omdat dit het aparaat is waar de site voornamelijk op zal worden bekeken. Ik heb breakingpoints gemaakt vanaf 768px (tablet) en 1024px (desktop). Deze heb ik toegepast doormiddel van media queries. Onder de 768px pakt hij stanaard het mobile design, omdat dit hoe dan ook toegankelijk is. 

https://github.com/user-attachments/assets/65629490-800c-4bb9-8f94-953923aedd3c

<!--Bij Gebruik staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

Ik heb gebruik gemaakt van Node.js, Express en CSS. Met Node.js en Liquid genereer ik dynamische HTML om mijn pagina interactief te maken.

**app.get('/', async function (request, response)** <br>
Hier wordt alle data opgehaald die ik hierin heb gezet. Dit is momenteel alle data van de webinar overzichtspagina. Deze staat nu ook in de index.liquid. 
<br>
https://github.com/kimnikitaschijf/server-side-rendering-server-side-website/blob/8b1e7bf7a13209bea608e3a55d6b689885cd1cf4/server.js#L35-L43

Ik heb nog geen route voor de detail pagina's toegevoegd. Dit ga ik volgende srpint toevoegen. 


## Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->

1. Download en installeer Node.js.
2. Fork deze repository naar je eigen GitHub-account.
3. Clone de repository naar je laptop.
4. Open de repository in VS code. 
5. Open de terminal in de map van je project in VS Code.
6. Installeer de benodigde pakketten door het volgende commando in de terminal uit te voeren:
**npm install**
7. Start de server met het commando:
**npm start**
Bekijk je project door de lokale host-link die in de terminal verschijnt te openen in je browser.

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
