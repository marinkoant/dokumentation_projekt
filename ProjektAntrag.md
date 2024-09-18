### 1. Projektbezeichnung

Entwicklung einer Projektmanagement-App mit Laravel als Backend-Framework und JavaScript als Frontend-Framework.

### 1.1 Kurzbeschreibung des Projekts

Ziel des Projektes ist die Entwicklung einer webbasierten Projektmanagement-App, die es Benutzern ermöglicht, Projekte in Form von Boards zu organisieren, Listen und Aufgaben zu verwalten sowie Benachrichtigungen und Kommentare hinzuzufügen. Das Backend wird in PHP unter Verwendung des Laravel-Frameworks implementiert, während das Frontend eine moderne, dynamische Single-Page-Anwendung (SPA) mit html, css und JavaScript sein wird. Die App soll mit einer RESTful API kommunizieren, die alle notwendigen Funktionen bereitstellt.

### 1.2 Ist-Analyse

Aktuell existiert keine Plattform im Unternehmen, die die Verwaltung von Projekten, Aufgaben und Teams in einem kollaborativen Umfeld ermöglicht. Viele Mitarbeiter verwenden manuelle Methoden wie Tabellenkalkulationen oder einfache To-Do-Listen-Apps, die jedoch nicht die Möglichkeit bieten, Projekte, Aufgaben und Verantwortlichkeiten zentral und transparent zu steuern. Hier fehlen vor allem Funktionen wie die Zuweisung von Aufgaben, das Kommentieren von Fortschritten, die Verwaltung von Dateien oder eine durchsuchbare Aktivitätsübersicht.

Zudem gibt es keine standardisierte Möglichkeit, Aufgaben und Fortschritte in Echtzeit zu verfolgen, was die Teamkommunikation und Produktivität beeinträchtigt.

### 2. Zielsetzung / Soll-Konzept

Das Ziel des Projektes ist die Entwicklung einer vollständigen Projektmanagement-App, die Teams eine nahtlose Zusammenarbeit ermöglicht. Am Ende des Projekts soll eine App bereitstehen, die folgende Funktionen bietet:

- Benutzerverwaltung (Registrierung, Login, Berechtigungen).
- CRUD-Funktionalitäten (Erstellen, Lesen, Bearbeiten, Löschen) für Boards, Listen und Karten.
- Drag-and-Drop-Support für die Umorganisation von Listen und Karten.
- Authentifizierung des Users.
- Benachrichtigungen für Benutzer über Aufgabenänderungen und -zuweisungen.
- Kommentarfunktion für Aufgaben.
- Suchfunktion zum Durchsuchen von Boards, Listen und Karten.


### 2.1 Anforderungen

Folgende Anforderungen müssen im Projekt erfüllt werden:

- **Backend**: Laravel-basierte RESTful API zur Verwaltung von Boards, Listen und Karten mit Authentifizierung.
- **Datenbank**: Modellierung und Implementierung einer relationalen SQL Datenbank zur Speicherung von Benutzern, Aufgaben und Kommentaren.
- **Benutzerfreundlichkeit**: Intuitive Bedienung der Benutzeroberfläche, Drag-and-Drop für Aufgaben sowie Kommentarfunktion.
- **Sicherheit**: Sichere Authentifizierung und Datenverarbeitung.
- **Suchfunktion**: Ermöglicht das schnelle Auffinden von Projekten und Aufgaben.

### 2.2 Einschränkungen

Das Projekt soll in einem begrenzten Zeitrahmen von maximal 80 Stunden abgeschlossen werden. Es wird keine vollständige Echtzeit-Synchronisierung implementiert; Aktualisierungen erfolgen nach Benutzeraktionen. Die App soll zunächst als Webanwendung realisiert werden, ohne spezifische native mobile App-Unterstützung.

### 3. Projektstrukturplan

Das Projekt wird in folgenden Schritten strukturiert:

- **Analysephase**:
  
  - Detaillierte Erfassung der Anforderungen und Ziele.
  - Auswahl der Technologien und Definition der Systemarchitektur.

- **Entwurfsphase**:
  
  - Datenmodellierung, MySQL.
  - API-Design und Festlegung der Schnittstellen.
  - Erstellung von Mockups und Prototypen für das Frontend.

- **Implementierungsphase**:
  
  - Backend-Entwicklung mit Laravel (API, Authentifizierung, Datenbankmodell).
  - Frontend-Entwicklung mit JavaScript, Html, Css (Benutzeroberfläche, Interaktionen, API-Integration).
  - Implementierung von Funktionen wie  Suchfunktion.

- **Testphase**:
  
  - Durchführung von Unit-Tests (API-Endpunkte, Datenbankfunktionen).
  - Usability-Tests der Benutzeroberfläche.

- **Abschluss**:
  
  - Bereitstellung der Dokumentation (Projektbeschreibung, Entwicklerdokumentation).
  - Übergabe und finale Präsentation des Projektes.


### 4. Zeitplan

Das Projekt wird in einem Zeitraum von etwa 80 Stunden durchgeführt. Die voraussichtliche Verteilung der Zeit sieht wie folgt aus:

- Analyse und Planung: 5 Stunden
- Backend-Entwicklung: 40 Stunden
- Frontend-Entwicklung: 25 Stunden
- Testen und Dokumentation: 10 Stunden

