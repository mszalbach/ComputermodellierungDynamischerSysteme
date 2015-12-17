Simulation Dynamischer Systeme
=======
Beispiel Projekt um mit Python Simulation von Dynamischen Systemen zu betreiben.

## Setup

### Ubuntu Packete
Folgende Ubuntu Packete werden benötigt um das arbeiten mit Python zu vereinfachen und um SciPy und Matplotlib zu bauen:
```bash
sudo apt-get install python3-pip python-virtualenv
#needed for scipy to be installed 
sudo apt-get install build-essential gfortran libatlas-base-dev libatlas3gf-base python-dev libjpeg-dev libxml2-dev libfreetype6-dev 
#needed for matplotlib to plot something
sudo apt-get install tcl-dev tk-dev python-tk python3-tk
```

### Python Packete instalieren
Aktiveren vom virtualenv:

```bash
cd my_project_folder
virtualenv -p python3 env
source env/bin/activate
sudo pip install --upgrade pip
pip install -r requirements.txt
```

## Arbeiten mit dem Projekt

### Python Environment 

```bash
cd my_project_folder
source env/bin/activate
```

### Python Notebook
Das Python Notebook kann gestartet werden mit:

```bash
ipython notebook
```

### Neue Bibliothek instalieren
Zuerst sicherstellen, dass das Python Environment geladen ist, dann via pip nachinstalieren und Abhängigkeiten sichern:

```bash
pip install IRGENDWAS
pip freeze > requirements.txt
```



