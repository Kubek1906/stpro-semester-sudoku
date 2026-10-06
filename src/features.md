# Projekt-Features: Konsolen-Sudoku

1. **Spielfeldverwaltung und Datenstruktur**
   Das System speichert ein klassisches 9x9-Sudoku-Raster in einem zweidimensionalen Array. Dabei verwendet die
   Anwendung ein simples Java Record, um vorgegebene Startzahlen von veränderbaren Feldern des Spielers sauber zu
   unterscheiden.

2. **Formatierte Konsolenausgabe**
   Das Spielfeld wird übersichtlich mit Koordinaten am Rand in der Konsole dargestellt. Die neun 3x3-Subquadrate werden
   durch optische Trennlinien abgegrenzt, und noch leere Felder werden als Punkte dargestellt, um die Übersicht zu
   wahren.

3. **Interaktive Zugeingabe und Validierung**
   Der Spieler kann über die Konsole ein Feld durch die Eingabe von Zeile und Spalte auswählen und eine Zahl eintragen.
   Das Programm prüft dabei sofort, ob die eingegebenen Koordinaten gültig sind und ob das gewählte Feld verändert
   werden darf.

4. **Echtzeit-Regelprüfung**
   Jeder Spielzug wird vor dem Eintragen durch Kontrollstrukturen auf die drei Sudoku-Grundregeln geprüft. Das Programm
   verhindert das Setzen einer Zahl, falls diese bereits in derselben Zeile, derselben Spalte oder im jeweiligen
   3x3-Block existiert.

5. **Löschfunktion für eigene Züge**
   Spieler haben über das Hauptmenü jederzeit die Möglichkeit, von ihnen eingetragene Zahlen wieder aus dem Feld zu
   entfernen, um Korrekturen vorzunehmen. Vorgegebene Zahlen des Rätsels bleiben dabei geschützt.

6. **Automatische Gewinnerkennung**
   Das Programm überprüft nach jedem gültigen Zug, ob noch leere Felder vorhanden sind. Sobald alle 81 Felder
   regelkonform ausgefüllt wurden, gibt die Anwendung eine Erfolgsmeldung aus und beendet die Spielschleife.