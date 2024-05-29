# 🚀 Projet d'Infrastructure Cloud pour une PME

# Sommaire

1. [Objectif](#-objectif)
2. [Équipe](#️-équipe)
3. [Phases du Projet](#-phases-du-projet)
   - [Planification Initiale](#-planification-initiale)
   - [Conception de l'Infrastructure Cloud](#️-conception-de-linfrastructure-cloud)
   - [Mise en Œuvre](#-mise-en-œuvre)
   - [Sécurité et Gestion](#️-sécurité-et-gestion)
   - [Test et Validation](#-test-et-validation)
   - [Livraison et Déploiement Final](#-livraison-et-déploiement-final)
4. [Suivi et Rapport](#-suivi-et-rapport)
5. [Livrables](#-livrables)
6. [Plan de Projet](#️-plan-de-projet)
   - [Définir les besoins du client](#1-définir-les-besoins-du-client)
   - [Planification](#2-planification)
   - [Réalisation](#3-réalisation)
   - [Validation](#4-validation)
   - [Clôture du projet](#5-clôture-du-projet)
7. [RACI](#️-raci)
8. [Schéma infrastructure](#-schéma-infrastructure)


## 📋 Objectif

Le but de ce projet est de fournir, en équipe de 2, une infrastructure informatique minimale à une PME qui démarre son activité. Cette infrastructure sera réalisée dans le CLOUD et devra être livrée à temps, selon une méthodologie de gestion de projet rigoureuse.

## 🛠️ Équipe

- **Nom du Projet**
  - Qilby

- **Membres**
  - Maxance Ferran
  - Bourdoncle Alan

## 📅 Phases du Projet

### 1. 📑 Planification Initiale
- **Identifier les besoins de la PME**
  - Réaliser des réunions avec le client pour comprendre les besoins spécifiques.
  - Documenter les attentes et les contraintes du client.
- **Définir les objectifs du projet**
  - Formuler des objectifs clairs et précis basés sur les besoins identifiés.
- **Établir une feuille de route avec des jalons clés**
  - Définir des étapes critiques et des jalons importants pour suivre l’avancement du projet.

### 2. ☁️ Conception de l'Infrastructure Cloud
- **Choisir le fournisseur de services Cloud (AWS, Azure, GCP, etc.)**
  - Évaluer les options et choisir le fournisseur le plus adapté aux besoins de la PME.
- **Définir l'architecture réseau**
  - Créer un schéma de l'architecture réseau incluant tous les composants.
- **Planifier la sécurité et la conformité**
  - Établir des mesures de sécurité pour protéger les données et respecter les réglementations.

### 3. 🔨 Mise en Œuvre
- **Déployer les instances de serveurs**
  - Configurer un serveur AD/DHCP pour la gestion des comptes utilisateurs.
  - Mettre en place un serveur de fichiers avec l’arborescence et les droits d’accès définis.
  - Installer un serveur applicatif accessible via HTTPS pour le chef et le commercial.
- **Configurer les bases de données**
  - Mettre en place les bases de données nécessaires pour le fonctionnement de la PME.
- **Mettre en place les solutions de sauvegarde et de restauration**
  - Planifier et configurer des stratégies de sauvegarde régulières.

### 4. 🛡️ Sécurité et Gestion
- **Configurer les pare-feux et les règles de sécurité**
  - Mettre en place un firewall pour la gestion de la sécurité réseau (VLAN, ouverture de flux).
- **Implémenter les politiques de gestion des accès**
  - Définir et appliquer les règles d’accès aux différents dossiers et serveurs.
- **Surveiller et auditer l'infrastructure**
  - Utiliser des outils de surveillance pour garantir la disponibilité et la sécurité.

### 5. ✅ Test et Validation
- **Effectuer des tests de performance**
  - Tester la capacité des serveurs et des applications à supporter les charges de travail prévues.
- **Vérifier la résilience et la tolérance aux pannes**
  - Tester les scénarios de panne et vérifier la reprise après sinistre.
- **Recevoir les feedbacks et ajuster**
  - Recueillir les commentaires des utilisateurs finaux et ajuster l’infrastructure en conséquence.

### 6. 🚀 Livraison et Déploiement Final
- **Former le personnel de la PME**
  - Organiser des sessions de formation pour les utilisateurs sur l'utilisation de l'infrastructure.
- **Documenter l'infrastructure et les processus**
  - Fournir une documentation complète sur l’architecture, les configurations et les procédures.
- **Transférer la gestion et offrir un support initial**
  - Assurer une transition fluide vers l’équipe de la PME et offrir un support pendant les premières semaines.

## 📈 Suivi et Rapport

Nous utiliserons des outils de gestion de projet comme **Trello** ou **Jira** pour suivre l'avancement du projet et assurer une communication transparente avec la PME.

## 📄 Livrables

- **Plan d’exécution (plan projet)**
  - Documentation détaillant les étapes et jalons du projet.
- **Schéma d’architecture**
  - Diagramme représentant l’architecture réseau et les composants de l’infrastructure.
- **Règles de flux**
  - Liste des règles de sécurité et des flux de réseau configurés.
- **Infrastructure**
  - Détails techniques de l'infrastructure déployée.
- **Recette de livraison validée**
  - Documentation des tests réalisés et validation par le client.

## 🗂️ Plan de Projet

### 1. Définir les besoins du client
**Objectif :** Comprendre ce que le client attend du projet.

**Actions :**
- Réunion initiale : Identifier les besoins en infrastructure et en nombre de postes clients.
- Documenter les besoins : Spécifier les rôles des utilisateurs (Admin, Commercial, Assistant, Chef).
- Obtenir l'approbation : Confirmer les besoins avec le client.

### 2. Planification
**Objectif :** Préparer un plan clair pour le projet.

**Actions :**
- Calendrier : Définir les étapes du projet et fixer des dates.
- Ressources : Identifier les personnes et le matériel nécessaires.
- Communication : Planifier des réunions régulières pour suivre l'avancement.

### 3. Réalisation
**Objectif :** Mettre en place les éléments du projet.

**Actions :**
- **Serveurs :** (Jalon 1)
  - Installer et configurer les serveurs Windows.
    1. Serveur AD/DHCP (Active Directory / DHCP)
    2. Serveur de Base de Données
    3. Serveur de Fichiers
    4. Serveur Applicatif
  - Configurer les rôles des utilisateurs.
- **Postes clients :** (Jalon 2)
  - Installer et configurer les postes clients.
- **Sécurité :** (Jalon 3)
  - Installer et configurer le firewall.
  - Mettre en place les mesures de sécurité.

### 4. Validation
**Objectif :** Vérifier que tout fonctionne correctement et que le client est satisfait.

**Actions :**
- Tests : Vérifier le bon fonctionnement et la sécurité des systèmes.
- Formation : Former les utilisateurs à utiliser les nouveaux systèmes.
- Validation finale : Obtenir l'approbation finale du client.

### 5. Clôture du projet
**Objectif :** Terminer le projet de manière formelle.

**Actions :**
- Revue : Analyser ce qui a bien fonctionné et ce qui peut être amélioré.
- Support : Offrir une assistance après le déploiement.
- Rapport final : Documenter et clôturer le projet avec la signature du client.

## 🗒️ RACI

| Tâches / Activités | Responsable (R) | Autorité (A)   | Consulté (C)       | Informé (I)      |
|--------------------|-----------------|----------------|--------------------|------------------|
| **Analyse**        | Fournisseur     | Fournisseur    | Client             | Client           |
| **Planification**  | Fournisseur     | Fournisseur    | Client             | Client           |
| **Réalisation**    | Fournisseur     | Fournisseur    | Client             | Client           |
| **Validation**     | Fournisseur     | Client         | Fournisseur, Client | Client, Fournisseur |

## Schéma infrastructure

![Schéma de l'infrastructure](/images/Schémainfra.png)