# Answers of Dennis Marotta dennismarotta

## Basics

### Task 1

Dans le répertoire, on trouve un dossier .git , img et un fichier answer.md. Answer.md sert a répondre les questions du laboratoire. le dossier .git conserve l'historique des différentes version du projet. Le dossier img permet de stocker des fichiers images.

### Task 2

Dans le git status, le fichier README.me a été ajouté dans les untracked.files. Le git log --online a permis de donner un aperçu simplifié de l'historique des commits. 

### Task 3

Le fichier README.md est un nouveau fichier dans la staging area et n'est plus dans les untracked files.

### Task 4

le status montre qu'il y a le fichier README.md qui est modifié et n'a pas été mis à jour dans la staging area.

### Task 5

première ligne : le première chaine de caractère est l'identifiant du commit, le head et le main montre que le commit est pointé par head et head pointe la branche main, donc c'est le dernier commit. Le message qui montre le fichier README.md a été ajouté.

Le git log --online indique le dernier commit crée dans le main (cfe8766) et le seconde ligne indique le premier commit dans le (origin/main).

### Task 6

En effectuant checkout sur le initial commit, le dossier repo est revenu dans l'état quand le initial commit a été crée. C'est-à-dire, avec le dossier img et .git ainsi que le fichier answer.md.

En revenant, dans le dernier commit avec checkout, le fichier README.md a été ajouté.

### Task 7

1: c'est le nom de la branche

2: c'est l'indentifiant du commit

3 : indique que la branche feature-auth a été merger dans la branche de développement 

4 : c'est le nom et l'email de la personne qui a mergé les fichiers

5 : c'est la version du projet

6 : c'est un merge, c'est-à-dire qu'on rassemble des fichiers

7 : c'est une branche de développment pour ajouter une feature

8 : dernière version du main

9 : c'est un branche qui permet de développer en parrallèle

10 : c'est l'initial commit, première version du projet



![Gitgraph](img/gitgraph.svg)