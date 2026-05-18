# Projektplanung – Der Weg vom Start bis zum Ziel

## 1. Was ist die Projektplanung?

Die **Projektplanung** ist die zweite Phase im Projektmanagement  
(nach der **Projektinitialisierung**).

Ziel ist es, den **Projektablauf detailliert zu strukturieren**, bevor die eigentliche Durchführung beginnt.

> **Frage der Projektplanung:**  
> *„WIE erreichen wir die Projektziele?“*

---

## 2. Wichtige Werkzeuge und Methoden

| Methode / Werkzeug | Kurz erklärt |
|-------------------|---------------|
| **SMART** | Formulierung von **klaren, überprüfbaren Zielen** |
| **Gantt-Diagramm** | **Zeitliche Darstellung** von Aufgaben und Meilensteinen |
| **Netzplan** | Darstellung von **Abhängigkeiten** zwischen Aufgaben |
| **PSP (Projektstrukturplan)** | Zerlegung des Projekts in **Teilaufgaben** |
| **Ressourcenplanung** | Wer macht was, mit welchem Budget? |
| **Meilensteine** | Wichtige Zwischenziele mit Terminbindung |

---

## 3. SMART – Ziele richtig formulieren

SMART ist ein **Akronym** für die Merkmale **guter Projektziele**.

| Buchstabe | Bedeutung | Fragestellung |
|-----------|-----------|----------------|
| **S** | **Specific** (spezifisch, konkret) | Was genau soll erreicht werden? |
| **M** | **Measurable** (messbar) | Woran erkennt man die Zielerreichung? |
| **A** | **Achievable** (erreichbar) | Ist das Ziel realistisch? |
| **R** | **Relevant** (relevant) | Trägt das Ziel zum Gesamterfolg bei? |
| **T** | **Time-bound** (terminiert) | Bis wann wird das Ziel erreicht? |

### Beispiel für ein SMART-Ziel

> **Nicht SMART:**  
> *„Die Software soll besser werden.“*

> **SMART:**  
> *„Die Antwortzeit der Anwendung wird bis zum 31.12. von 5 Sekunden auf unter 2 Sekunden reduziert.“*

---

## 4. Gantt-Diagramm – Zeitliche Übersicht

Ein **Gantt-Diagramm** zeigt Aufgaben, Dauer und Meilensteine **auf einer Zeitachse**.

### Beispiel (textuell)

```text
Aufgabe               | Start      | Ende       | Dauer
----------------------|------------|------------|-------
Projekt initialisieren| 01.03.     | 05.03.     | 5 Tage
Anforderungen erfassen| 06.03.     | 15.03.     | 10 Tage
Design erarbeiten     | 16.03.     | 25.03.     | 10 Tage
Implementierung       | 26.03.     | 15.04.     | 21 Tage
Testen                | 16.04.     | 25.04.     | 10 Tage
Abnahme               | 26.04.     | 28.04.     | 3 Tage
```

### Typische Symbole

| Symbol | Bedeutung |
|--------|-----------|
| ██████ | Dauer einer Aufgabe |
| ◆      | Meilenstein (Zwischenziel) |
| ⬆      | Anfangstermin |
| ⬇      | Endtermin |

### Vorteile von Gantt

- ✅ Einfach zu verstehen
- ✅ Zeigt Überlappungen / parallele Aufgaben
- ✅ Gut für Kommunikation mit Auftraggeber

---

## 5. Netzplan – Abhängigkeiten darstellen

Ein **Netzplan** zeigt, **welche Aufgaben vor anderen erledigt sein müssen**.

### Beispiel

```text
A (5) → B (3) → D (2)
  ↘         ↗
    → C (4) → E (1)
```

- A → B → D
- A → C → E
- B und E parallel möglich (nach C)

### Wichtige Begriffe im Netzplan

