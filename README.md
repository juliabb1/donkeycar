# donkeycar

Git Commands

### Verbinden mit remote repository ()

git init
git remote add origin https://github.com/juliabb1/donkeycar.git


### Most Essential 

# Daten aus GitHub ziehen
git pull

# Daten auf Github pushen
git add .  # "." für alles adden, ansonsten Pfad zu der Datei, die hinzugefügt werden soll
git commit -m "message here (was wurde geändert?)"
git push -u origin main


# Starten der Simulationsumgebung (conda environment donkey ist aktiviert)
cd mysim
python manage.py drive
http://localhost:8887 # Steuerung