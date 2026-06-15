# SSH-Unauthorized-Access-Lab
Detection and analysis of unauthorized SSH access attempts on a Linux server.
# SSH Unauthorized Access Lab

## Objectif

Simuler une tentative d'accès non autorisée sur un serveur Linux afin d'analyser les journaux d'authentification SSH.

---

## Environnement

- Windows 11
- Ubuntu Server
- OpenSSH Server
- VirtualBox
- SSH (Port 22)

---

## Actions réalisées

- Installation d'OpenSSH Server
- Vérification du service SSH
- Connexion distante depuis Windows
- Tentatives répétées avec un utilisateur invalide
- Analyse des journaux Linux

---

## Architecture

Windows Host
↓ SSH
Ubuntu Server

---

## Résultats

Les événements suivants ont été observés :

- Invalid user
- Failed password
- Adresse IP source
- Tentatives de connexion échouées

---

## Compétences démontrées

- Linux Administration
- SSH
- Analyse de logs
- Investigation sécurité
- Détection d'accès non autorisés
- Réseaux TCP/IP
