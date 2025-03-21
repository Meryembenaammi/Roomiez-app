# Roomiez - Plateforme de Colocation avec Reconnaissance Faciale

Roomiez est une application innovante facilitant la colocation entre jeunes filles étudiantes. Elle intègre un **système de gestion de présence basé sur la reconnaissance faciale**, garantissant sécurité et transparence dans les espaces partagés.

## Fonctionnalités Principales
- **Reconnaissance faciale** pour l'accès sécurisé aux espaces communs.
- **Gestion des présences** des colocataires.
- **Génération de rapports** sur les entrées et sorties.
- **Interface web interactive** basée sur Flask.
- **Stockage des données** avec des bases SQLite.


## Installation et Utilisation
### Prérequis
- Python 3.11
- Flask
- OpenCV
- SQLite


### Installation
1. Clonez le projet :

2. Installez les dépendances :
   ```sh
   pip install -r requirements.txt
   ```
3. Exécutez l'application :
   ```sh
   python app2.py
   ```
4. Accédez à l'interface web : `http://localhost:5000`

## Technologies Utilisées
- **Flask** pour le backend web.
- **OpenCV** pour la reconnaissance faciale.
- **SQLite** pour le stockage des données.
- **HTML/CSS/JavaScript** pour l'interface utilisateur.

## Structure du Projet
```
roomiez/
│── app2.py                # Application principale
│── requirements.txt        # Dépendances
│── Procfile               # Configuration Heroku
│── static/                # Fichiers statiques (CSS, images...)
│── templates/             # Templates HTML
│── users.db               # Base de données des utilisateurs
│── information.db         # Base de données des informations
```

## Auteurs
- Meryem Benaammi et son équipe


Roomiez simplifie et sécurise la colocation étudiante grâce à l'IA et la reconnaissance faciale ! 
## User Interface Demo
Fig.1: Home page ![home](https://github.com/user-attachments/assets/81f03a11-9fc7-4d24-939e-b7b1ff3ca5e3)







