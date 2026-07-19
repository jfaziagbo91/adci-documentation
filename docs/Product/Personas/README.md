# Personas

Version : 1.0

Projet : ADCI

---

# Objectif

Ce document décrit les principaux utilisateurs de la plateforme ADCI.

Les personas permettent de concevoir les fonctionnalités en fonction des besoins réels des utilisateurs.

---

# Persona 1 : Visiteur

## Description

Le visiteur est une personne qui découvre le mouvement ADCI et souhaite obtenir des informations avant d'effectuer une demande d'adhésion.

---

## Objectifs

- Découvrir le mouvement.
- Comprendre les conditions d'adhésion.
- Choisir une formule adaptée.
- Déposer une demande rapidement.
- Recevoir une confirmation.

---

## Besoins

- Navigation simple.
- Interface claire.
- Peu d'étapes.
- Formulaire compréhensible.
- Site responsive.

---

## Frustrations

- Formulaires trop longs.
- Informations peu claires.
- Erreurs de validation.
- Temps de chargement élevé.

---

## Parcours

1. Consultation du site.
2. Lecture des informations.
3. Début de la demande.
4. Saisie des informations.
5. Téléversement de la pièce d'identité.
6. Ajout éventuel du conjoint.
7. Choix de la formule.
8. Vérification.
9. Soumission.

---

## User Stories concernées

US-01 à US-08

---

# Persona 2 : Gestionnaire des adhésions

## Description

Le gestionnaire est chargé d'examiner les demandes d'adhésion reçues.

---

## Objectifs

- Consulter les demandes.
- Vérifier les informations.
- Contrôler les pièces justificatives.
- Valider ou refuser une demande.
- Contacter le demandeur si nécessaire.

---

## Besoins

- Liste des demandes.
- Recherche rapide.
- Historique.
- Téléchargement des pièces.
- Tableau de bord.

---

## Fonctionnalités attendues (V2)

- Authentification.
- Tableau de bord.
- Validation.
- Refus.
- Export Excel.
- Statistiques.

---

# Persona 3 : Administrateur

## Description

L'administrateur configure et supervise la plateforme.

---

## Objectifs

- Gérer les utilisateurs.
- Gérer les formules d'adhésion.
- Consulter les statistiques.
- Administrer les paramètres.

---

## Fonctionnalités attendues (V2)

- Gestion des comptes.
- Gestion des rôles.
- Paramétrage des cotisations.
- Paramétrage des campagnes.
- Journal des actions.

---

# Synthèse

| Persona | V1 | V2 |
|----------|:--:|:--:|
| Visiteur | ✓ | ✓ |
| Gestionnaire | | ✓ |
| Administrateur | | ✓ |

---

# Priorité

## MVP

- Visiteur

## Versions futures

- Gestionnaire
- Administrateur

---

# Correspondance avec les Epics

| Persona | Epic |
|----------|------|
| Visiteur | Adhésion |
| Gestionnaire | Gestion des adhésions |
| Administrateur | Administration |

---

# Conclusion

Le MVP est entièrement centré sur le persona **Visiteur**. Les personas **Gestionnaire des adhésions** et **Administrateur** seront pris en compte à partir de la V2 afin d'accompagner la gestion opérationnelle et l'administration de la plateforme.
