
- [Pré-requis à l'utilisation de Git Bash](#Pré-requis-à-l-utilisation-de-Git-Bash)
  - [Les 3 langages Git Bash, qui nous utiliserons dans le terminal. Ici wt.exe (Windows terminal)](#Les-3-langages-Git-Bash,-qui-nous-utiliserons-dans-le-terminal.-Ici-wt.exe-(Windows-terminal))
  - [Git Bash](#Git-Bash)
  - [Le terminal](#Le-terminal)
  - [Le Glossaire de Bash dans Git](#Le-Glossaire-de-Bash-dans-Git)
  - [Le Glossaire de Git](#Le-Glossaire-de-Git)
  - [Exemples concrèts (production) d'utilisation de Git](#Exemples-concrèts-(production)-d-utilisation-de-Git)
# Pré-requis à l'utilisation de Git Bash
## Les 3 langages Git Bash, qui nous utiliserons dans le terminal. Ici wt.exe (Windows terminal)

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

- Permet de mettre à jour la date/heure  le nom_du_fichier. touchER, touch = contact

## Le Glossaire de Git

### ✔ Commande :  git

`git`  Préfixe des commandes git

```shell
$git --help
```  

### ✔ Commande :  init

`init`  initialiser un dépot en local (le client)

```shell
$git init
```  

### ✔ Commande :  add

`add`  ajoute vos fichiers à l'index de git en local (le client)

```shell
git add nom_du_fichier
```  

>>>Avant d'utiliser cette commande vous pouvez faire un `git status` permet de voir si des modifications peuvent être `commit`

### ✔ Commande :  commit

`commit`  stage vos fichiers en local (le client) -m "Message de vos modifications"

```shell
git commit -m "Votre message pour indiquer vos modifications à l'équipe.
```  

### ✔ Commande : push

`push`  transfert vos fichiers du local (le client) vers le dépôt Github.

> Permet de sauvegarder votre projet sur github et ajoute le versonning des modifications effectuées.

### ✔ Commande : echo

```shell
$ echo "votre texte" > nom_du_fichier puis Entrée
```          

Création d'un fichier et insertion de "Votre Texte" Vous avez, également, la commande ```echo "votre texte" >> nom_du_fichier```

> 😎 Utiliser ```>>``` pour ajouter (append) à la suite de "ancien texte", "votre texte", évite de supprimer les anciennes données. 

### ✔ Commande : log

```shell
$ git log Entrée
```          

Affiche la liste de toutes les dernières actions faites (les commits) pour git. (Attention la liste peut-être longue.)

> pour sortir de cette commande taper : q, vous reviendrez au prompt (invite de commande) avec le symbole $, ainsi vous pourrez saisir une nouvelle commande.

### ✔ Commande : log -10

```shell
$ git log -10 Entrée
```          

Affiche la liste des  10 dernières actions faites pour git. <br/>git log -5 pour les 5 dernières

> flèche du bas  pour faire défiler les logs. `end` en bas du filement taper: q, pour revenir au prompt (invite de commande) $.

### ✔ Commande : log -oneline

```shell
$ git log --oneline puis Entrée
```          

Affiche la liste de toutes les dernières actions (de façon simplifié) faites pour git, avec l'option  --oneline. (Attention la liste peut-être longue.)

### ✔ Commande : log -p nom_du_fichier

```shell
$ git  log -p nom_du_fichier puis Entrée
```          

Affiche les modifications des 2 derniers commit sur nom_du_fichier. Historique des modifications.

> Permet de voir rapidement les lignes modifiées.

### ✔ Commande : log -p --oneline nom_du_fichier

```shell
$ git  log -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications des 2 derniers commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

### ✔ Commande : log -n1 -p --oneline nom_du_fichier

```shell
$ git  log -n1 -p --oneline nom_du_fichier puis Entrée
```          

Affiche les modifications le dernier `-n1` commit sur nom_du_fichier. Historique des modifications. --oneline réduit un peu la taille des infos en sortie

> Permet de voir rapidement les lignes modifiées, sur le dernir commit car  `-n1` a été ajouté à notre ligne de commande.

## Exemples concrèts (production) d'utilisation de Git

### des exemples de Git

- 27-May-2022/8:09:50.148+2:00 JJ V