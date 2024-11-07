# 🌐 Mise en place d'un service web entrant 🌐

Ce projet a pour objectif de configurer un hébergement web sécurisé permettant d'héberger plusieurs sites sur une même machine. Le projet inclut la création de sites, l'intégration de bases de données, l'installation de PHP, ainsi que la configuration de certificats HTTPS pour garantir la sécurité des connexions.

## 📑 Table des matières 📑

- [Aperçu du Projet](#-aperçu-du-projet)
- [Fonctionnalités Principales](#-fonctionnalités-principales)
- [Technologies Utilisées](#-technologies-utilisées)
- [Configuration](#-configuration)
- [Problèmes Rencontrés et Solutions](#-problèmes-rencontrés-et-solutions)
- [Remerciements](#-remerciements)

## 🔍 Aperçu du Projet 🔍

Le projet s'articule autour de plusieurs étapes pour configurer un environnement sécurisé de services web :

1. **Création des sites web** : Mise en place des sites et configurations nécessaires avec Apache2.
2. **Intégration d'une base de données (BDD-LAB)** : Utilisation de MariaDB pour gérer la base de données associée au site.
3. **Support PHP** : Installation et configuration de PHP pour permettre des fonctionnalités dynamiques sur les sites.
4. **Certification HTTPS** : Génération et installation de certificats SSL pour sécuriser les connexions.

## 🌟 Fonctionnalités Principales 🌟

- **Hébergement multi-sites** : Hébergement de plusieurs sites web sur une seule machine Debian.
- **Base de données sécurisée** : Utilisation de MariaDB pour stocker les données des sites.
- **Support PHP** : Intégration de PHP pour les pages dynamiques.
- **HTTPS sécurisé** : Configuration de certificats SSL pour sécuriser les connexions aux sites.

## 🛠️ Technologies Utilisées 🛠️

- **Debian** : Système d'exploitation pour héberger les services.
- **Apache2** : Serveur web utilisé pour l'hébergement multi-sites.
- **MariaDB** : Système de gestion de base de données pour les sites.
- **PHP** : Langage de programmation pour les sites dynamiques.
- **OpenSSL** : Génération des certificats SSL pour sécuriser les sites.

## ⚙️ Configuration ⚙️

- **Apache2** : Configuration des fichiers `pro.conf` et autres pour chaque site.
- **Base de données** : Création d’une table spécifique pour le site avec des permissions d'utilisateur.
- **Certificats HTTPS** : Création de certificats SSL et importation dans le navigateur pour des connexions sécurisées.

## 🔧 Problèmes Rencontrés et Solutions 🔧

Certaines difficultés, comme les permissions d'accès et les configurations réseau, ont été résolues en ajustant les règles ACL et en affinant les configurations d'Apache et de la base de données.

## 🙏 Remerciements 🙏

Merci à mes enseignants du lycée Pergaud pour leur soutien et leurs conseils précieux tout au long de ce projet.



![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Apache_HTTP_server_logo_%282019-present%29.svg/1200px-Apache_HTTP_server_logo_%282019-present%29.svg.png)
