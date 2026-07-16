# Proximity Privacybeleid

Status: conceptinhoud voor integratie, staging en productreview.

Dit concept-privacybeleid bestaat zodat productbuilds een realistische, scrollbare en geversioneerde privacyverklaring kunnen tonen voordat definitieve juridische goedkeuring is verleend. Het weerspiegelt de categorieën gegevens die de dienst naar verwachting zal verwerken en de operationele redenen waarom die categorieën kunnen worden gebruikt, maar blijft onderworpen aan juridische en compliancebeoordeling.

Door een build te gebruiken die naar deze repository verwijst, erken je dat dit document voorlopig is en kan veranderen vóór een productielancering of bredere publieke uitrol.

## 1. Gegevenscategorieën die wij verwachten te verwerken

Afhankelijk van de functies die in een bepaalde build zijn ingeschakeld, kan de dienst accountidentificatoren, informatie over authenticatieproviders, profielmetadata, taalvoorkeuren, grove of door het apparaat verstrekte locatiesignalen, app-interactiegebeurtenissen, supportcommunicatie en apparaatdiagnostiek verwerken die nodig zijn om het product te laten functioneren.

Sommige functies kunnen ook afhankelijk zijn van tijdelijke status die aangeeft of je onboarding hebt voltooid, de nieuwste juridische documenten hebt geaccepteerd, vereiste toestemmingen hebt verleend of via het product met andere gebruikers hebt geïnteracteerd.

## 2. Waarom wij verwachten gegevens te verwerken

Wij verwachten gegevens te verwerken om gebruikers te authenticeren, taal- en onboardingstromen te personaliseren, productgedrag met betrekking tot nabijheid te bepalen, veiligheidscontroles te ondersteunen, misbruik te onderzoeken, de betrouwbaarheid van de dienst te behouden en de productkwaliteit te verbeteren tijdens ontwikkeling en releasevoorbereiding.

In beperkte gevallen kunnen operationele logs of moderatiegerelateerde records ook worden bewaard om incidenten te begrijpen, fouten te reproduceren, op meldingen te reageren en handhavingsbeslissingen vast te leggen.

## 3. Locatiegerelateerde signalen

Omdat Proximity is gebouwd rond discovery-functies in de nabijheid, kunnen sommige builds door het apparaat verstrekte locatie of gerelateerde afgeleide signalen gebruiken om te bepalen of relevante productinteracties moeten worden getoond. De exacte precisie, bewaartermijn en server-side verwerking blijven onderworpen aan product- en juridische beoordeling.

Dit concept is bewust voorzichtig: het beschrijft verwachte categorieën en doeleinden zonder een definitieve productie-implementatie te claimen waar nog geen goedkeuring voor bestaat.

## 4. Bewaarbenadering

Wij verwachten verschillende categorieën gegevens gedurende verschillende perioden te bewaren afhankelijk van productbehoefte, veiligheidseisen, operationele debugging, wettelijke verplichtingen en de levenscyclusstatus van het account. Sommige informatie kan worden verwijderd of geanonimiseerd wanneer die niet langer nodig is, terwijl andere records langer bewaard moeten blijven om incidenten of beveiligingsgebeurtenissen te documenteren.

Specifieke bewaarschema's worden in een latere goedgekeurde versie vastgesteld.

## 5. Delen en dienstverleners

Wij kunnen vertrouwen op aanbieders van infrastructuur, authenticatie, analytics, klantenondersteuning, hosting of beveiliging om de dienst te exploiteren. Waar providers worden gebruikt, verwachten wij dat toegang wordt beperkt tot wat redelijkerwijs nodig is voor de relevante functie en onderworpen is aan contractuele en beveiligingsmaatregelen die passend zijn voor de definitieve implementatie.

Het is niet de bedoeling dat dit concept een definitieve leverancierslijst of een volledig productie-datastroomschema suggereert.

## 6. Gebruikerscontroles

Afhankelijk van het productscherm kunnen gebruikers profielinformatie kunnen bijwerken, de interfacetaal kunnen wisselen, versies van juridische documenten kunnen bekijken, bepaalde toestemmingen kunnen intrekken of verwijdering van hun account kunnen verzoeken. De exacte controles die in productie beschikbaar zijn, kunnen afwijken van wat beschikbaar is in een ontwikkel- of stagingbuild.

## 7. Conceptstatus

Dit document is een werkconcept dat bedoeld is ter ondersteuning van integratie en review. Het is geen definitieve productieprivacyverklaring en mag niet worden behandeld als de laatste goedgekeurde verklaring over hoe de live dienst persoonsgegevens verwerkt.
