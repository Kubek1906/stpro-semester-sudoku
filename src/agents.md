# Spielanleitung & Grundlegende Instruktionen: Konsolen-Sudoku

Diese Anleitung erklärt die Regeln, die Steuerung und die Bedienung der Konsolen-Sudoku-Anwendung.

---

## 1. Spielziel

Ziel von Sudoku ist es, ein $9 \times 9$-Gitter so mit den Ziffern $1$ bis $9$ zu füllen, dass jedes Feld eine Zahl enthält und alle drei Grundregeln eingehalten werden.

---

## 2. Die drei Grundregeln

Beim Eintragen einer Zahl prüft das Programm automatisch folgende Regeln in Echtzeit:

1. **Zeilen-Regel:** Jede Ziffer von $1$ bis $9$ darf in jeder waagerechten Zeile nur **ein einziges Mal** vorkommen.
2. **Spalten-Regel:** Jede Ziffer von $1$ bis $9$ darf in jeder senkrechten Spalte nur **ein einziges Mal** vorkommen.
3. **3x3-Block-Regel:** Das $9 \times 9$-Spielfeld ist in neun $3 \times 3$-Quadrate unterteilt. In jedem dieser Blöcke darf jede Ziffer von $1$ bis $9$ nur **ein einziges Mal** enthalten sein.

---

## 3. Steuerung & Menüführung

Die Steuerung erfolgt vollständig über Tastatureingaben im Terminal oder in der Konsole.

### Das Hauptmenü
Nach jeder Aktualisierung des Spielfelds stehen folgende Optionen zur Auswahl:

* **`1` – Zahl eintragen:**
  Setzt eine Zahl auf ein gewähltes Feld.
* **`2` – Feld leeren:**
  Löscht eine selbst eingetragene Zahl wieder vom Spielfeld.
* **`3` – Spiel beenden:**
  Beendet die Anwendung vorzeitig.

---

## 4. Eingabeformat & Koordinaten

* **Zeilen:** Werden von oben nach unten von **`1` bis `9`** gezählt.
* **Spalten:** Werden von links nach rechts von **`1` bis `9`** gezählt.
* **Werte:** Gültige Ziffern sind die Zahlen **`1` bis `9`**.

### Ablauf eines Spielzugs:
1. Wähle im Menü die Option `1`.
2. Eingabe `Zeile (1-9)`: z. B. `3`
3. Eingabe `Spalte (1-9)`: z. B. `4`
4. Eingabe `Zahl (1-9)`: z. B. `7`

Das Feld in Zeile 3, Spalte 4 wird nun auf den Wert `7` gesetzt, sofern kein Regelverstoß vorliegt.

---

## 5. Wichtige Symbole & Hinweise

* **Punkte (`.`):** Stellen leere Felder dar, in die eine Zahl eingetragen werden kann.
* **Vorgegebene Felder:** Zahlen, die zu Beginn bereits im Rätsel enthalten sind, sind fest geschützt und können weder überschrieben noch gelöscht werden.
* **Fehlermeldungen:** Falls eine Zahl gegen die Sudoku-Regeln verstößt oder fehlerhafte Koordinaten eingegeben werden, zeigt die Konsole einen entsprechenden Hinweis an.
* **Siegbedingung:** Das Spiel erkennt automatisch, wenn alle 81 Felder vollständig und korrekt ausgefüllt wurden, und schließt die Runde mit einer Erfolgsmeldung ab.