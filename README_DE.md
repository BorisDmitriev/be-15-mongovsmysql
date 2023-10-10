# Übungsaufgabe: Datenbankkonzepte verstehen

## Einführung
Diese Übungsaufgabe konzentriert sich auf grundlegende Konzepte von Datenbanken, insbesondere auf Tabelle / Collection, Zeile / Dokument, Spalte / Feld und Schlüssel / ID. Sie werden praktische Beispiele sowohl für MongoDB als auch für SQL kennenlernen und diese Konzepte anwenden.

## Aufgaben

### Aufgabe 1: Erstellen einer Sammlung in MongoDB
Erstellen Sie eine Sammlung in MongoDB mit dem Befehl `db.createCollection()`. Überprüfen Sie, ob die Sammlung erfolgreich erstellt wurde, indem Sie den Befehl `show collections` verwenden.

### Aufgabe 2: Erstellen einer Tabelle in SQL
Erstellen Sie eine Tabelle in SQL mit dem Befehl `CREATE TABLE <tabellenname> (<spaltendefinitionen>)`. Verwenden Sie geeignete Spaltendefinitionen für Ihre Tabelle. Überprüfen Sie, ob die Tabelle erfolgreich erstellt wurde, indem Sie den Befehl `SHOW TABLES` verwenden.

### Aufgabe 3: Unterschiede zwischen Tabelle und Sammlung
Beschreiben Sie kurz den Unterschied zwischen einer Tabelle und einer Sammlung in Bezug auf ihre Struktur und Verwendung. Geben Sie die Antwort als Markdown-Kommentar in Ihrer README_DE.md-Datei an.

### Aufgabe 4: Einfügen eines Dokuments in MongoDB
Fügen Sie ein Dokument in die zuvor erstellte Sammlung in MongoDB ein. Verwenden Sie den Befehl `db.<sammlung>.insertOne(<dokument>)`. Das Dokument sollte relevante Felder enthalten, die der Struktur Ihrer Sammlung entsprechen.

### Aufgabe 5: Einfügen einer Zeile in SQL
Fügen Sie eine Zeile in die zuvor erstellte Tabelle in SQL ein. Verwenden Sie den Befehl `INSERT INTO <tabellenname> VALUES (<werte>)`. Geben Sie die entsprechenden Werte für Ihre Tabelle ein.

### Aufgabe 6: Unterschiede zwischen Zeile und Dokument
Beschreiben Sie kurz den Unterschied zwischen einer Zeile und einem Dokument in Bezug auf ihre Verwendung und Erstellung. Geben Sie die Antwort als Markdown-Kommentar in Ihrer README_DE.md-Datei an.

### Aufgabe 7: Anzeigen aller Dokumente in MongoDB
Rufen Sie alle Dokumente aus der erstellten Sammlung in MongoDB ab. Verwenden Sie den Befehl `db.<sammlung>.find({})`. Überprüfen Sie, ob die abgerufenen Dokumente den erwarteten Inhalt enthalten.

### Aufgabe 8: Anzeigen aller Zeilen in SQL
Rufen Sie alle Zeilen aus der erstellten Tabelle in SQL ab. Verwenden Sie den Befehl `SELECT * from <tabellenname>`. Überprüfen Sie, ob die abgerufenen Zeilen den erwarteten Inhalt enthalten.

### Aufgabe 9: Unterschiede zwischen Spalte und Feld
Beschreiben Sie kurz den Unterschied zwischen einer Spalte und einem Feld in Bezug auf ihre Verwendung und Darstellung. Geben Sie die Antwort als Markdown-Kommentar in Ihrer README_DE.md-Datei an.

### Aufgabe 10: Hinzufügen von IDs zu SQL-Tabelle
Fügen Sie eine einde

utige ID-Spalte zu Ihrer SQL-Tabelle hinzu. Verwenden Sie den Befehl `CREATE TABLE <tabellenname> (id NOT NULL AUTO_INCREMENT, <spaltendefinitionen>, PRIMARY_KEY(id))`. Stellen Sie sicher, dass die ID automatisch inkrementiert wird und als Primärschlüssel festgelegt ist.

## Hinweise

- Für weitere Informationen zu den Befehlen und Konzepten können Sie die entsprechende Dokumentation konsultieren:
  - [MongoDB Dokumentation](https://docs.mongodb.com/)
  - [SQL Dokumentation](https://www.w3schools.com/sql/)

- Machen Sie Screenshots der erwarteten Ergebnisse für die Beispiele und fügen Sie sie in den Abschnitt "Example" Ihrer README_DE.md-Datei ein.

Viel Erfolg bei der Bearbeitung der Übungsaufgabe!
