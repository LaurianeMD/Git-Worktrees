# exercice3
# Git Worktrees : Concept et Utilisation

Les Git worktrees permettent de gérer plusieurs répertoires de travail attachés à un seul dépôt. Cela est utile pour travailler sur différentes branches ou tâches simultanément sans avoir à changer fréquemment de branche dans un seul répertoire de travail. Ce README fournit une explication détaillée des Git worktrees avec des exemples pratiques.

## Table des Matières

1. [Introduction](#introduction)
2. [Configuration d'un Dépôt](#configuration-dun-dépôt)
3. [Création et Utilisation des Worktrees](#création-et-utilisation-des-worktrees)
4. [Lister et Supprimer les Worktrees](#lister-et-supprimer-les-worktrees)
5. [Nettoyage](#nettoyage)

## Introduction

Les Git worktrees sont une fonctionnalité qui permet d'avoir plusieurs répertoires de travail pour un seul dépôt. Cela vous permet de travailler sur différentes branches ou fonctionnalités en même temps sans avoir à changer fréquemment de branche. 

## Configuration d'un Dépôt

1. **Initialiser un Nouveau Dépôt**

   ```bash
   mkdir git-worktree-exercise
   cd git-worktree-exercise
   git init
