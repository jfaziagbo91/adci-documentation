# Product Backlog V1

**Projet :** ADCI – Aujourd'hui, Demain, la Côte d'Ivoire

**Version :** V1 (MVP)

**Statut :** En préparation

**Product Owner :** Jean-François AZIAGBO

---

# Objectif

Ce document présente le Product Backlog de la version 1 (MVP) de la plateforme ADCI.

Il constitue la référence fonctionnelle pour la planification des développements.

---

# Objectifs du MVP

Le MVP permet à un visiteur :

- de consulter les informations d'adhésion ;
- de déposer une demande d'adhésion en ligne ;
- de transmettre les informations nécessaires ;
- de choisir une formule d'adhésion ;
- de vérifier le récapitulatif ;
- de soumettre sa demande ;
- de recevoir une confirmation.

Le MVP ne comprend pas de paiement en ligne ni d'espace adhérent.

---

# Epic

| ID | Epic | Priorité | Version |
|----|------|----------|----------|
| EPIC-01 | Gestion des adhésions | Must Have | V1 |

---

# Features

| ID | Feature | Epic | Priorité |
|----|----------|------|----------|
| FT-01 | Consultation de la page Adhésion | EPIC-01 | Must |
| FT-02 | Informations personnelles | EPIC-01 | Must |
| FT-03 | Pièce d'identité | EPIC-01 | Must |
| FT-04 | Informations du conjoint | EPIC-01 | Must |
| FT-05 | Choix de la formule | EPIC-01 | Must |
| FT-06 | Récapitulatif | EPIC-01 | Must |
| FT-07 | Soumission de la demande | EPIC-01 | Must |
| FT-08 | Responsive | EPIC-01 | Must |

---

# User Stories

| ID | User Story | Feature | Priorité | Story Points | Sprint | Statut |
|----|------------|----------|----------|--------------|---------|---------|
| US-01 | Consulter la page Adhésion | FT-01 | Must | 3 | Sprint 1 | Terminé |
| US-02 | Renseigner les informations personnelles | FT-02 | Must | 8 | Sprint 1 | Terminé |
| US-03 | Ajouter une pièce d'identité | FT-03 | Must | 5 | Sprint 1 | Terminé |
| US-04 | Ajouter un conjoint | FT-04 | Must | 8 | Sprint 1 | Terminé |
| US-05 | Choisir une formule d'adhésion | FT-05 | Must | 3 | Sprint 1 | Terminé |
| US-06 | Vérifier le récapitulatif | FT-06 | Must | 5 | Sprint 1 | Terminé |
| US-07 | Soumettre la demande | FT-07 | Must | 5 | Sprint 1 | Terminé |
| US-08 | Utiliser le site sur mobile | FT-08 | Must | 5 | Sprint 1 | Terminé |

---

# Estimation

| Élément | Valeur |
|----------|---------|
| Nombre d'Epics | 1 |
| Nombre de Features | 8 |
| Nombre de User Stories | 8 |
| Story Points totaux | 42 |

---

# Dépendances

| User Story | Dépend de |
|------------|-----------|
| US-02 | US-01 |
| US-03 | US-02 |
| US-04 | US-03 |
| US-05 | US-04 |
| US-06 | US-05 |
| US-07 | US-06 |
| US-08 | Aucune |

---

# Hors périmètre

Les fonctionnalités suivantes sont exclues de la V1 :

- Authentification
- Paiement en ligne
- Tableau de bord
- Administration
- Gestion des adhérents
- Renouvellement d'adhésion
- Notifications SMS
- Carte d'adhérent
- Historique des cotisations

---

# Critères de validation du MVP

Le MVP sera considéré comme terminé lorsque :

- toutes les User Stories V1 seront validées ;
- les critères d'acceptation seront satisfaits ;
- les tests fonctionnels seront validés ;
- les tests de non-régression seront passés ;
- les maquettes seront conformes au développement ;
- les SFG seront finalisées ;
- la documentation UML et BPMN sera à jour ;
- le Product Owner validera la version.

---

# État d'avancement

| Domaine | Statut |
|----------|:------:|
| Vision Produit | ✅ |
| Personas | ✅ |
| Epics | ✅ |
| Features | 🚧 |
| Product Backlog | 🚧 |
| User Stories | ✅ |
| Maquettes Desktop | ✅ |
| Maquettes Mobile | ✅ |
| SFG | 🚧 |
| UML | ⏳ |
| BPMN | ⏳ |
| MCD | ⏳ |
| API | ⏳ |
| Tests | ⏳ |

---

# Historique

| Version | Date | Auteur | Description |
|----------|------|---------|-------------|
| 1.0 | Juillet 2026 | Jean-François AZIAGBO | Création du Product Backlog V1 |
