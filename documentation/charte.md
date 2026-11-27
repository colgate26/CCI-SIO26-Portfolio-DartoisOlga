---
title: Charte graphique - Portfolio Olga Dartois-Stojadinovic
author: Olga Dartois-Stojadinovic
---

# Charte graphique - Portfolio Olga Dartois-Stojadinovic

## 1. Le projet

* **Contexte** : Portfolio d'Olga Dartois-Stojadinovic, étudiante en BTS SIO option SISR en alternance à l'IGBMC.
* **Objectifs** :
  * Présenter le parcours de professionnalisation (formations, expériences, projets) et servir de support aux épreuves E5 et E6.
  * Exposer le projet professionnel : intégrer la police scientifique dans le domaine numérique.
  * Faciliter la prise de contact (recruteurs, jury, écoles).
* **Public visé** : Enseignants et jury BTS SIO, recruteurs IT, écoles/organismes (cybersécurité, police scientifique).
* **Arborescence (7 pages)** : Accueil, Parcours, Projets, Projet atelier 3, Projet atelier 4, Veille technologique, Mentions légales.

---

## 2. Les couleurs

### Palette principale
| Nom              | Code HEX  | Variable CSS           | Rôle                                                     |
| ---------------- | --------- | ---------------------- | -------------------------------------------------------- |
| **Bordeaux**     | `#7B1E3A` | `--couleur-principale` | Titres (`h1`, `h2`), liens, en-tête, boutons secondaires |
| **Jaune beurre** | `#F3D77A` | `--couleur-accent`     | Boutons d'action principaux, repères/accents             |
| **Crème**        | `#FBF6EA` | `--couleur-fond`       | Fond principal des pages                                 |
| **Brun prune**   | `#2A1A24` | `--couleur-texte`      | Texte courant                                            |

### Palette secondaire et fonctionnelle
| Nom                  | Code HEX  | Variable CSS                 | Rôle                                                         |
| -------------------- | --------- | ---------------------------- | ------------------------------------------------------------ |
| **Prune**            | `#4B1D49` | `--couleur-prune`            | Pied de page, titres `h3`, contour de focus                  |
| **Vert olive**       | `#5E6B2E` | `--couleur-olive`            | Icônes de compétences, messages de confirmation              |
| **Bleu ciel**        | `#BEDCEC` | `--couleur-ciel`             | Fond de sections alternées, étiquettes de technologies       |
| **Rose clair**       | `#F8CDD6` | `--couleur-rose`             | Fond de sections alternées, étiquettes de numéros de projet, survol |
| **Taupe**            | `#6E6058` | `--couleur-texte-secondaire` | Texte secondaire (légendes, dates, métadonnées)              |
| **Gris taupe clair** | `#8A7B72` | `--couleur-bordure`          | Bordures des champs de formulaire et éléments d'interface    |
| **Beige filet**      | `#E3D9CF` | `--couleur-filet`            | Filets décoratifs, séparateurs, bordures des cartes          |
| **Blanc**            | `#FFFFFF` | `--couleur-surface`          | Fond des cartes                                              |
| **Rouge alerte**     | `#B3261E` | `--couleur-erreur`           | Messages d'erreur (avec icône et texte)                      |

**Règles d'usage** : Contrastes conformes WCAG AA/AAA. Ne jamais utiliser le jaune beurre en texte sur fond clair. Utiliser le vert olive et le taupe uniquement sur fond crème ou blanc. Ne pas mélanger le rose clair et le bleu ciel dans une même section.

---

## 3. La typographie

### Polices (hébergées localement en `woff2`)
* **Titres et texte courant** : **IBM Plex Sans** (graisses `400` normal et `600` semi-gras) — pile de secours : `"Segoe UI", Roboto, Arial, sans-serif`.

### Échelle typographique
| Niveau           | Balise / Classe | Mobile             | Ordinateur        | Graisse                | Interligne |
| ---------------- | --------------- | ------------------ | ----------------- | ---------------------- | ---------- |
| Titre principal  | `h1`            | 2 rem (32 px)      | 2,75 rem (44 px)  | 600                    | 1,2        |
| Titre de section | `h2`            | 1,5 rem (24 px)    | 2 rem (32 px)     | 600                    | 1,25       |
| Sous-titre       | `h3`            | 1,25 rem (20 px)   | 1,5 rem (24 px)   | 600                    | 1,3        |
| Texte courant    | `p`             | 1 rem (16 px)      | 1,125 rem (18 px) | 400                    | 1,6        |
| Petit texte      | `small`         | 0,875 rem (14 px)  | 0,875 rem (14 px) | 400                    | 1,5        |
| Étiquette        | `.etiquette`    | 0,8125 rem (13 px) | 0,875 rem (14 px) | 400 (mono, majuscules) | 1,4        |

---

## 4. La maquette

**Lien Figma** : [À compléter] (Pages : *01 - Wireframe*, *02 - Maquette UI*, *03 - Prototype*, *Charte graphique*).

### Structure responsive par page
* **En-tête & Pied de page (communs)** : En-tête bordeaux `sticky` (menu burger sur mobile/tablette, horizontal avec sélecteur FR/EN sur ordinateur). Pied de page prune avec filet jaune beurre de 4 px.
* **Accueil (`index.html`)** : Introduction en 1 colonne (mobile/tablette) puis 2 colonnes texte/portrait (ordinateur) ; section « En bref » en 3 blocs empilés puis côte à côte ; bouton contact centré.
* **Parcours (`parcours.html`)** : Présentation texte/illustration (empilés sur mobile, côte à côte dès tablette) ; frise chronologique verticale des formations/expériences ; compétences en 1 colonne (mobile) puis 2 colonnes (tablette/ordinateur).
* **Projets (`projets.html`)** : Grille de 4 cartes projets (1 colonne sur mobile, 2 colonnes sur tablette/ordinateur) + liens vers les ateliers 3 et 4.
* **Ateliers 3 et 4 (`atelier3.html`, `atelier4.html`)** : Gabarit commun. Titre et illustration côte à côte sur ordinateur ; liste d'étiquettes compétences ; liens de téléchargement des documentations en 2 colonnes sur ordinateur.
* **Veille technologique (`veille.html`)** : Projet professionnel (texte/illustration côte à côte sur ordinateur) + grille de notes de veille (1 colonne sur mobile, 2 sur tablette, 3 sur ordinateur).
* **Mentions légales (`mentions-legales.html`)** : Page texte en 1 colonne centrée (`max-width: 70ch`) sur tous les écrans.[cite: 1]