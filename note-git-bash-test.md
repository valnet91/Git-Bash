
- [Pré-requis à l'utilisation de Git Bash](#Pré-requis-à-l-utilisation-de-Git-Bash)
  - [Les 3 langages qui nous utiliserons dans le terminal Git Bash.](#Les-3-langages-qui-nous-utiliserons-dans-le-terminal-Git-Bash.)
  - [Git Bash](#Git-Bash)
  - [Le terminal](#Le-terminal)
  - [Le Glossaire de Bash dans Git](#Le-Glossaire-de-Bash-dans-Git)
  - [Le Glossaire de Git](#Le-Glossaire-de-Git)
# Pré-requis à l'utilisation de Git Bash
## Les 3 langages qui nous utiliserons dans le terminal Git Bash.

### 1/    Bash exemple:  `mkdir Nom_Du_Repertoire`

### 2/    Git exemple:  `git commit -m \"Message important du commit\"`

### 3/    GH exemple:  `gh repo create  Nom_Du_Repertoire --public`

## Git Bash

## Le terminal

### 2/ Le terminal de Windows

**`wt.exe`** Terminal Preview (test) & Windows Terminal (production)

## Le Glossaire de Bash dans Git

### *<small> Logiciel GNU</small>* 

### ✔ Commande : pwd

```shell
$ pwd puis Entrée
```          

### ✔ Commande : ls

```shell
$ ls puis Entrée
```          

### ✔ Commande : ls -ah

```shell
$ ls -ah puis Entrée
```          

### ✔ Commande : rm delete (shell)

```shell
$ rm -d nom_du_repertoire puis Entrée
```          

### ✔ Commande : rm delete

```shell
$ rm -d nom_du_fichier puis Entrée
```          

### ✔ Commande : touch

```shell
$ touch nom_du_fichier puis Entrée
```          

## Le Glossaire de Git

### ✔ Commande :  git

`git`  Préfixe des commandes git

```shell
$git --help
```  

### ✔ Commande :  init

`init`  initialiser un dépot en local (le client)

Exemple: ```shell
$git init    
```  

### ✔ Commande :  add

`add`  ajoute vos fichiers à l'index de git en local (le client)

Exemple: ```shell
git add nom_du_fichier
```  

>>>Avant d'utiliser cette commande vous pouvez faire un `git status` permet de voir si des modifications peuvent être `commit`

### ✔ Commande :  commit

`commit`  stage vos fichiers en local (le client) -m "Message de vos modifications"

```shell
git commit -m "Votre message pour indiquer vos modifications à l'équipe.
```  

- 23-May-2022/15:52:08+2:00 23-May-2022/15:52:08.588+2:00