# DNS (Domain Name System)

## Waar staat de afkorting voor?
DNS staat voor **Domain Name System**.

## Definitie
Het Domain Name System (DNS), of domeinnaamsysteem, is de dienst die zorgt voor de koppeling tussen de domeinnaam en het IP-adres van een server. Internetgebruikers hoeven dan niet het exacte IP-adres van een website te kennen om deze te bereiken.

## Leg het concept uit in je eigen woorden
DNS is een soort "adresboek" voor het internet. Stel je voor dat je een vriend wilt bellen, maar je hebt alleen zijn naam, niet zijn telefoonnummer. In plaats van het nummer zelf te zoeken, vraag je aan iemand anders die het nummer kent. DNS doet hetzelfde: als je een website wilt bezoeken, zoals www.google.com, dan zoekt DNS het "telefoonnummer" (het IP-adres) van die website voor je, zodat je computer contact kan maken met de juiste website. Het helpt je dus snel de juiste website te vinden zonder dat je allemaal nummers hoeft te onthouden!

## Hoe draagt DNS bij aan de functionaliteit van het internet?
DNS maakt het mogelijk om websites te bezoeken door domeinnamen te vertalen naar IP-adressen. Het zorgt ervoor dat je gebruikerservaring snel en efficiënt is, omdat je niet handmatig een numeriek IP-adres hoeft in te voeren voor elke website die je bezoekt. DNS fungeert als een tussenpersoon die het makkelijker maakt om toegang te krijgen tot internetservices door de technische aspecten te verbergen voor de gebruiker.

### Welke rol speelt DNS bij het waarborgen van de beveiliging van online communicatie?
DNS speelt een belangrijke rol in de beveiliging van online communicatie, vooral met technieken zoals DNSSEC (DNS Security Extensions). DNSSEC helpt om te verifiëren dat de ontvangen DNS-gegevens echt zijn en niet zijn gemanipuleerd door kwaadwillenden. Dit beschermt gebruikers tegen aanvallen waarbij verkeerde DNS-gegevens worden ingevoerd, zoals DNS-spoofing.

### Welke data zou gestolen kunnen worden wanneer een hacker toegang krijgt tot dit protocol?
Als een hacker toegang krijgt tot het DNS-protocol, kan hij het volgende stelen of manipuleren:

- **Domeinnaam-informatie**: 
Dit kan leiden tot phishing-aanvallen of het omleiden van verkeer naar kwaadaardige websites.
- **Gebruikersinformatie**: 
Gevoelige gegevens zoals inloggegevens en persoonlijke informatie kunnen worden onderschept als verkeer verkeerd wordt omgeleid naar onbetrouwbare servers.
- **Communicatie-inhoud**: 
Als DNS-aanvallen niet goed worden beveiligd, kan de hacker het verkeer tussen de gebruiker en de website beïnvloeden.

### Wat zijn de mogelijke gevolgen van DNS-vertragingen voor de prestaties van websites?
DNS-vertragingen kunnen de snelheid van een website aanzienlijk beïnvloeden. Wanneer een DNS-server traag reageert of niet goed functioneert, kan het langer duren om de vertaling van een domeinnaam naar een IP-adres uit te voeren. Dit veroorzaakt vertragingen bij het laden van een website, wat de gebruikerservaring negatief beïnvloedt. Dit kan vooral problematisch zijn voor e-commercewebsites of andere websites die afhankelijk zijn van snelheid.

### Hoe kan een DNS-aanval, zoals DNS-spoofing, de internetveiligheid beïnvloeden?
DNS-spoofing is een aanval waarbij een kwaadwillende actor valse DNS-gegevens verstrekt, waardoor de gebruiker naar een valse website wordt geleid. Dit kan ernstige gevolgen hebben, zoals:

- **Phishing-aanvallen**: 
Gebruikers kunnen worden misleid om inloggegevens in te voeren op een nepsite die eruitziet als een vertrouwde website.
- **Man-in-the-middle-aanvallen**: 
De aanvaller kan de communicatie tussen de gebruiker en de website onderscheppen en manipuleren.
- **Malware-infecties**: 
Door verkeer naar kwaadaardige websites om te leiden, kan malware worden verspreid.

## Afbeeldingen ter verduidelijking
![DNS Proces](https://upload.wikimedia.org/wikipedia/commons/thumb/8/86/An_example_of_theoretical_DNS_recursion-nl.svg/500px-An_example_of_theoretical_DNS_recursion-nl.svg.png)

## Link naar een externe pagina
Voor meer gedetailleerde uitleg over DNS, kun je [hier klikken](https://nl.wikipedia.org/wiki/Domain_Name_System).

## Link naar een header op dezelfde pagina
- [Definitie van DNS](#definitie)

## Tabel
| Onderdeel        | Omschrijving                                              |
|------------------|-----------------------------------------------------------|
| **DNS**          | Het systeem dat domeinnamen naar IP-adressen vertaalt.    |
| **DNSSEC**       | Een beveiligingsprotocol om DNS-gegevens te verifiëren.  |
| **DNS-spoofing** | Een aanval waarbij nep-DNS-gegevens worden verstrekt.    |

## Bronvermelding (volgens de APA-regels)
Wikipedia. (2023). *Domain Name System*. Geraadpleegd op 10 februari 2025, van https://nl.wikipedia.org/wiki/Domain_Name_System