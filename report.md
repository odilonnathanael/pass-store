---
title: "Rapport de laboratoire n°5"
subtitle: "Gestionnaire de mots de passe pass et gestion des configurations avec chezmoi"
author: "Lissombo Ayem"
lang: fr-FR
toc-title: "Table des matières"
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
figureTitle: "Fig."
tableTitle: "Tableau"
lofTitle: "Liste des figures"
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float}
  - \floatplacement{figure}{H}
---

# Objectif

Configurer l’environnement de travail avec le gestionnaire de mots de passe `pass` et l’outil de gestion de configurations `chezmoi`.

# Tâches

1. Installer et configurer `pass`.
2. Intégrer `pass` avec le navigateur Firefox.
3. Manipuler les mots de passe (ajout, consultation, modification).
4. Installer des logiciels supplémentaires.
5. Installer `chezmoi` et créer un dépôt de dotfiles sur GitHub.
6. Connecter le dépôt à son système et appliquer la configuration.
7. Simuler l’utilisation sur une seconde machine (via un utilisateur temporaire).
8. Activer les commits et pushes automatiques.

# Déroulement

## Installation et configuration de `pass`

J’ai installé `pass` et `gopass` (fig. @fig:cp2) :

