# dockerfile-ansible

 Environnement Ansible basé sur Docker composé de deux images :

**1. Image Ansible --> Control Node**

-  Contient Ansible installé.
-  Contient OpenSSH Server
-  Sert de machine de pilotage (control node).
-  Permet d’exécuter les playbooks vers les serveurs cibles.

Lien vers le repository Dockerhub de l'image  -->  **https://hub.docker.com/r/loicmeng/ansible**

**2. Image Serveur cible --> Managed Node**

-  Contient OpenSSH Server.
-  Supporte systemd pour gérer les services.
-  Sert à simuler des serveurs (web, db, etc.).
  
Lien vers le repository Dockerhub de l'image  --> **https://hub.docker.com/r/loicmeng/ansible_client** 

**L’objectif est de disposer d’un lab d’apprentissage et de test Ansible reproductible, entièrement conteneurisé.**
