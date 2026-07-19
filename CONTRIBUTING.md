# Guide de contribution

Bienvenue dans le dépôt documentaire du projet **ADCI**.

Ce document définit les règles de contribution afin de garantir une documentation homogène, maintenable et facilement exploitable.

---

# Objectif

Les objectifs de ce dépôt sont :

- centraliser la documentation du projet ;
- assurer la traçabilité des évolutions ;
- faciliter la collaboration entre les membres de l'équipe ;
- garantir une qualité documentaire constante.

---

# Organisation du dépôt

```
docs/
exports/
references/
scripts/
sprint/
templates/
```

Chaque dossier possède un rôle précis et doit être utilisé conformément à sa destination.

---

# Règles de nommage

## Dossiers

Les dossiers sont nommés :

- en anglais lorsque cela concerne la structure du dépôt ;
- avec une majuscule initiale.

Exemple :

```
Product
Architecture
Tests
API
```

---

## Fichiers Markdown

Les fichiers Markdown utilisent le format :

```
nom-document.md
```

Exemples :

```
vision-produit.md

backlog-produit.md

roadmap.md
```

---

## Fichiers LaTeX

Les chapitres suivent la convention :

```
01-page-garde.tex
02-historique.tex
03-introduction.tex
```

Les sections suivent la convention :

```
us01-consulter-adhesion.tex

us02-informations-personnelles.tex
```

---

## Diagrammes

Les diagrammes utilisent le format :

```
nom-diagramme.drawio
nom-diagramme.png
nom-diagramme.pdf
```

---

# Convention Git

Chaque modification suit le processus suivant.

```
git pull

git checkout -b feature/nom-feature

git add .

git commit

git push
```

Les commits doivent être explicites.

Exemples :

```
Ajout de la Vision Produit

Création du diagramme BPMN

Mise à jour des User Stories

Ajout du chapitre Architecture
```

---

# Gestion des branches

Le dépôt utilise Git Flow.

```
main
develop
feature/*
release/*
hotfix/*
```

Les modifications ne sont jamais réalisées directement sur `main`.

---

# Documentation

Toute évolution fonctionnelle doit être documentée.

Les éléments suivants doivent être maintenus à jour :

- Vision Produit ;
- Backlog ;
- User Stories ;
- Maquettes ;
- Diagrammes ;
- API ;
- SFG.

---

# Documentation des User Stories

Chaque User Story doit respecter le modèle suivant.

- Description
- Contexte
- Critères d'acceptation
- Règles de gestion
- Priorité
- Epic
- Persona
- Définition of Done

---

# Documentation UML

Les diagrammes UML sont réalisés avec Draw.io.

Chaque diagramme est exporté :

- au format Draw.io ;
- au format PNG ;
- au format PDF si nécessaire.

---

# Documentation BPMN

Chaque processus métier doit être représenté par un diagramme BPMN.

Les fichiers sont enregistrés dans :

```
docs/BPMN/
```

---

# Documentation API

Chaque API doit être documentée.

La documentation comprend :

- description ;
- endpoints ;
- paramètres ;
- exemples de requêtes ;
- exemples de réponses ;
- codes HTTP ;
- règles de sécurité.

---

# Documentation des maquettes

Chaque écran doit être disponible :

- en version Desktop ;
- en version Mobile.

Chaque maquette doit être associée à une ou plusieurs User Stories.

---

# Documentation des tests

Chaque fonctionnalité doit disposer de :

- cas de tests ;
- jeux de données ;
- résultats de recette ;
- matrice de traçabilité.

---

# Qualité documentaire

Avant toute validation, vérifier que :

- les documents sont à jour ;
- les liens sont valides ;
- les images sont présentes ;
- les diagrammes correspondent aux spécifications ;
- les User Stories respectent le format défini.

---

# Gestion des versions

Toute évolution significative doit être reportée dans :

```
CHANGELOG.md
```

---

# Outils utilisés

- Git
- GitHub
- Git Bash
- Visual Studio Code
- LaTeX
- Draw.io
- Markdown

---

# Bonnes pratiques

- Une seule source de vérité par information.
- Éviter les doublons.
- Documenter chaque décision importante.
- Utiliser des noms explicites.
- Mettre à jour la documentation en même temps que le projet.
- Conserver un historique complet des évolutions.

---

# Validation

Une contribution est considérée comme terminée lorsque :

- les documents sont complets ;
- les conventions sont respectées ;
- les modifications sont versionnées avec Git ;
- les fichiers sont correctement organisés ;
- le dépôt reste cohérent.
