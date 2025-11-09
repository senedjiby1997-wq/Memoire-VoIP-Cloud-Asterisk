# 📘 Mémoire VoIP - Cloud - Asterisk sur AWS

Auteur : Djiby SENE
Niveau : Master 2 – Électronique, Systèmes et Télécommunications
Université : UCAO – Unité de Formation et de Recherche en Sciences et Technologies
Année académique : 2024–2025

## 🎯 Objectif du projet

Ce mémoire a pour objectif d’implémenter une solution de communication VoIP complète basée sur le serveur Asterisk, hébergée sur une infrastructure AWS Cloud.
L’étude vise à démontrer comment la virtualisation et le Cloud Computing peuvent améliorer la flexibilité, la sécurité et la scalabilité des systèmes de téléphonie d’entreprise.

### 🧩 Aperçu du mémoire

Le projet explore les concepts fondamentaux de la VoIP, du Cloud Computing, et de la virtualisation, puis met en œuvre une infrastructure de communication IP basée sur Asterisk dans le Cloud.

Étapes principales :

Analyse des technologies VoIP et Cloud

Protocoles utilisés : SIP, RTP, PJSIP

Avantages du Cloud dans les solutions de communication

Mise en place de l’environnement AWS

Création d’une instance EC2 (Ubuntu Server 24.04 LTS)

Configuration du réseau (VPC, sous-réseaux, sécurité)

Installation et configuration d’Asterisk

Version : Asterisk 20.11.1

Configuration des comptes PJSIP, extensions et plans de numérotation

Tests d’appels internes et externes

Intégration et fonctionnalités avancées

Messagerie vocale, mise en attente, transfert d’appel

Conférences audio et gestion des files d’attente

Supervision et gestion de la qualité de service

Analyse des résultats et perspectives

Performances de la solution

Sécurité, résilience et coût d’exploitation

Améliorations possibles : intégration IA, interface web, vidéo-conférence

#### 🏗️ Architecture du projet
Mémoire-VoIP-Cloud-Asterisk/
│
├── docs/                  # Documents et rapports du mémoire
├── config/                # Fichiers de configuration Asterisk (pjsip.conf, extensions.conf)
├── scripts/               # Scripts d’installation et d’automatisation
├── diagrams/              # Schémas réseau et architecture AWS
├── results/               # Résultats des tests et captures d’écran
└── README.md              # Présentation du projet

##### ☁️ Technologies et outils utilisés
Catégorie	Outils / Technologies
Système d’exploitation	Ubuntu Server 24.04 LTS
Serveur VoIP	Asterisk 20.11.1
Cloud Provider	AWS (EC2, VPC, Security Groups, Elastic IP)
Protocole VoIP	SIP, RTP, PJSIP
Langages / Outils	Linux CLI, Vim, SSH, AWS Console
Téléphones IP / Softphones	Zoiper, Linphone
Supervision	Wireshark, sngrep
###### 🧠 Résumé technique

Ce mémoire démontre comment :

Une infrastructure VoIP complète peut être déployée dans le Cloud AWS.

Le serveur Asterisk assure la signalisation SIP et la gestion des appels.

La virtualisation des services de communication réduit les coûts et simplifie la maintenance.

L’utilisation d’AWS EC2 garantit la scalabilité et la disponibilité du service.

###### 📈 Résultats attendus

Appels internes et externes fonctionnels via PJSIP

Voicemail, mise en attente, transfert et conférence opérationnels

Communication stable avec une faible latence

Documentation complète de l’architecture et des configurations

###### 📚 Références principales

Stallings, W. (2013). Foundations of Modern Networking: SDN, NFV, QoE, IoT, and Cloud. Addison-Wesley.

Meggelen, J. Van, Smith, L., & Madsen, J. (2019). Asterisk: The Definitive Guide (5th Edition). O’Reilly Media.

Amazon Web Services. (2023). AWS Architecture Center. https://aws.amazon.com/architecture

RFC 3261 – SIP: Session Initiation Protocol. Internet Engineering Task Force (IETF).

##🧾 Auteur

Djiby SENE
Master 2 – Électronique, Systèmes et Télécommunications
📍 Sénégal
✉️ senedjiby1995@gmail.com
