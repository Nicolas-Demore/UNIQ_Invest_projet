# Prédiction : Valorisation et Timing (Modèle LSTM)

Ce projet implémente un réseau de neurones récurrents (LSTM) pour analyser l'historique financier de startups et prédire leur prochaine levée de fonds. 

L'objectif est d'estimer deux variables clés à partir des données historiques (type PitchBook) :
1. La **Valorisation Post-Money** (en millions de dollars).
2. Le **Temps estimé** avant le prochain round (en mois).

## Contenu du Projet

L'intégralité du projet est détaillée et documentée au sein du Notebook(`Prédiction_RNN_Valo_and_next_round.ipynb`), en voici un rapide résumé :

- **Data Preprocessing :** Nettoyage, gestion chronologique, mise en place des features.
- **Standardisation :** Passage à l'échelle logarithmique (pour gérer les différentes échelles des valorisations) et standardisation classique.
- **Formatage Tenseurs :** Création des matrices 3D adaptées au LSTM.
- **Modèle Deep Learning :** Mise en place de l'architecture du modèle (choix des hyperparamètres etc., mode d'apprentissage etc.) et entrainement.
- **Évaluation :** Observation du MSE et comparaison graphique des trajectoires réelles vs prédites sur un jeu de test.

## Améliorations Futures

Le Notebook propose enfin des pistes d'amélioration (discussions sur le biais, nouvelles features etc.)

## Installation et Utilisation

Installez les dépendances nécessaires  :

   ```bash
   pip install -r requirements.txt
   ```
   