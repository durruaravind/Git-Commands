Commandes Git
============

## Versions traduites
- [Versão em português](READMEpt.md)
- [Versión en español](READMEes.md)
- [Türkçe versiyon](READMEtr.md)
- [Version Française]'READMEfr.md)

___

_Une liste de mes commandes Git couramment utilisées_

*Si vous êtes intéressé par mes alias Git, jetez un œil à mon `.bash_profile`, trouvé ici : https://github.com/joshnh/bash_profile/blob/master/.bash_profile*

--

### Obtenir et Créer des projets

| Command | Description |
| ------- | ----------- |
| `git init` | Initialiser un dépôt Git local |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Créer une copie locale d'un référentiel distant |

### Instantané de base

| Command | Description |
| ------- | ----------- |
| `git status` | Vérifier l'état |
| `git add [file-name.txt]` | Ajouter un fichier à la zone de préparation |
| `git add -A` | Ajouter tous les fichiers nouveaux et modifiés à la zone de préparation |
| `git commit -m "[commit message]"` | Valider les modifications |
| `git rm -r [file-name.txt]` | Supprimer un fichier (ou un dossier) |

### Branchement et Fusion

| Command | Description |
| ------- | ----------- |
| `git branch` | Lister les branches (l'astérisque indique la branche actuelle) |
| `git branch -a` | Lister toutes les succursales (locales et distantes) |
| `git branch [branch name]` | Créer une nouvelle branche |
| `git branch -d [branch name]` | Supprimer une branche |
| `git push origin --delete [branch name]` | Supprimer une branche distante |
| `git checkout -b [branch name]` | Créer une nouvelle branche et basculer vers celle-ci |
| `git checkout -b [branch name] origin/[branch name]` | Cloner une branche distante et basculer vers celle-ci |
| `git branch -m [old branch name] [new branch name]` | Renommer une branche locale |
| `git checkout [branch name]` | Passer à une branche |
| `git checkout -` | Basculer vers la dernière branche vérifiée |
| `git checkout -- [file-name.txt]` | Ignorer les modifications apportées à un fichier |
| `git merge [branch name]` | Fusionner une branche dans la branche active |
| `git merge [source branch] [target branch]` | Fusionner une branche dans une branche cible |

### Partage et mise à jour des projets

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Poussez une branche vers votre référentiel distant |
| `git push -u origin [branch name]` | Pousser les modifications vers le référentiel distant (et mémoriser la branche) |
| `git push` | Pousser les modifications vers le référentiel distant (branche mémorisée) |
| `git push origin --delete [branch name]` | Supprimer une branche distante |
| `git pull` | Mettre à jour le référentiel local vers le dernier commit |
| `git pull origin [branch name]` | Extraire les modifications du référentiel distant |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Ajouter un référentiel distant |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Définir la branche d'origine d'un référentiel sur SSH |

### Inspection et Comparaison

| Command | Description |
| ------- | ----------- |
| `git log` | Afficher les modifications |
| `git log --summary` | Afficher les modifications (détaillées) |
| `git log --oneline` | Afficher les modifications (brièvement) |
| `git diff [source branch] [target branch]` | Prévisualiser les modifications avant de fusionner |


