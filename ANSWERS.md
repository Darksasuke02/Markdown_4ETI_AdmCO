# Réponses AdmCO


## Questions Préparatoires

1. (Connaissances + ChatGPT)
Ce code demande à l'utisateur de rentrer deux variables et les stockent dans x et y, ensuite la fonction add est appelée elle renvoie la somme x+y (Il y a un print pour vérifier le lancement),
 le résulat est affiché grâce à un print (Il y a un print pour vérifier l'exécution). addition.py fonctionne uniquement si il est lancé directement

1. (Openclassrooms)
Le fichier requirements.txt permet de renseigner les différents paquets Python nécessaire au bon lancement de l'application

2. (ChatGPT + Internet)
Un module python est un fichier python pouvant contenir des fonctions, classes, variables. 
Il peux être importé facilement avec un 
```console
import nom_du_module  #(dans le meme répertoire courant)
``` 
peux nécessité un 
```console
import sys
sys.path.append('chemin')
```
 avant si il n'est pas dans le répertoire courant
 
3. (ChatGPT + Internet)
Un package fait partie d'une un structure utilisé pour organiser et structurer le code, un dossier doit contenir un fichier "__init__.py" pour est défini comme package (sous python),
il peux contenir soit des modules Python (.py) ou des sous-packages


5. (ChatGPT + Internet) 
L'utilisation de pip est en lien avec le fichier requirements.txt, c'est un gestionnaire de packets python, en effet il permet d'installer et-ou mettre à jour des packages Python 
```bash
pip install nom_du_package
```
Il facilite donc la gestion des dépendances du projet (rédigé dans requirements.txt).

6. (ChatGPT)
 PYTHONPATH sert à gérer les dépendances Python dans les projets. C'est le chemin de recherche des modules : Lorsque vous importez un module ou un package Python dans un script,
Python recherche dans certains répertoires prédéfinis pour trouver ce module. PYTHONPATH est la liste de répertoires que Python parcourt lorsqu'il recherche les modules à importer.

7. (ChatGPT + Internet)
Par défaut les paquets installé par pip se retrouve dans un dossier du nom de site-packages, le chemin exact dépends de l'accessibilité des packets (utilisateur/système/environnements virtuels)

Par défaut les chemins linux sont (X et Y pour la version de Python) :
```console
usr/lib/pythonX.Y/site-packages   (pour l'installation système)
~/.local/lib/pythonX.Y/site-packages   (pour l'installation utilisateur)
<environnement>/lib/pythonX.Y/site-packages   (pour les environnements virtuels)
```
8. (ChatGPT)
Ce paramètre d'installation est utilisé pour faire une installation des package pour l'utilisateur courant

9. (ChatGPT)
venv est un module Python qui permet la création d'environnements virtuels isolés pour les différents projets, de cette manière il est possible de travailler sur des projets aux dépendances différentes en évitant les inteférance. Il est même possible d'utiliser des versions différentes de Python


10. (ChatGPT)
Pour l'utiliser : 
```bash
python -m venv nom_de_lenvironnement #pour créer l'environnement
source mon_env/bin/activate #pour activer l'environnement
pip install nom_du_package #une fois l'environnement activé les installation se font dans l'env
deactivate #desactiver l'environnement virtuel
```
11. (ChatGPT)
Docker permet de dévelloper, déployer et gérer des applications dans des conteneur logiciel.
Un conteneur logiciel est une encapsulation des projets et de leur environnement d'exécution afin de les isoler des autres application et du système d'exploitation (on isole les variables d'environnement, code ,etc...).

12. (ChatGPT)
Pour l'utiliser :
```bash 
sudo apt install docker.io #installation de docker
sudo systemct1 start docker #démarrage du service Docker
docker --version  #vérif de l'installation
```
commande de base après installation : 
```bash
docker pull nom_de_l_image # Télécharger une image depuis le Docker Hub.
docker run nom_de_l_image #Exécuter un conteneur à partir d'une image.
docker ps # Afficher les conteneurs en cours d'exécution.
docker images # Afficher les images Docker disponibles sur votre système.
docker stop ID_du_conteneur # Arrêter un conteneur en cours d'exécution.
```

## Exercices

#### Exercice 0
https://gitlab.com/kevin5450406/admco_20232024ex0.git
#### Exercice 1
https://gitlab.com/kevin5450406/admco_20232024ex1.git
#### Exercice 2
https://gitlab.com/kevin5450406/admco_20232024ex2.git
#### Exercice 3
https://gitlab.com/kevin5450406/admco_20232024ex3.git
#### Exercice 4
https://gitlab.com/kevin5450406/admco_20232024ex4.git
#### Exercice 5
https://gitlab.com/kevin5450406/adm-co-20232024-ex-5.git
#### Exercice 6
https://gitlab.com/kevin5450406/admco20232024ex6.git
#### Exercice 7
https://gitlab.com/kevin5450406/admco20232024ex7.git
#### Exercice 8
https://gitlab.com/kevin5450406/admco20232024ex8.git
#### Exercice 9
https://gitlab.com/kevin5450406/admco20232024ex9.git
#### Exercice 10
https://gitlab.com/kevin5450406/admco20232024ex10.git
#### Exercice 11
https://gitlab.com/kevin5450406/admco20232024ex11.git
#### Exercice 12
https://gitlab.com/kevin5450406/admco20232024ex12.git
