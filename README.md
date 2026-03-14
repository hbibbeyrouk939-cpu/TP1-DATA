TP N°1 : Pipeline d'Acquisition de Données (KDD)
Présentation du Projet
Ce projet a été réalisé dans le cadre du module Data Mining (L2 MIAGE/DA2I 2025-2026) sous la direction du Pr. EL BENANY.
Objectif Principal

L'objectif de ce travail est de concevoir et de mettre en œuvre un pipeline d'acquisition de données capable de collecter et de fusionner des informations provenant de sources hétérogènes :
 * CSV : Données structurées relatives à la performance des étudiants.
 * JSON : Données semi-structurées sur les films.
 * SQL : Simulation d'extraction de données filtrées.
 * Web Scraping : Extraction de titres à partir de Wikipedia.
Structure du Répertoire
Le projet est organisé de la manière suivante :
 * data/ : Contient les fichiers sources (student-mat.csv, movies.json).
 * notebooks/ : Contient le notebook principal (TP1_KDD_Pipeline.ipynb).
 * src/ : Dossier dédié aux scripts Python réutilisables.
 * requirements.txt : Liste des dépendances nécessaires au projet.
Installation
Pour préparer l'environnement de travail et installer les bibliothèques requises, exécutez la commande suivante :
pip install -r requirements.txt

Utilisation
Pour visualiser les étapes d'acquisition et de fusion des données, veuillez ouvrir le fichier suivant avec Jupyter Lab ou VS Code :
notebooks/TP1_KDD_Pipeline.ipynb

