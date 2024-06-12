# 🚀 Compte rendu Projet Infra (Qilby)
### par FERRAN Maxance et Bourdoncle Alan

# RAPPEL :
Pour rappel, voici notre Plan Projet :

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
    2. Serveur de Fichiers
    3. Serveur Applicatif
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

# *Où en sommes-nous ?*

Dans ce projet infra, nous en sommes à l'étape de la réalisation. Toutes les étapes précédentes sont réalisées. Dans cette étape, nous avons mis en place tous les éléments présents sur le schéma de l'infrastructure. Cependant, nous avons pu configurer correctement trois éléments :

- Le switch avec la mise en place de trois VLAN (un pour le serveur DHCP, un pour les deux autres serveurs, un pour les postes clients)
- Le serveur DHCP a été configuré correctement avec la mise en place du DNS, une forêt, les ip en DHCP, les rôles et les groupes mais n'est pas dans le bon VLAN pour le moment
- Le serveur Applicatif a bien rejoint le domaine mais n'est pas dans le bon VLAN et n'est pas terminé car, à l'heure actuelle, il n'a pas de page web HTTPS

Les deux serveurs peuvent se ping, donc peuvent communiquer entre eux.

À l'heure actuelle, il nous manque des utilisateurs, le serveur de fichiers et les postes clients ne sont pas dans le domaine mais sont bien présents. Également, il manque les quatre dossiers du serveur de fichiers.

Nous avons bien un firewall.

Lors de la dernière séance avec PnetLab, nous avons voulu enlever le switch et passer directement par le firewall pour nos connexions car le switch ne fonctionner pas correctement, on pouvait même plus l'allumer. Puis après nos recherches, nous avons fini par en remettre un mais en changeant ce dernier (nous sommes passés sous un CISCO) car sa configuration était plus adéquate avec notre idée d'infrastructure.

Ainsi, nous avons pu respecter notre schéma d'infrastructure initial.

# Identifiant de connexion

- *Serveur **AD/DHCP*** : 1 compte ***"Administrateur"*** ***|*** Mot de passe : ***Azerty33****