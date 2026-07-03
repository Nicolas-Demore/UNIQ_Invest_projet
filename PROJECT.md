# Objectif du projet

## Contexte

L'un des défis majeurs d'un fonds d'investissement est de savoir **détecter les signaux faibles** de réussite ou d'échec dans l'historique financier d'une startup, pour pouvoir ainsi investir ou se rétracter.

## Le But du Projet

Notre objectif a donc été d'essayer de prédire les potentielles valorisations des startups et les dates de leurs prochaines levées de fonds, donnant ainsi des signaux clairs d'investissement.
Une première étape a été l'analyse des datas à notre dispositions (historiques financiers de centaines de startups), le nettoyage des données et la mise en place d'algorithmes de prédiction.

Le choix est la mise en place des ces algorithmes a occupé la majeure partie du hackaton. En raison de dataset trop simple, il y a eu un travail de réflexion et de débat sur l'augmentation "artificiel" des données et la mise en place des meilleurs algorithmes adaptés au problème dans l'espoir de trouver le modèle le plus performant.

Ce fichier comprend les étapes de notre raisonnement, de l'implémentation de modèles simples (régression et random forest) à des modèles plus élaborrés (modèle LSTM et XGBoost) semblant plus convainquant.
Chacun des fichiers notebooks contenant les modèles sont détaillés (démarche, choix des paramètres, des hyperparamètres, détail sur l'implémentation, motivations etc.)

Chacun de ces modèles s'accompagnent également d'une analyse des résultats et des réflexions sur des possibles améliorations (optimisation, nouvelles features, discussion sur le biais etc.) 


