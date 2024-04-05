# GIT CHEAT SHEET       ![curl -o badge.svg](https://img.shields.io/badge/GIT%20%20-orange?style=for-the-badge&logo=git)
## Configuration :  

```git config --global user.name "pseudo"```

```git config --global user.email "tonemail@macaroni.fr"```

```git config --global core.editor subl```

```git config --global merge.tool filemerge```

## Lister les branches :

```git branch -a```

```*```sur la branche courante.

## Créer une branche

```git branch``` nom_de_ma_branch_nouvelle

```git checkout``` nom_de_ma_branch_nouvelle

```git checkout -b``` nom_de_ma_branch_nouvelle


```git init``` : Traquage du dossier + creation d'un .git

```git add``` : Ajouter au staging

```git clone``` : Commande utilisée pour la vérification des dépôts.

```git commit -m "Décrire le commit"``` : Permet de valider les modfications apportées.

```git status``` :  Vérifie l'état du dépot local

```git push``` : Ajoute les contenus d'un dépôt local vers un depot distant

```git switch (branch)``` : Changer de branche

```git remote -v``` : Cette commande est utilisée pour lister toutes les 'remote' configurations de votre dépôt Git local

```git remote add``` : Créer la liason le dépôt local et le depot distant

```git pull``` : Récupère les nouvelles mise à jour du depot distant sur le depot local


```git remote set-url depot_distant``` : Utilisée pour changer l'URL du depot distant

```git merge``` : Fusion de la branche que je veux ramener à la mienne

```git diff``` : Cette commande permet de détecter rapidement les erreurs et de suivre facilement les bonnes évaluations

```git tag 1.1.0 <insert-commitID-here>``` : Permet des commits spécifiques.

```git log``` L'éxécution de cette commande génère le log d'une branche.

```git reset```--hard HEAD : Pour réinitialiser l'index et le répertoire de travail à l'état du dernier commit.

```git rm``` : Permet de supprimer un ou plusieurs fichiers ou dossiers.

```git stash``` : Aide à enregistrer les changements qui ne doivent pas être 'commit' immédiatement.

```git show``` : Pour afficher des informations ssur tout fichier git.

```git grep "www.hostinger.com"``` : Permet de chercher des mots et/ou des expressions.

```working directory``` : Ce que l'on voit dans la branche actuelle.

### ⚠️Toujours effectuer un commit avant de push/pull ou changer de branche


### 🚨Staging area : 
C'est la zone qui permet d'ajouter du changement.