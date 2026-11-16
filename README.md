# formation-it-cyber-cloud-ia-6mois
  Programme pratique intensif sur 6 mois (24 semaines) - Réseaux, Linux, Cyber/SOC, Azure, DevOps &amp; IARESEAUX-RESEAUX-INFORMATIQUES/
│
├── README.md
│
├── 01-FONDAMENTAUX-RESEAUX/
Les fondamentaux des réseaux informatiques

Un réseau informatique est un ensemble d'équipements interconnectés permettant d'échanger des informations et de partager des ressources.les Principaux équipements réseau: 

Équipement

Fonction

Routeur : Assure la communication entre différents réseaux.

Switch : Connecte plusieurs équipements au sein d'un réseau local.

Hub : Diffuse les données vers tous ses ports.

Point d'accès Wi-Fi : Permet la connexion sans fil.

Modem : Assure l'interconnexion avec un réseau d'accès opérateur.

Pare-feu : Contrôle et filtre le trafic réseau.

Serveur : Fournit des services aux autres équipements.

Types de réseaux

LAN : Local Area Network, réseau local.

WAN : Wide Area Network, réseau étendu.

MAN : Metropolitan Area Network, réseau métropolitain.

WLAN : Wireless Local Area Network, réseau local sans fil.

PAN : Personal Area Network, réseau personnel.

Notions essentielles

Adresse IP : identifie une interface sur un réseau IP.

Adresse MAC : identifiant de couche liaison associé à une interface réseau.

Masque de sous-réseau : permet de déterminer la partie réseau et la partie hôte d'une adresse IPv4.

Passerelle par défaut : permet de joindre les réseaux extérieurs au réseau local.

DNS : traduit les noms de domaine en adresses IP.

DHCP : attribue automatiquement les paramètres de configuration IP.
├── 02-MODELE-OSI/
Le modèle OSI

Le modèle OSI (Open Systems Interconnection) est un modèle conceptuel qui décrit les communications réseau à travers sept couches.

Couches

7 Application :Services réseau destinés aux applications. HTTP, DNS, SMTP

6 Présentation : Formatage, encodage et chiffrement des données.TLS, formats de données

5 Session : Gestion des sessions de communication.Gestion des sessions

4 Transport : Communication de bout en bout et transport des données. TCP, UDP

3 Réseau Adressage logique et routage.IPv4, IPv6, ICMP

2 Liaison de données Communication sur le réseau local et adressage MAC. Ethernet, ARP, Wi-Fi

1 Physique : Transmission des bits sur le support physique. Câbles, fibre, signaux radio Les unités de données (PDU)

Couche

Unité de données

Application à Transport

Données / segments selon le contexte

Transport

Segment TCP ou datagramme UDP

Réseau

Paquet IP

Liaison

Trame

Physique

Bits

À retenir

Le modèle OSI permet de comprendre où intervient chaque protocole et de localiser plus facilement les problèmes de communication réseau.
├── 03-MODELE-TCP-IP/
Le modèle TCP/IP

Le modèle TCP/IP représente l'architecture de communication utilisée sur Internet et dans la majorité des réseaux IP.

Il comporte quatre couches.

Couche TCP/IP

Correspondance OSI

Exemples

Application

5, 6 et 7

HTTP, HTTPS, DNS, DHCP, SSH

Transport

4

TCP, UDP

Internet

3

IPv4, IPv6, ICMP

Accès réseau

1 et 2

Ethernet, Wi-Fi

Différences entre OSI et TCP/IP

OSI est principalement un modèle de référence conceptuel.

TCP/IP est une architecture de protocoles réellement utilisée dans les communications réseau.

OSI possède sept couches, tandis que TCP/IP en possède quatre dans sa représentation classique.

Encapsulation et désencapsulation

Lorsqu'un ordinateur envoie des données :

Les données sont produites par l'application.

La couche transport ajoute ses informations (TCP ou UDP).

La couche Internet ajoute les informations IP.

La couche accès réseau ajoute les informations de trame.

Les bits sont transmis sur le support physique.

À la réception, le processus inverse permet de retrouver les données originales.
├── 04-PROTOCOLES-RESEAU/
 Les principaux protocoles réseau

Protocole

Fonction

Port

HTTP

Communication Web non chiffrée

TCP 80

HTTPS

Communication Web sécurisée

TCP 443

DNS

Résolution des noms de domaine

UDP/TCP 53

DHCP

Attribution automatique des adresses IP

UDP 67/68

FTP

Transfert de fichiers

TCP 20/21

SSH

Administration distante sécurisée

TCP 22

Telnet

Administration distante non chiffrée

TCP 23

SMTP

Envoi de courriers électroniques

TCP 25

POP3

Réception des courriers électroniques

TCP 110

IMAP

Accès aux courriers électroniques

TCP 143

SNMP

Supervision réseau

UDP 161/162

NTP

Synchronisation de l'heure

UDP 123

TCP et UDP

TCP (Transmission Control Protocol) :

Orienté connexion.

Assure la livraison fiable et ordonnée des données.

Utilise des mécanismes de contrôle et de retransmission.

UDP (User Datagram Protocol) :

Sans établissement préalable de connexion.

Fonctionnement plus simple.

Ne garantit pas la livraison ni l'ordre des datagrammes.
├── 05-WIRESHARK/
Introduction à Wireshark

Wireshark est un outil d'analyse de protocoles réseau permettant de capturer, examiner et interpréter les paquets échangés entre différents équipements.

Objectifs

Observer les communications réseau en temps réel.

Identifier les protocoles utilisés.

Examiner les adresses IP et MAC.

Comprendre les échanges TCP et UDP.

Analyser les requêtes DNS.

Diagnostiquer certains problèmes de connectivité.

Développer des compétences en analyse réseau et cybersécurité.

Installation

Téléchargement officiel :

https://www.wireshark.org/download.html

Prérequis :

Windows 10/11.

Wireshark.

Npcap.

Terminal CMD ou PowerShell.

Connexion réseau.

Les principales zones de Wireshark

Zone

Fonction

Packet List

Liste des paquets capturés.

Packet Details

Détails des protocoles et champs du paquet sélectionné.

Packet Bytes

Contenu brut du paquet en hexadécimal et ASCII.

Types de filtres

Capture Filter : filtre les paquets avant ou pendant leur capture.

Display Filter : filtre les paquets déjà capturés pour faciliter leur analyse.
│   ├── TP-01-ICMP.md
│   ├── TP-02-DNS.md
│   ├── TP-03-TCP-HANDSHAKE.md
│   └── captures/
│
└── 06-PREPARATION-CCNA/
