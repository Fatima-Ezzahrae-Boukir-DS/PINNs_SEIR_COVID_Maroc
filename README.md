# PINNs_SEIR_COVID_Maroc
Ce dépôt contient l’implémentation d’un projet de fin d’études portant sur l'identification des paramètres du modèle épidémique SEIR à l’aide de réseaux de neurones informés par la physique (PINNs).
L’approche repose sur la résolution inverse d’un système SEIR à partir de données synthétiques (générées via RK4) ainsi que de données réelles (COVID-19 – Maroc). Deux méthodes sont comparées :

Une approche conjointe, où les compartiments et paramètres sont estimés simultanément ;

Une approche Split-PINN, qui décompose l’apprentissage en deux phases (détection + dynamique).

Le notebook principal (notebooks/SEIR_PINN_notebook.ipynb) détaille toutes les étapes de modélisation, d’entraînement, de visualisation et d’analyse.

