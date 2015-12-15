Simulation Dynamischer Systeme
=======
Beispiel Projekt um mit Python Simulation von Dynamischen Systemen zu betreiben.

## Ubuntu Packete
Folgende Ubuntu Packete werden benötigt um das arbeiten mit Python zu vereinfachen und um SciPy und Matplotlib zu bauen:
```
sudo apt-get install python3-pip virtualenv
sudo pip install --upgrade pip
#needed for scipy to be installed 
sudo apt-get install build-essential gfortran libatlas-base-dev libatlas3gf-base python-dev libjpeg-dev libxml2-dev libfreetype6-dev 
#needed for matplotlib to plot something
sudo apt-get install tcl-dev tk-dev python-tk python3-tk
```

## Projekt benutzen
Aktiveren vom virtualenv:

```
cd my_project_folder
source env/bin/activate
```

Installieren der benötigten Python Pakete:

```
pip install -r requirements.txt
```

## Python Notebook
Das Python Notebook kann gestartet werden mit:

```
ipython notebook
```



