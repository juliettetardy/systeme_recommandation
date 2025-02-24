# Projet Data Mining - Système de recommandation

Auteurs : Juliette Tardy et Estelle Zheng

CPE Lyon - 4ETI

## Description du projet
Le projet consiste à développer un système de recommandation de photos de chiens et de chats basé sur les préférences d'un utilisateur. 

## Structure du projet
Le projet est structuré en plusieurs fichiers Jupyter Notebooks qui assurent différentes étapes du processus :

1. **Acquisition.ipynb** : Collecte des images de chiens et de chats à partir de Wikipédia.
2. **Etiquetage.ipynb** : Étiquetage automatique des images avec différentes caractéristiques (orientation, qualité, type d'animal, nature, luminosité) et génère le fichier `étiquetage.json`.
3. **Interaction.ipynb** : Création du profil utilisateur sur un échantillon de 20 photos et génère un fichier `profil.json`
4. **Analyse.ipynb** : Analyse des données et des préférences utilisateur pour identifier les éléments clés.
5. **Recommandation.ipynb** : Génération des recommandations basées sur les préférences utilisateur.
6. **Visualisation.ipynb** : Visualisation des données sous forme de graphiques.

## Détails Techniques

### Langages utilisés :
- **Python** (Jupyter Notebooks)
- **Fichiers JSON** 

### Bibliothèques utilisées : 

#### Manipulation des données et analyse :
- **Pandas** : DataFrames utilisés pour organiser les données et effectuer des analyses statistiques.
- **Matplotlib** : Visualisation des données sous forme de graphiques.
- **NumPy** : Manipulation des matrices et des tableaux multidimensionnels, utilisée pour les calculs liés aux images.

#### Traitement d'images pour l'étiquetage :
- **OpenCV** : Traitement des images (redimensionnement, conversion en niveaux de gris, analyse des couleurs).
- **Keras / TensorFlow** : Frameworks pour l'apprentissage automatique et le deep learning, utilisés pour la classification d'images (chien ou chat) avec l'IA MobileNetV2.
#### Analyse des données
- **Scikit-learn** : Utilisé pour les algorithmes d'apprentissage automatique, notamment **Random Forest** 
