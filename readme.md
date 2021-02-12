# Übersicht

`id_name_und_beschreibung_aller_parteien.csv` Enthält den Parteien zugeordneten Nummern (ids), die als key benötigt werden um die Daten zusammen zu führen. Enthält außerdem die Parteinamen in Kurz- und Langform sowie eine Kurzbeschreibung der Parteien.

`thesenkatalog.csv` Enthält eine Liste aller Fragen/Thesen, zu denen die Parteien Stellung beziehen. Mit der parteien_positionen-Spalte lassen sich die Fragen zuordnen. Den Fragen/Thesen wird zusätzlich ein Thema beigefügt.

`positionen_der_parteien_in_ziffern.csv`Enthält die Positionen aller Parteien zu den Thesen/Fragen als Ziffern (-1, 0, 1): -1 steht für "Ablehnung", 0 für "Neutral" und 1 für "Zustimmung". Über die thesen_id-Spalte lassen sich die Positionen der Fragen zuordnen.

`standpunkte_der_parteien_in_textform.csv`Alle Standpunkte der Partein in ausführlicher Textform. Über thesen_id und parteien_id lassen sich die Antworten den Parteien sowie dem Thesenkatalog zuordnen.
