# Projet2 
Bonjour
Avant tout d'accord, je tiens à vous informer que  je travail sur windows10.
Pour mettre en place l'environnement python sur windows10:
IL faut d'accord installer python3 ou 2
Ensuite installer le editeur pycharm community edition 2020.3.1 parce que sans installer python le code ne sera pas exécutatble.
En installant python il faut toujours coher PATH sinon les packages ne seront pas installés tel que pip et python.
Pour verifier si le packages sont vraiment installer je vous invite à se positionner le repertoire suivant:
C :>Windows/Systeme32  python --version
C :>Windows/Systeme32  pip --version
Il vous affichera les packages et leurs versions
Apartir de là l'environnement est pret de recevoire notre projet ou le code python.
Alors pour notre projet on va installer les packages suivant dans la console(clavier:windows+R) avec la commande cmd:
C :>Windows/Systeme32 pip installe requests    #Ainsi il va installer certaines comme indépendants pour verifier on tape la commande suivant:
C :>Windows/Systeme32 pip freez
certifi==2020.4.5.1
chardet==3.0.4
idna==2.9
requests==2.25.1
urllib3==1.26.2

Ensuite on tape la commande suivant:
C :>Windows/Systeme32 pip installe bs4
C :>Windows/Systeme32 pip installe Beutifoulsoup4

Ensuite on se place dans notre editeur pycharm pour installer de dans  nos packages:
On clique sur File -> Settings -> Python interpreter -> ongle(+) et on saisie nos packages dans la bande de recherche et ensuite on clique sur install package

Ensuite on cree notre fichier code main.py et on import nos packages et on saisie notre code python. 

Alors pour mettre en place environnement virtuel et exécuter notre code python :

Dans notre dossier environnement appelé testProjet:
testProjet ls:
main.py
Books
Fichiers
Categories
LesImages
testProjet touch requirements.txt
testProjet/cat requirements.txt :
requests ==2.25.1  
beautifulsoup4==4.9.3
bs4==0.0.1

Maintenant on va exécuter notre code dans l'environnement virtuel:
testProjet   mkdir projetV     # On cree notre dossier environnement virtuel

testProjet/projetV    python -m venv envV      # On cree notre environnement virtuel

testProjet/projetV    source envV/bin/activate  # On active notre environnement virtuel

(envV)~c:../../testProjet cp main.py /projetV      # On copie notre fichier code main.py dans le dossier environnement virtuel

(envV)~c:../../testProjet/projetV ls
main.py  envV

Ensuite on va installer automatique les packages dans le fichier requirements.txt de testProjet vers ProjetV
(envV)~c:../../testProjet/projetV pip install -r requirements.txt

En fin notre environnement virtuel est pret d'exécuter notre code main.py

















