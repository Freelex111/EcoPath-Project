# 🌿 EcoPath - Industries

## Objectif
Informatiser la gestion des collectes de matières premières (déchets plastiques) et le suivi des inscriptions des clients pour la distribution de pavés écologiques au Cameroun. Le projet vise à transformer un défi environnemental en solution de construction durable.

## Description
Ce projet est une plateforme web vitrine et utilitaire pour l'entreprise EcoPath. Il permet de :

   * Présenter la vision des ingénieurs fondateurs et l'impact écologique du projet.

   * Gérer les inscriptions dynamiques des fournisseurs de déchets via des formulaires intelligents.

   * Simuler des commandes de pavés pour les clients.

   * Maintenir un suivi rigoureux via une gestion de versions avec Git.

## Architecture & Dossiers
Pour garantir une organisation claire du projet, les fichiers sont répartis comme suit :

   * Racine : `index.html` (Accueil) et `README.md`.

   * Dossier <strong>/pages</strong> : Contient toutes les interfaces secondaires (`Client.html`, `collecte.html`, `inscription.html`, etc).

   * Dossier <strong>/css</strong> : Regroupe les feuilles de style (`style.css`, `dashboard.css`,'messagerie.css', etc).

   * Dossier <strong>/images</strong> : Centralise toutes les ressources visuelles et icônes.

 La logique métier et les scripts de validation (aperçu d'image, vérification de formulaires, gestion du localStorage) sont directement intégrés dans les fichiers HTML pour assurer une autonomie totale de chaque page.

## Installation
1.  **Prérequis** : Avoir un navigateur web moderne (Chrome, Firefox, Edge).
2.  **Clonage du projet** :
    ```bash
    git clone https://github.com/Freelex111/EcoPath-Project.git
    ```
3.  **Structure** : Respectez l'arborescence des dossiers pour que les liens relatifs (../) fonctionnent correctement entre les pages et les styles.

## Exécution
Il suffit d'ouvrir le fichier index.html (à la racine) dans votre navigateur.

## Règles de contribution
Pour garder un projet propre et collaboratif, merci de respecter le format de message de commit suivant :

**Format :** `type : description courte`

* **feat** : Ajout d'une nouvelle fonctionnalité (ex: `feat : ajout du menu inscription`).
* **fix** : Correction d'un bug (ex: `fix : correction alignement logo`).
* **docs** : Modification de la documentation (ex: `docs : mise à jour du readme`).
* **style** : Modification du design/CSS sans changer la logique.

---
*Projet développé par l'équipe IT d'EcoPath - 2026*


