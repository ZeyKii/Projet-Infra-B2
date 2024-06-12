# 🚀 Compte rendu Projet Infra (Qilby)
### par FERRAN Maxance et Bourdoncle Alan


# RAPPEL : 
Pour rappel voici notre Plan Projet :

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

# *Où en sommes nous ?*

Dans ce projet infra nous en sommes à l'étape de la réalisation, toute les étapes précédente sont réalisées. Dans cette étape nous avons mis en place tout les élements présents sur le schéma de l'infrastructure. Cependant nous avons pu configurer correctement 3 éléments : 

- Le switch avec une mise en place de 3 VLAN (1 pour le serveur DHCP, 1 pour les deux autres serveurs, 1 pour les Poste client)
- Le serveur DHCP à été configurer correctement mais n'est pas dans le bon VLAN pour le moment 
- Le serveur Applicatif à bien rejoins le domaine mais n'est pas dans le bon VLAN et n'est pas terminé car à l'heure actuelle il n'a pas de page web HTTPS

Les deux serveurs peuvent se ping donc peuvent communiquer entre eux.

A l'heure actuel il nous manque des utilisateur, le serveur de fichier et les postes clients ne sont pas dans le domaine mais bien présents. Egalement il manque les 4 dossiers du serveur de fichier.

On a bien un firewall.

Lors de la dernières séances avec PnetLab on a voulus enlever le switch et passer directement par le Firewall pour nos connexion, puis avec nos recherches on a finit par en remettre un mais en changeant ce dernier (on est passer sous un CISCO) car sa configuration était plus adéquate avec notre idée d'infrastructure.

Ainsi nous avons pu respecter notre schéma d'infrastructe initial.

# Identifiant de connexion

- *Serveur **AD/DHCP*** : 1 compte ***"Administrateur"***  ***|*** Mot de passe : ***Azerty33****