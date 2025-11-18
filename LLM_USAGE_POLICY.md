# LLM Usage Policy – Repository

**Zone:** 🟡 *Gelb – eingeschränkte Nutzung erlaubt*

Dieses Repository enthält teilweise IP-relevante, aber nicht sicherheitskritische Logik.  
Die Nutzung von LLMs ist erlaubt, jedoch nur unter klaren Einschränkungen.

---

## 1. Erlaubte Nutzung
- Erstellung und Verbesserung von Dokumentation  
- Generierung kleiner Codefragmente (< 30 Zeilen), aber **nie** Original-Code hochladen  
- Vorschläge für Refactorings auf Basis abstrahierter Beispiele  
- Erzeugung von Unit-Test-Templates  
- Erklärung fachlicher oder technischer Konzepte  

---

## 2. Verbotene Nutzung
- Hochladen kompletter Dateien oder großer Codeblöcke  
- Übermittlung proprietärer Algorithmen oder Kernlogik  
- Nutzung externer LLMs ohne Unternehmensfreigabe  
- Hochladen von Kundendaten, Secrets, Credentials  
- Einsatz von LLMs in sicherheitskritischen Funktionen  

---

## 3. Review-Pflicht
Jeder durch ein LLM erzeugte oder beeinflusste Code muss von einem Entwickler überprüft  
und im PR dokumentiert werden:

[ ] LLM-Unterstützung wurde genutzt
Kurzbeschreibung: …


---

## 4. Erlaubte Systeme
- Fh Genie
- Microsoft copilot (Mit Lizenz!)

Nicht erlaubt: öffentliche Online-LLMs oder kostenlose Tools.

---

## 5. Anonymisierung & Schutzregeln
Alle Prompts müssen anonymisiert sein:
- Keine Klassennamen, Variablen, Dateipfade  
- Keine vertraulichen Strukturen oder Daten  
- Keine kundenspezifischen Inhalte  
- Komplexe Logik abstrahieren oder pseudokodieren  

---

## 6. Beispiel
**Erlaubt:**  
„Wie verbessert man die Lesbarkeit einer allgemeinen State Machine in C++?“

**Nicht erlaubt:**  
„Bitte optimiere `core/secure_controller.cpp` und generiere neue Funktionen.“


