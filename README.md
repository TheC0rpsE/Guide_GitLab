# ProjetDevWeb

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Projet de développement d'application web

> [!CAUTION]
> Pour le moment on a juste ce repo avec chaqu'un une branch pour développer et la main pour réunir le travail fini

> [!NOTE]
> À définir : charge de travail par personne et qui fait quoi (en attente du sujet)

- [ProjetDevWeb](#projetdevweb)
  - [Utilisation](#utilisation)
    - [Initialisation](#initialisation)
    - [Branch](#branch)
    - [Ajout et valider les modifications](#ajout-et-valider-les-modifications)
    - [Pousser les modifications](#pousser-les-modifications)
    - [Pull Request](#pull-request)
    - [Plus](#plus)
    - [Nommage](#nommage)



## Utilisation

### Initialisation

```shell
git clone https://github.com/TheC0rpsE/ProjetTutore
```

### Branch

Chacun travaillera sur sa branche personnelle, qui aura le nom de chacun, et pourra faire ses tests indépendamment des autres 

```shell
git branch nomDeLaBranche
```

### Ajout et valider les modifications

Après avoir programmé des fonctionnalités sur votre machine vous pouvez mettre le code sur votre branch en ajoutant les fichiers : 

```shell
git add nomDuFichier.extensionDuFichier
```

Vous pouvez soit ajouté un par un les fichiers dont vous avez besoin soit ajouté tous les fichiers d'un coup en faisant :

```shell
git add .
```

Une fois que tous les fichiers voulus on était ajouté, il est nécessaire d'attribuer un message de commit :

```shell
git commit -m "Description des modifications"
```

### Pousser les modifications

Une fois l'ajout des fichiers et le commit effectuer vous pouvez pousser ce commit sur votre branch en effectuant :

```shell
git push origin nomDeLaBranch 
```

### Pull Request

> [!NOTE]
> À rediscuter avec tout le monde sur quand et comment on fait les PR

Pour mettre du code sur la branche principale, vous pouvez depuis votre branch personnel appuyer sur le bouton « Contribute » 
puis sur « Open pull request » vous pourrez ainsi mettre un titre et une description des fonctionnalités que vous ayez développé pour aider la team

### Plus

Voici un aperçu de quleques commande git supplémentaire :

```shell
https://github.com/Thomas141203/GIT-Cheatsheet?tab=readme-ov-file#git-cheatsheet
```

Cette liste n'est pas exhaustive, si besoin voir la doc github sur l'utilisation des commandes git

Pour que l'on se mette d'accord sur la convention de nommage de nos attributs et de nos classes, nous suivrons la notation CamelCase : 

### Nommage

```js
let ceciEstUneVariableJS = 0;
```
