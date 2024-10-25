# Projet de Gestion des Utilisateurs et Groupes

Ce projet a pour objectif de gérer les utilisateurs et les groupes dans un environnement Linux. Il inclut des fonctionnalités pour l'ajout d'utilisateurs, la gestion des utilisateurs inactifs, ainsi que la gestion des groupes fonctionnels.

## Table des matières

- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Contributeurs](#contributeurs)

## Fonctionnalités

1. **Ajout et modification d'utilisateurs** (partie 1)
   - Ajout d'utilisateurs avec un mot de passe généré aléatoirement.
   - Mise à jour des informations des utilisateurs existants.

2. **Gestion des utilisateurs inactifs** (partie 2)
   - Identification des utilisateurs inactifs depuis plus de 90 jours.
   - Alertes générées pour les utilisateurs inactifs.
   - Options pour verrouiller ou supprimer les comptes inactifs, avec sauvegarde des répertoires personnels.

3. **Gestion des groupes fonctionnels** (partie 3)
   - Création de groupes.
   - Ajout et retrait d'utilisateurs dans les groupes.
   - Suppression de groupes vides.

4. **Gestion des permissions** (partie 4)
   - Configuration des permissions d'accès pour différents groupes sur des répertoires spécifiques.

## Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre_nom_utilisateur/nom_du_depot.git
2. Naviguez dans le répertoire du projet :
    ```bash
    cd nom_du_depot

## Utilisation

Exécutez le script pour chaque partie selon les besoins :

- Pour ajouter/modifier des utilisateurs :
    ```bash
    bash partie1_1.sh
    ```

- Pour gérer les utilisateurs inactifs :
    ```bash
    bash partie2_1.sh
    ```

- Pour gérer les groupes :
    ```bash
    bash partie3_1.sh
    ```

- Pour configurer les permissions :
    ```bash
    bash partie4_1.sh
    ```

## Contributeurs

- **Esteban** : Partie 2 (1.sh)
- **John** : Partie 1 (1.sh) et Partie 4 (1.sh)
- **Anthony** : Partie 3 (1.sh)

## Avertissements

- Assurez-vous d'exécuter ces scripts avec les permissions appropriées (souvent en tant que super utilisateur).
- Vérifiez les sauvegardes avant de supprimer des utilisateurs.
