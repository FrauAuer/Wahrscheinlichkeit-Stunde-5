# Würfel-Statistik Web-App

Diese Web-App ermöglicht es Kindern, die Häufigkeiten von Augensummen beim Würfeln einzugeben und die Ergebnisse anschließend gemeinsam auszuwerten. Die Daten werden in Firebase gespeichert und im Dashboard als Tabelle und Säulendiagramm dargestellt.

## Funktionen

- Eingabe der Augensummen 2 bis 12 über eine übersichtliche Tabelle
- automatische Berechnung der Gesamtzahl der Würfe
- Speicherung der Gruppenergebnisse in Firebase Realtime Database
- Anzeige aller Gruppenergebnisse in einer gemeinsamen Übersicht
- grafische Darstellung der Gesamtergebnisse als Säulendiagramm
- numerische Sortierung der Gruppennummern
- Nutzung der Schriftart Fibel Nord in normal und fett

## Projektdateien

- `index.html` – Eingabeseite für die Gruppen
- `dashboard.html` – Auswertungsseite mit Tabelle und Diagramm
- `firebase-config.js` – Verbindung zur Firebase-Datenbank
- `FibelNord-Regular.ttf` – normale Schriftdatei
- `FibelNord-Bold.ttf` – fette Schriftdatei

## Voraussetzungen

- ein Firebase-Projekt mit aktivierter Realtime Database
- korrekt eingetragene Firebase-Zugangsdaten in `firebase-config.js`
- alle Projektdateien im selben Ordner

## Projektstruktur

```text
projektordner/
├── index.html
├── dashboard.html
├── firebase-config.js
├── FibelNord-Regular.ttf
└── FibelNord-Bold.ttf
```

## Einrichtung

1. Ein Firebase-Projekt anlegen.
2. In Firebase die Realtime Database aktivieren.
3. Die Zugangsdaten in `firebase-config.js` eintragen.
4. Alle Dateien gemeinsam in ein GitHub-Repository oder auf einen Webserver hochladen.
5. Darauf achten, dass beide Schriftdateien im selben Ordner wie die HTML-Dateien liegen.

## Hinweise zur Nutzung

- Die Gruppennummer darf nur aus Zahlen bestehen.
- Leere Eingabefelder werden automatisch wieder zu `0`.
- Führende Nullen werden automatisch entfernt.
- Gespeichert wird unter dem Pfad `Stunde5/<passwort>/groups/<gruppennummer>`.
- Über den URL-Parameter `?lesson=` kann das Passwort bereits vorausgefüllt werden.

## Einsatz im Unterricht

Die Anwendung eignet sich für Unterrichtsvorhaben, in denen Kinder Zufallsexperimente durchführen, Ergebnisse sammeln und Häufigkeiten auswerten. Besonders passend ist sie für das gemeinsame Untersuchen von Augensummen beim Würfeln mit zwei Würfeln.

## Autorin

Leonie Auer
