**Nom :** Lemoine

**Groupe :** Groupe 5

**Année :** 1ere

**IUT Le Havre - Cours GIT** 

### Compte-rendu TP1 Introduction GIT

Dans ce TP on apprend à travailler avec git. Et a mettre a jours notre git.


# Compte-rendu TP1 : Introduction à GIT

**Nom :** Lemoine Paul
**Groupe :** [5]  
**Année :** [2024-2025]  

**IUT Le Havre - Cours GIT**

---

## Objectifs du TP

Ce premier TP avait pour but de se familiariser avec l’outil de gestion de version **Git** en local, sans utiliser de dépôt distant comme GitHub. Les objectifs principaux étaient :

- Configurer Git avec une identité (nom et email) et un éditeur de texte.
- Créer un dépôt Git local avec `git init`.
- Ajouter et suivre les modifications d’un fichier texte (`README.md`).
- Comprendre les 3 zones de Git : *Working Directory*, *Staging Area*, *Repository*.
- Versionner un fichier source Java.
- Ignorer les fichiers compilés à l’aide d’un fichier `.gitignore`.

---

## Étapes réalisées

### 1. Configuration de Git

Configuration de l’identité et de l’éditeur avec :

```bash
git config --global user.name "Prénom Nom"
git config --global user.email "email@example.com"
git config --global core.editor nano
