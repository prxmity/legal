# Proximity Datenschutzrichtlinie

Status: Entwurfsinhalt fuer Integration, Staging und Produktpruefung.

Diese Datenschutzrichtlinie als Entwurf dient dazu, dass Produkt-Builds schon vor der endgueltigen rechtlichen Freigabe einen realistischen, scrollbaren und versionierten Datenschutzhinweis anzeigen koennen. Sie beschreibt die Datenkategorien, die der Dienst voraussichtlich verarbeitet, sowie die betrieblichen Gruende fuer diese Verarbeitung, bleibt aber rechtlich und organisatorisch vorlaeufig.

Durch die Nutzung eines Builds, der auf dieses Repository verweist, bestaetigst du, dass dieses Dokument vorlaeufig ist und sich vor einem Produktionsstart oder breiteren oeffentlichen Rollout noch aendern kann.

## 1. Datenkategorien, die wir voraussichtlich verarbeiten

Je nach in einem Build aktivierten Funktionen kann der Dienst Konto-Identifikatoren, Informationen des Authentifizierungsanbieters, Profilmetadaten, Sprachpraeferenzen, ungefaehre oder geraetebasierte Standortsignale, Interaktionsereignisse in der App, Support-Kommunikation und fuer den Betrieb erforderliche Geraetediagnosen verarbeiten.

Einige Funktionen koennen zudem temporaere Statusdaten nutzen, etwa dazu, ob du das Onboarding abgeschlossen, die aktuellen Rechtstexte akzeptiert, erforderliche Berechtigungen erteilt oder mit anderen Nutzern ueber das Produkt interagiert hast.

## 2. Warum wir Daten voraussichtlich verarbeiten

Wir erwarten, Daten zu verarbeiten, um Nutzer zu authentifizieren, Sprach- und Onboarding-Ablaufe zu personalisieren, produktbezogene Naehefunktionen zu steuern, Sicherheitspruefungen zu unterstuetzen, Missbrauch zu untersuchen, die Zuverlaessigkeit des Dienstes aufrechtzuerhalten und die Produktqualitaet waehrend Entwicklung und Release-Vorbereitung zu verbessern.

In begrenzten Faellen koennen auch Betriebsprotokolle oder moderationsbezogene Aufzeichnungen vorgehalten werden, um Vorfaelle zu verstehen, Fehler zu reproduzieren, Meldungen zu bearbeiten und Durchsetzungsentscheidungen zu dokumentieren.

## 3. Standortbezogene Signale

Da Proximity auf Funktionen zur Anzeige naher Kontakte aufbaut, koennen manche Builds geraetebasierte Standortdaten oder daraus abgeleitete Signale verwenden, um zu bestimmen, ob relevante Produktinteraktionen angezeigt werden sollen. Die genaue Praezision, Aufbewahrungsdauer und serverseitige Verarbeitung bleiben Gegenstand der Produkt- und Rechtspruefung.

Dieser Entwurf ist bewusst vorsichtig formuliert: Er beschreibt erwartete Kategorien und Zwecke, ohne eine final freigegebene Produktionsimplementierung zu behaupten.

## 4. Aufbewahrungsansatz

Wir erwarten, unterschiedliche Datenkategorien fuer unterschiedliche Zeitraeume aufzubewahren, abhaengig von Produktbedarf, Sicherheitsanforderungen, operativer Fehleranalyse, rechtlichen Pflichten und dem Status des Kontolebenszyklus. Manche Informationen koennen geloescht oder anonymisiert werden, sobald sie nicht mehr erforderlich sind, waehrend andere Aufzeichnungen laenger vorgehalten werden muessen, um Vorfaelle oder Sicherheitsereignisse zu dokumentieren.

Konkrete Aufbewahrungsfristen werden in einer spaeteren freigegebenen Version finalisiert.

## 5. Weitergabe und Dienstleister

Wir koennen Infrastruktur-, Authentifizierungs-, Analyse-, Support-, Hosting- oder Sicherheitsanbieter einsetzen, um den Dienst zu betreiben. Falls Dienstleister genutzt werden, soll ihr Zugriff auf das fuer die jeweilige Funktion angemessen Erforderliche begrenzt sein und vertraglichen sowie sicherheitsbezogenen Kontrollen unterliegen, die zur finalen Implementierung passen.

Dieser Entwurf soll keine endgueltige Liste von Dienstleistern oder einen abgeschlossenen Produktions-Datenfluss suggerieren.

## 6. Nutzerkontrollen

Je nach Produktoberflaeche koennen Nutzer Profilinformationen aktualisieren, die Interface-Sprache wechseln, Versionen von Rechtstexten einsehen, bestimmte Berechtigungen widerrufen oder die Loeschung des Kontos anstossen. Welche Kontrollen in Produktion verfuegbar sein werden, kann sich von Entwicklungs- oder Staging-Builds unterscheiden.

## 7. Entwurfsstatus

Dieses Dokument ist ein Arbeitsentwurf fuer Integration und Pruefung. Es ist kein finaler Datenschutzhinweis fuer die Produktion und sollte nicht als letzte freigegebene Aussage zur Verarbeitung personenbezogener Daten im Live-Dienst verstanden werden.
