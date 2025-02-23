# Projet Data Mining

Auteurs : Juliette Tardy et Estelle Zheng

CPE Lyon - 4ETI

## Description du projet
Le projet consiste à développer un système de recommandation d'images basé sur les préférences des utilisateurs. Il a pour but de recommander des photos de chiens et de chats en fonction de critères précis tels que les caractéristiques visuelles des images.

## Structure du projet
Le projet est structuré en plusieurs fichiers Jupyter Notebooks qui assurent différentes étapes du processus :

1. **Acquisition.ipynb** : Collecte des images de chiens et de chats à partir de Wikipédia.
2. **Etiquetage.ipynb** : Étiquetage automatique des images avec différentes caractéristiques (orientation, qualité, type d'animal, nature, luminosité) et génère le fichier `étiquetage.json`.
3. **Interaction.ipynb** : Création du profil utilisateur sur un échantillon de 20 photos et génère un fichier `profil.json`
4. **Analyse.ipynb** : Analyse des données et des préférences utilisateur pour identifier les éléments clés.
5. **Recommandation.ipynb** : Génération des recommandations basées sur les préférences utilisateur.
6. **Visualisation.ipynb** : Visualisation des données sous forme de graphiques.

