# Reviews
## Peer Reviews

Umfang: Alle Änderungen am Quellcode (Features, Bugfixes, Refactorings) müssen vor dem Merge in den Hauptentwicklungszweig durch mindestens ein weiteres Teammitglied geprüft werden.

## Ziel:

- Erkennen von Fehlern und Inkonsistenzen

- Sicherstellung der Einhaltung von Coding Standards

- Überprüfung auf offensichtliche Performance- oder Sicherheitsprobleme

- Sicherstellung ausreichender Testabdeckung

- Werkzeuge: GitLab Merge Requests mit aktivierten Branch-Schutzregeln.

- Unterstützende Maßnahmen: Alle Änderungen werden vor dem Review automatisiert mit Parasoft statisch analysiert, sodass formale und syntaktische Fehler bereits vorab erkannt werden.

- Aufwand: In der Regel maximal 30 Minuten pro Review.

## Formale Code-Inspektionen

Für besonders kritische Teile der Softwarearchitektur werden zusätzlich formale Inspektionen durchgeführt.

### Anwendungsfälle:

- sicherheitsrelevante Module

- Komponenten mit hoher Komplexität oder zentraler Bedeutung (z. B. Transaktionslogik, Schnittstellenbibliotheken)

- Codebereiche mit erhöhter Fehlerrate in der Vergangenheit

- größere Refactorings oder architekturrelevante Änderungen

### Vorgehen:

Vorbereitung: Der Autor stellt den Code und relevante Dokumentation den Inspektoren vorab zur Verfügung.

Checklisten-basierte Prüfung: Die Reviewer prüfen den Code anhand vorgegebener Kriterien (z. B. Korrektheit, Fehlerbehandlung, Wartbarkeit, Konformität mit Normen).

Inspektionssitzung: Moderierter Review-Termin mit allen beteiligten Prüfern; die identifizierten Probleme werden dokumentiert.

Nachbereitung: Der Autor behebt die festgestellten Mängel; der Moderator überprüft die Korrekturen.

Aufwand: In der Regel 1–2 Stunden pro Inspektion.

Frequenz: Bedarfsabhängig, mindestens jedoch einmal pro Entwicklungszyklus für besonders kritische Module.

## Automatisierte Prüfungen

Zur Ergänzung der Peer Reviews und Inspektionen sind folgende automatisierte Prüfungen verpflichtender Bestandteil des Entwicklungsprozesses:

- Statische Code-Analyse mit Parasoft

- Linter-Regeln

- Automatisierte Unit- und Integrationstests

Dadurch können Peer Reviews und Inspektionen sich auf inhaltliche, architektonische und domänenspezifische Fragestellungen konzentrieren.