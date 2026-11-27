---
title: Technique portfolio
author: Olga Dartois-Stojadinovic
creator: Typora inc.
subject: Atelier de professionnalisation 1 - Portfolio
header:
footer: ${title} - ${author} - Page ${pageNo} / ${totalPages}

---

# Projet Professionnel 1 | Portfolio - Technique

Ce document présente les technologies utilisées, l'architecture du site et l'environnement de développement afin de permettre à tout technicien de reprendre le projet facilement.

## 1. Technologies utilisées

| Catégorie         | Outil              | Version  | Utilité                             |
| :---------------- | :----------------- | :------- | :---------------------------------- |
| **Langages**      | HTML               | 5        | Structure des pages                 |
|                   | CSS                | 3        | Mise en forme et responsive         |
|                   | JavaScript         | ES6+     | Menu mobile et changement de langue |
| **Développement** | WSL (Ubuntu)       | 2.7.14.0 | Environnement Linux sous Windows    |
|                   | Apache             | 2.4.66   | Serveur web local                   |
|                   | Visual Studio Code | 1.115.0  | Éditeur de code                     |
|                   | Git / GitHub       | 2.53.0   | Sauvegarde et suivi des versions    |
|                   | Firefox            | 160.0.1  | Tests d'affichage et débogage       |

## 2. Architecture et environnement de développement

### 2.1. Arborescence du projet

```text
portfolio/
├── documentation/
│   ├── charte.md
│   ├── contenu.md
│   ├── technique.md
│   └── medias/              # Illustrations et schémas de la documentation
└── html/
    ├── assets/
    │   ├── css/
    │   │   └── style.css    # Feuille de style unique
    │   ├── js/
    │   │   └── main.js      # Scripts du site
    │   ├── fonts/           # Polices locales (IBM Plex Sans / Mono en woff2)
    │   └── img/             # Images, icônes et illustrations du site
    ├── en/                  # Version anglaise des 7 pages
    ├── index.html           # Accueil
    ├── parcours.html        # Formations, expériences et compétences
    ├── projets.html         # Réalisations techniques
    ├── atelier3.html        # Projet atelier 3
    ├── atelier4.html        # Projet atelier 4
    ├── veille.html          # Veille technologique
    └── mentions-legales.html # Mentions légales
```

### 2.2. Reconstruction de l'environnement

1. Système et serveur local : Installer WSL sous Windows 11 avec le serveur web Apache configuré sur `/var/www/html/portfolio/html/`.
2. Récupération du code : Cloner le dépôt GitHub dans `/var/www/html/portfolio/`.
3. Édition et tests : Ouvrir le dossier avec Visual Studio Code (extension WSL) et tester le rendu via `http://localhost/portfolio/html/` sur Firefox.

## 3. Environnement de Production

***À REMPLIR EN FIN DE PROJET***

## 4. Procédure de Transfert

***À REMPLIR EN FIN DE PROJET***