# Änderung 1: Erstellen einer Konfigurationsdatei
echo "[settings]\nversion=1.0" > config.ini
git add config.ini
git commit -m "Erstellen der Konfigurationsdatei config.ini"

# Änderung 2: Hinzufügen von Daten in eine CSV-Datei
echo "Name,Alter,Ort\nAlice,30,Berlin" > daten.csv
git add daten.csv
git commit -m "Hinzufügen einer CSV-Datei mit Beispieldaten"

# Änderung 3: Anpassen der README-Datei
echo "# Projekt-README\nDieses Projekt demonstriert Git-Kommandos." > README.md
git add README.md
git commit -m "Erstellen und Befüllen der README-Datei"

# Git History anzeigen
git log --oneline