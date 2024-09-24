# Projet Tutore

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Projet Tutoré

> [!NOTE]
> À définir : charge de travail par personne et qui fait quoi 

- [Projet Tutore](#projet-tutore)
  - [Utilisation](#utilisation)
    - [Initialisation](#initialisation)
    - [Branch](#branch)
    - [Ajout et valider les modifications](#ajout-et-valider-les-modifications)
    - [Pousser les modifications](#pousser-les-modifications)
    - [Pull Request](#pull-request)
    - [Plus](#plus)
  - [Bonne Pratique](#bonne-pratique)
    - [Nommage](#nommage)



## Utilisation

### Initialisation

Cette première commande git permet de cloner un repository déjà créé ce qui va être notre cas pour ce projet : 

```shell
git clone https://github.com/TheC0rpsE/ProjetTutore
```

### Branch

Chaque membre doit travailler sur une propre branche pour éviter des conflits. Créez une nouvelle branche avec comme nom quelque chose de court et explicite sur lequelle vous allez travailler :

```shell
git branch feature/login
```

### Ajout et valider les modifications

Après avoir effectué des modifications ou ajouté des fonctionnalités, il est nécessaire d'ajouter les fichiers modifiés ou créés. Vous pouvez les ajouter un par un :

```shell
git add nomDuFichier.extensionDuFichier
```

Vous pouvez soit ajouté un par un les fichiers dont vous avez besoin soit ajouté tous les fichiers d'un coup en faisant :

```shell
git add .
```

Une fois que tous les fichiers voulus on était ajouté, il est nécessaire d'attribuer un message de commit qui est très important pour comprendre si il y a un bugs ce qu'il c'est passé et qu'elle ajout vous avez fait :

```shell
git commit -m "Description des modifications"
```

### Pousser les modifications

Une fois l'ajout des fichiers et le commit effectuer vous pouvez pousser ce commit sur votre branch en effectuant :

```shell
git push origin feature/login 
```

### Pull Request

Pour mettre du code sur la branche principale, vous pouvez depuis votre branch personnel appuyer sur le bouton « Contribute » 
puis sur « Open pull request » vous pourrez ainsi mettre un titre et une description des fonctionnalités que vous ayez développé pour aider la team.
Les PR seront soumis à 3 administrateurs ici : Alexandre, Garance et Bastien qui valideront la fusion de votre branche avec le main.

### Plus

Voici un aperçu de quleques commande git supplémentaire :

```shell
https://github.com/Thomas141203/GIT-Cheatsheet?tab=readme-ov-file#git-cheatsheet
```

Cette liste n'est pas exhaustive, si besoin voir la doc github sur l'utilisation des commandes git

## Bonne Pratique
### Nommage

Pour nommer vos variable avec de bonne convention nous utiliserons le snake_case qui se resout a ce type de nommage : 

```js
let ceci_est_une_variable = 0;
```
> [!NOTE]
> À définir : nommage pour les fonctions et les classes.
