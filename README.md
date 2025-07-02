# Plateforme de Pré-Enrôlement - Carte Jeune Biométrique (MINJEC)

Développement d'une plateforme web sécurisée et performante pour le pré-enrôlement des jeunes à la carte biométrique, commandée par le Ministère de la Jeunesse et de l'Éducation Civique (MINJEC) du Cameroun.

---

## 📝 Contexte du Projet

Ce projet stratégique a été réalisé au sein d'ITGStore Consulting pour le compte du MINJEC. L'objectif était de moderniser et de centraliser le processus d'inscription à la carte jeune en créant une porte d'entrée numérique unique. La plateforme de pré-enrôlement constitue le premier maillon d'un écosystème digital plus large, visant à faciliter l'accès des jeunes aux services gouvernementaux.

> **Note de confidentialité :** En raison de la nature gouvernementale et sensible de ce projet, le code source est strictement confidentiel et ne peut être partagé. Ce document a pour but de présenter en détail l'architecture technique, les fonctionnalités et mes contributions en tant que Développeur Full Stack.

---

## ✨ Fonctionnalités Clés de la Plateforme

*   **Parcours de Pré-enrôlement Intuitif :** Un formulaire multi-étapes, développé avec Vue.js 3, guide l'utilisateur dans la saisie de ses informations personnelles.
*   **Interface Réactive et Moderne :** L'interface, construite avec Tailwind CSS et la librairie de composants Element Plus, offre une expérience utilisateur fluide et accessible sur tous les supports (desktop, tablette, mobile).
*   **Synchronisation Automatisée :** Les données collectées sont transmises de manière sécurisée et instantanée à la plateforme d'enrôlement principale via une API REST.
*   **Espace Utilisateur (Notion) :** Possibilité pour les jeunes de suivre l'état d'avancement de leur demande.
*   **Sécurité Renforcée :** Protection contre les vulnérabilités courantes (injection SQL, XSS) et gestion sécurisée des données personnelles conformément aux standards.

---

## 🏛️ Architecture et Interconnexion des Systèmes

Le défi majeur de ce projet était de concevoir un système capable de communiquer de manière fiable avec d'autres plateformes gouvernementales. J'ai conçu et développé une API REST qui sert de pont entre trois systèmes distincts :

1.  **La Plateforme de Pré-enrôlement**.
2.  **La Plateforme d'Enrôlement** .
3.  **L'Observatoire National de la Jeunesse (ONJ)**.



## 💻 Technologies & Outils

| Catégorie             | Technologies / Outils                                      |
| --------------------- | ---------------------------------------------------------- |
| **Backend**           | **Laravel 11**, PHP 8.2+, API RESTful                      |
| **Frontend**          | **Vue.js 3** (Composition API), **TypeScript**, **Inertia.js**, **Tailwind CSS**, Element Plus, HTML5 |
| **Base de Données**   | **PostgreSQL**, SQL                                        |
| **DevOps & Infra.**   | Apache, Ubuntu, GitLab (CI/CD notions), Déploiement sur Cloud Privé |
| **Outils**            | Insomnia (Test d'API), Git, NPM, Composer                  |

---

## 🚀 Mes Contributions en tant que Développeur Full Stack

En tant que développeur principal sur ce projet, j'ai eu la responsabilité de :

1.  **Développement Full Stack de la Plateforme :** Prise en charge complète du développement, du frontend avec Vue.js 3 à la logique backend avec Laravel 11.
2.  **Conception et Développement des API :** Création de l'architecture des API REST pour garantir une communication sécurisée et performante entre les différentes plateformes gouvernementales.
3.  **Intégration Frontend-Backend :** Utilisation d'**Inertia.js** pour créer une Single Page Application (SPA) monolithique, combinant la puissance de Laravel en backend et la réactivité de Vue.js en frontend sans la complexité d'une gestion d'API séparée pour l'application elle-même.
4.  **Modélisation et Gestion de la Base de Données :** Conception du schéma de la base de données relationnelle sous **PostgreSQL** et écriture des migrations pour assurer l'intégrité et la cohérence des données.
5.  **Mise en place de l'Environnement de Développement :** Configuration du dépôt **GitLab** et gestion des branches fonctionnelles pour un développement collaboratif et organisé.
6.  **Déploiement :** Participation active au déploiement de la solution sur un serveur cloud privé sous Ubuntu/Apache.

---

## Auteur

*   **Idriss Cabrel MBIAPO NZEPA**
*   [Profil LinkedIn]
*   [Profil GitHub]
