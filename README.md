# Projet d'Optimisation Stochastique

##  Description du Projet

Ce projet explore l'optimisation stochastique appliquée à un problème de régression linéaire avec des données bruitées. Différents algorithmes d'optimisation sont implémentés pour estimer les paramètres du modèle tout en minimisant l'erreur quadratique moyenne (MSE). Une analyse comparative de la convergence et de la robustesse des algorithmes face au bruit est réalisée.


##  Problématique : Identification des défis liés à l'estimation des paramètres d'un modèle linéaire en présence de bruit.


# Algorithmes Implémentés
1. Descente de Gradient Stochastique (SGD) : Mise à jour des paramètres à chaque échantillon.
2.   Mini-batch Gradient Descent : Compromis entre SGD et Batch Gradient Descent.
3.   RMSprop : Adaptation dynamique du taux d'apprentissage pour stabiliser les mises à jour.
4.   Adam (Adaptive Moment Estimation) : Combinaison de SGD et RMSprop pour une convergence rapide.

## Prérequis

Python 3.x

Bibliothèques : numpy, matplotlib

Installation

1. Clonez le dépôt :

git clone https://github.com/ihssane2002/optimisation-stockastqiue.git
cd optimisation-stockastqiu

2. Installez les dépendances :

pip install numpy matplotlib

3. Exécution

Vous pouvez exécuter le projet directement sur Google Colab 

Sur Google Colab :

Ouvrez le fichier Code projet.ipynb sur Google Colab.

Cliquez sur "Exécuter tout" pour lancer les simulations et visualiser les résultats.


# Analyse des Résultats

1. Convergence : Adam offre une convergence plus rapide et stable.

2. Sensibilité au Bruit : RMSprop et Adam sont plus robustes face aux données bruitées.

3. Régularisation : L'ajout de la régularisation L2 améliore la généralisation.

# Conclusion

Adam se distingue par sa rapidité de convergence et sa robustesse face au bruit, tandis que le Mini-batch Gradient Descent offre un bon compromis entre stabilité et performance. RMSprop reste une option viable, mais légèrement inférieure à Adam dans les environnements très bruités.
# Auteurs

GAREH Malika

BAMMAD Ihssane
