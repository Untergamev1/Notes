###  Dev Web

Ceci est une commande :
``` shell
    mkdir 
    test
```

Ceci est du code : 
``` javascript
const test = 'Hello World';
```

``` shel
    mkdir 'Programmation'
    cd 'Programmation'
    code .
````
La commande `git init` permet d'initialiser un dépot Git.
Elle retourne :
```
Initialized empty Git repository in C:/Users/BZ8036/Programmation/.git/
```
Pour vérifier l'état de votre dépot Git utiliser la commande : 
```
git status
```
Pour changer le nom de la branche on fait 
```
git branch -M main
```
La commande `pwd` permet de voir le chemin obsolue d'accès de fichier sur le terminal

La commande `ls -la` permet de regarder les fichiers racine sur lequel est installé `ATTENTION` ne pas supprimer le dossier `git`

```shell
rm -rf .gift/
```
C'est la commande à ne pas faire

commit : c'est pour suivre la modification de fichier, ça veut donc dire qu'il faut faire la commande commit suivante pour ajouter un fichier au suivit :
```
git add test.md
```
et pour enlever le suivit/commit 
```
git rm --cached <file>...
```
Quand on fait un ```.``` ça veut dire que tu prends tout

```
git commit
```
Avant de sauvegarder les modifications, il faut ajouter les modifications que l'on souhaite sauvegarder avec la commande :
```
git add <nom de fichier> .
```
La sauvegarde s'effectue ensuite avec la commande :
```
$ git commit -m "first commit"
```
Le dépot Git ou repository est le dossier qui contient les données que l'on souhaite versionner. On y trouve un dossier cache `.git/`

Commande qui permet de voir l'historique des commits

```
git log 
```

permet de changer de répertoire (si on laisse de base on revient juste dans le répertoire utilisateur)

```
cd
```

Pour revenir en arrière dans le répertoire

```
cd ..
```
Permet de connaître la valeur de tes remotes 
```
git remote -v
```
Permet de supprimer la valeur de tes remotes 
```
git remote rm -v
```

```cat ```c'est une commande qui permet d'afficher le contenue d'un fichier dans le terminal

```| clip``` ça permet de copier le contenue d'un fichier

cat [file name] | clip 
git clone <url_du_depot> (pour copier l'url d'un depot)
