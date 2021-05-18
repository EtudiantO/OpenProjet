# Projet2 

Aprés d'avoir mettre en place mon environnement de développement en python.

Alors pour mettre en place environnement virtuel et exécuter mon code python :

# J'ai fait la lecture de mon dossier environnement appelé testProjet:
testProjet ls:
main.py
Books
Fichiers
Categories
LesImages
# J'ai cree un fichier requirements.txt pour mettre tous mes packages
testProjet touch requirements.txt
testProjet/cat requirements.txt :
requests ==2.25.1  
beautifulsoup4==4.9.3
bs4==0.0.1

# Pour proceder l'exécution de mon  code dans l'environnement virtuel:
# Je vais d'accord creer mon dossier environnemment virtuel
testProjet   mkdir projetV     
# Ensuite j'ai creer mon en environnement virtuel
testProjet/projetV    python -m venv envV      
# J'active
testProjet/projetV    source envV/bin/activate  
# Je copie mon fichier code main.py dans le dossier environnement virtuel
(envV)~c:../../testProjet cp main.py /projetV      

(envV)~c:../../testProjet/projetV ls
main.py  envV

# Ensuite J'installe automatique les packages dans le fichier requirements.txt de testProjet vers ProjetV
(envV)~c:../../testProjet/projetV pip install -r requirements.txt

# En fin mon environnement virtuel est pret d'exécuter mon code python ( main.py)

