| Begriff | Bedeutung |
|---------|-----------|
| **Vorgänger** | Aufgabe, die abgeschlossen sein muss |
| **Nachfolger** | Aufgabe, die erst nach Vorgänger starten kann |
| **Kritischer Pfad** | Längster Weg durch den Netzplan – bestimmt die Gesamtdauer |
| **Puffer** | Zeit, um eine Aufgabe zu verschieben, ohne Gesamtdauer zu gefährden |

### Vorteile von Netzplänen

- ✅ Zeigt Abhängigkeiten klar
- ✅ Berechnet **früheste / späteste Termine**
- ✅ Identifiziert **kritischen Pfad**

---

## 6. Vergleich: Gantt vs. Netzplan

| Kriterium | Gantt-Diagramm | Netzplan |
|-----------|----------------|----------|
| **Abhängigkeiten** | nicht im Fokus | ✅ zentral |
| **Lesbarkeit für Laien** | ✅ sehr gut | mittel |
| **Kritischer Pfad** | nicht direkt sichtbar | ✅ direkt berechenbar |
| **Parallelität** | sichtbar | berechenbar |
| **Typische Nutzung** | Kommunikation, Reporting | Detailplanung, Terminberechnung |

> **Merke:**  
> Gantt für den Auftraggeber – Netzplan für den Projektleiter.

---

## 7. Weitere wichtige Begriffe der Projektplanung

| Begriff | Bedeutung |
|---------|-----------|
| **Projektstrukturplan (PSP)** | Hierarchische Zerlegung des Projekts in Arbeitspakete |
| **Ressourcenplanung** | Welche Personen, Geräte, Budgets werden benötigt? |
| **Kostenplanung** | Budgetierung, Kostenarten, Zahlungsströme |
| **Meilensteinplan** | Liste der wichtigsten Termine und Zwischenziele |
| **Qualitätsplanung** | Definition von Qualitätszielen und Prüfmethoden |
| **Risikoplanung** | Erkennung, Bewertung und Maßnahmen von Risiken |

---

## 8. Typische IHK-Prüfungsfragen

**Frage 1:**  
*Wofür steht SMART?*

**Antwort:**  
Specific, Measurable, Achievable, Relevant, Time-bound (spezifisch, messbar, erreichbar, relevant, terminiert).

---

**Frage 2:**  
*Welchen Unterschied gibt es zwischen Gantt-Diagramm und Netzplan?*

**Antwort:**  
Gantt zeigt **Aufgaben auf einer Zeitachse** (gut für Kommunikation).  
Netzplan zeigt **Abhängigkeiten zwischen Aufgaben** und berechnet den **kritischen Pfad**.

---

**Frage 3:**  
*Was ist der kritische Pfad im Netzplan?*

**Antwort:**  
Der längste Weg durch den Netzplan – er bestimmt die **Mindestgesamtdauer** des Projekts.  
Aufgaben auf dem kritischen Pfad haben **keinen Puffer**.

---

**Frage 4:**  
*In welcher Projektphase findet die detaillierte Projektplanung statt?*

**Antwort:**  
Nach der **Projektinitialisierung**, vor der **Durchführung**.

---

## 9. Merksätze für die Prüfung

> **„SMART stellt sicher, dass Ziele klar und überprüfbar sind.“**

> **„Gantt zeigt was und wann – Netzplan zeigt was wovon abhängt.“**

> **„Der kritische Pfad ist der längste Weg – er bestimmt die Projektdauer.“**

> **„Ohne Planung läuft das Projekt ins Chaos.“**

---

## 10. Zusammenfassung als Checkliste

| Schritt | Erledigt? |
|---------|-----------|
| Ziele SMART formuliert | ☐ |
| Projektstrukturplan (PSP) erstellt | ☐ |
| Gantt-Diagramm erstellt | ☐ |
| Netzplan mit Abhängigkeiten erstellt | ☐ |
| Kritischer Pfad berechnet | ☐ |
| Ressourcen und Kosten geplant | ☐ |
| Meilensteine definiert | ☐ |
| Risikoanalyse durchgeführt | ☐ |