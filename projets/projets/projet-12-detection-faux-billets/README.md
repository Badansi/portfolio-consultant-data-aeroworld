# Projet 12 – Détection de faux billets (Machine Learning)

## Contexte
Mission réalisée pour l’Organisation nationale de lutte contre le faux-monnayage (ONCFM).

Objectif : développer une application de Machine Learning capable de distinguer automatiquement les vrais billets des faux billets en euros à partir de mesures géométriques.

## Données
1 500 billets scannés :
- 1 000 vrais
- 500 faux

Variables :
- length
- height_left
- height_right
- margin_up
- margin_low
- diagonal

## Objectif du projet
Créer un modèle performant capable d’identifier un maximum de faux billets (critère prioritaire).

## Méthodologie

### 1. Analyse exploratoire
- Statistiques descriptives
- Analyse des distributions
- Détection des outliers
- Étude des corrélations

### 2. Préparation des données
- Standardisation (z-score)
- Gestion des valeurs manquantes
- Imputation par régression si nécessaire
- Création éventuelle de variables dérivées

### 3. Modélisation
Test de plusieurs algorithmes :
- Régression logistique
- K-Nearest Neighbors (KNN)
- K-means
- Random Forest
- ACP en analyse complémentaire

### 4. Évaluation
- Matrices de confusion
- Précision
- Recall
- F1-score
- Comparaison des performances

Le modèle final est sélectionné selon sa capacité à détecter un maximum de faux billets.

## Déploiement
Création d’un notebook fonctionnel permettant :
- d’entrer les dimensions d’un billet
- d’obtenir une prédiction : vrai / faux

## Livrables
- Notebook d’analyse exploratoire
- Notebook application prédictive
- Support de présentation
- Recommandations finales

## Compétences mobilisées
Machine Learning  
Préparation et traitement des données  
Évaluation comparative de modèles  
Data science appliquée à un cas réel  
