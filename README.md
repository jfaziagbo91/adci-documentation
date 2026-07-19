# ADCI Documentation

> Documentation officielle du projet **ADCI – Aujourd'hui, Demain, la Côte d'Ivoire**

---

# Présentation

Ce dépôt contient l'ensemble de la documentation fonctionnelle, technique et organisationnelle du projet **ADCI**.

L'objectif est de centraliser les spécifications, les décisions d'architecture, les modèles de données, les maquettes, les diagrammes UML ainsi que la documentation des API.

Le code source du projet est hébergé dans un dépôt distinct :

- adci-web

---

# Objectifs

Ce dépôt permet de :

- centraliser la documentation du projet ;
- versionner les documents avec Git ;
- produire les Spécifications Fonctionnelles Générales (SFG) ;
- assurer la traçabilité des décisions ;
- documenter les évolutions du produit ;
- faciliter la collaboration entre les parties prenantes.

---

# Organisation

```
adci-documentation/
│
├── docs/
├── exports/
├── references/
├── scripts/
├── sprint/
└── templates/
```

---

# Contenu

## Product

Documentation fonctionnelle du produit.

```
Vision
Personas
Epics
Features
Backlog
Roadmap
User Stories
Décisions
```

---

## SFG

Documentation officielle du projet rédigée en LaTeX.

Contient notamment :

- Vision Produit
- Architecture Fonctionnelle
- Backlog
- User Stories
- Maquettes
- Règles de gestion
- Exigences non fonctionnelles

---

## UML

Diagrammes UML.

- Cas d'utilisation
- Activité
- Séquence
- Classes
- Composants
- Déploiement
- États

---

## BPMN

Processus métier.

---

## MCD

Modèle Conceptuel de Données.

---

## API

Documentation des API REST.

- OpenAPI
- Swagger
- Endpoints
- Exemples JSON
- Collections Postman

---

## Maquettes

Interfaces Desktop et Mobile.

---

## Tests

Documentation de validation.

- Jeux de données
- Cas de tests
- Campagnes
- Procès-verbaux
- Matrice de traçabilité

---

## Architecture

Documentation de l'architecture fonctionnelle et technique.

---

## Exports

Documents générés.

- PDF
- DOCX
- PPTX
- ZIP
- Images

---

# Technologies utilisées

- Git
- GitHub
- Markdown
- LaTeX
- Draw.io
- Visual Studio Code

---

# Gestion des versions

Le dépôt est versionné avec Git.

Branches utilisées :

```
main
develop
feature/*
release/*
hotfix/*
```

---

# Convention documentaire

Les documents sont rédigés en :

- Markdown
- LaTeX
- Draw.io

Tous les documents sont versionnés.

---

# État d'avancement

| Élément | Statut |
|----------|:------:|
| Vision Produit | ✅ |
| MVP V1 | ✅ |
| Parcours Utilisateur | ✅ |
| User Stories | ✅ |
| Maquettes UX | ✅ |
| Structure documentaire | ✅ |
| SFG Tome 1 | 🚧 |
| Diagrammes UML | 🚧 |
| BPMN | 🚧 |
| API | ⏳ |
| Tests | ⏳ |

---

# Roadmap documentaire

## Sprint 0

- Vision Produit
- MVP
- User Stories
- Maquettes
- Initialisation du dépôt documentaire

## Sprint 1

- SFG Tome 1
- BPMN
- UML
- MCD

## Sprint 2

- API
- Architecture
- Cas de tests

## Sprint 3

- Documentation finale
- Release 1.0

---

# Licence

Ce projet est distribué sous la licence définie dans le fichier `LICENSE`.

---

# Auteur

**Jean-François AZIAGBO**

Product Owner | PMP® | PSPO II | PSM II

Projet ADCI – Aujourd'hui, Demain, la Côte d'Ivoire
