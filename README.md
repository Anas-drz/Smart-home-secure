# Smart-home-secure
# 🏠🔐 Projet : Maison Intelligente Sécurisée

Ce projet porte sur la **conception et la simulation d’une maison intelligente sécurisée**, à l’aide de deux environnements de simulation réseau : **Cisco Packet Tracer** et **GNS3**.

---

## 📌 Objectifs

- Concevoir un système domotique intelligent et interconnecté
- Mettre en place des mécanismes de **sécurité réseau** adaptés à l’environnement IoT
- Simuler l’infrastructure avec des outils professionnels (Packet Tracer, GNS3)
- Intégrer des technologies modernes comme **pfSense**, **MQTT (EMQX)**, **TLS/SSL**, etc.

---

## 🛠️ Technologies utilisées

| Environnement     | Description                                          |
|-------------------|------------------------------------------------------|
| **Cisco Packet Tracer** | Simulation initiale de la topologie domotique : capteurs, caméras IP, actionneurs |
| **GNS3**              | Simulation avancée avec virtualisation de pare-feu et serveurs |
| **pfSense**           | Pare-feu pour le filtrage, la segmentation et la sécurité WAN/LAN |
| **MQTT (EMQX)**       | Protocole de messagerie IoT sécurisé              |
| **TLS/SSL**           | Chiffrement des communications entre objets connectés |
| **ACL**               | Listes de contrôle d'accès pour restreindre les communications |

---

## 🔧 Architecture du projet

1. **Cisco Packet Tracer**  
   Création d’un prototype de maison connectée :
   - Caméras IP, capteurs (mouvement, gaz, feu, température)
   - Configuration d’un routeur avec ACL pour contrôler les flux réseau

2. **Migration vers GNS3**  
   Simulation plus poussée avec :
   - Déploiement de **pfSense** pour un contrôle précis des VLANs
   - Mise en œuvre d’un serveur **MQTT/EMQX**
   - Sécurisation des échanges avec **TLS/SSL** et authentification client

---

## 🔐 Sécurité mise en place

- 🔒 **Chiffrement TLS/SSL** entre les objets et le broker MQTT
- 👤 **Authentification** des objets connectés
- 🧱 **Pare-feu pfSense** avec filtrage sur les VLANs
- 🚫 **ACL** pour le contrôle d’accès réseau dès la couche Cisco

---

## 🧠 Apports pédagogiques

> Ce projet propose une approche à la fois **pratique et pédagogique** pour appréhender les bases de la **cybersécurité appliquée à l’IoT**. Il constitue une fondation idéale pour explorer des concepts plus avancés tels que la **détection d’intrusion (IDS)** ou la **surveillance réseau** dans un contexte domotique.

---

## 📎 Fichiers inclus

- `rapport.pdf` : Rapport final du projet (85 pages)
- `topologie.pkt` : Fichier Cisco Packet Tracer
- `projet.gns3` : Projet GNS3
- `images.zip` : Dossier d’illustrations du rapport
- `README.md` : Présentation du projet

---

## 🔑 Mots-clés

> **Maison intelligente**, **IoT sécurisé**, **pfSense**, **MQTT (EMQX)**, **TLS/SSL**, **Cisco Packet Tracer**, **GNS3**, **ACL**, **Firewall**, **Simulation réseau**

---
