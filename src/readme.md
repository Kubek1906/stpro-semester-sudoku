Author:
Jakob Malicki

1. Das Spielfeld (Gitteransicht)
   In der Mitte des Bildschirms siehst du ein sauber ausgerichtetes 9x9-Raster, das aus normalen Zeichen aufgebaut ist:

Koordinaten: Am oberen Rand stehen die Spaltennummern von 1 bis 9 und am linken Rand die Zeilennummern von 1 bis 9.
Dadurch siehst du sofort, welches Feld welche Koordinaten hat.

3x3-Blöcke: Das große Spielfeld ist durch Trennlinien aus Pluszeichen, Bindestrichen und senkrechten Strichen (+-------+
und |) in die neun typischen 3x3-Quadrate unterteilt.

Zahlen und Punkte: Fest vorgegebene Startzahlen sowie deine eingetragenen Werte stehen als Ziffern 1 bis 9 im Raster.
Alle noch leeren Felder werden übersichtlich als Punkte (.) dargestellt.

2. Das Interaktions-Menü Direkt unter dem Spielfeld erscheint nach jeder Aktualisierung ein einfaches Textmenü. Dort
   wirst du aufgefordert, eine Zahl von 1 bis 3 einzugeben:

Zug machen: Du wirst nacheinander nach der Zeile, der Spalte und der Zahl gefragt, die du eintragen möchtest.

Feld leeren: Du gibst die Koordinaten an, um eine eigene Zahl wieder zu löschen.

Beenden: Das Spiel wird beendet.

3. Rückmeldungen und Feedback Nach jeder Eingabe druckt das Programm das Spielfeld neu aus und gibt dir direkt darunter
   kurze Rückmeldungen in Textform:

Wenn deine Zahl den Sudoku-Regeln entspricht, erscheint: Zug erfolgreich gesetzt!.

Wenn die Zahl bereits in der gleichen Zeile, Spalte oder im 3x3-Block vorkommt, erhältst du eine deutliche Warnung:
Regelverstoß: Zahl existiert bereits in Zeile, Spalte oder 3x3-Block!.

Versuchst du eine vorgegebene Startzahl zu ändern, weist dich das Programm mit Fehler: Dieses Feld ist fest vorgegeben!
darauf hin.

Sobald das letzte freie Feld korrekt ausgefüllt ist, zeigt die Konsole eine große Glückwunschmeldung zum Sieg an.