# Q&R

## algorithmique

q différence entre opérandes et opérateurs ?
r opérandes : objets avec lesquels ont travail
  opérateurs : opérations qu'on fait sur les objets

q combien d'opérateurs arithmétiques existent-ils ?
r 5 en standard et 2 optionnels

q combien d'opérateurs d'affectation existent-ils ?
r un seul (le =)

q quel type de valeur / données les opérateurs de comparaison renvoient-ils ?
r un booléen

q quelle est la différence entre = et == ?
r = est l'opérateur d'affectation (affirmation)
  == est un opérateur de comparaison (interrogation)

q quels sont les éléments qui permettent de créer un algorithme sous forme de diagramme / schéma ?
r 1. cercle : afficher des valeurs
  2. rectangle : effectuer une action (par exemple une affectation)
  3. losange : poser une question fermée / vérfier une condition / comparer des valeurs

q à quoi sert github ?
r - portfolio
  - collaborer
  - sauvegarder
  - mise en prod (MEP) / deploy

## théorie des clés publiques et privés de l'algorithme RSA

q À quoi sert l'algorithme RSA ?
r Échanger des données de manière sécurisée

q À quoi sert une clé publique ?
r Chiffrer des données que seule la clé privée associée peut déchiffrer.

## github

q À qui appartient github ?
r Microsoft

## git

q à quoi sert git ?
r - travailler en équipe
  - sauvegarder son travail
  - publier son travail sur un site comme github ou autre
  - publier son travail sur en production
  - travailler seul mais avec plusieurs postes
  - suivre l'avancement du travail
  - filet de secours (c-à-d récupération d'un code fonctionnel)

q comment créer une clé ssh ?
r avec windows, utiliser la commande `ssh-keygen -t rsa -b 4096`

q quelles sont les étapes pour créer un repo ?
r 1. avoir un compte github (ou autre site) et une clé ssh
  2. créer un dossier qui contient le code du projet
  3. créer des fichiers et écrire du code
  4. initialiser un repo local avec la commande `git init`
  5. copier des fichiers dans la zone de staging (déposer sur la scène) avec la commande `git add`
  6. enregistrer un commit (prendre un photo) avec la commande `git commit` et rédiger une description (une légende)
  7. faire le lien entre le repo local et le repo distant (remote), on utilise la commande `git remote add origin [url_ssh_github]`
  8. envoyer les commits sur github avec la commande `git push`

## git

q à quoi servent les branches ?
r elles permettent de travailler dans une branche sans modifier les autres

q comment savoir dans quelle branche on est ?
r commmande `git branch`

q comment créer une nouvelle branche ?
r git branch nom_branche

## git merge

q à quoi sert git merge ?
r ça sert à fusionner (importer) le code d'une autre branche dans la branche actuelle

## git checkout

q comment faire pour changer de (c-à-d basculer vers un autre) branche ?
r commande `git checkout [nom_branche]`

q comment voir tous les commits ?
r commande `git log`

## opérateurs logiques

q quels sont les opérateurs logiques les plus courants ?
r AND ET &&, OR OU ||, NOT NON !

q écrivez la table de vérité de l'opérateur AND ET &&
r 

A | B | A && B
--+---+-------
F | F | F
T | F | F
F | T | F
T | T | T

q écrivez la table de vérité de l'opérateur OR OU ||
r 

A | B | A || B
--+---+-------
F | F | F
T | F | T
F | T | T
T | T | T

q écrivez la table de vérité de l'opérateur NOT NON !
r 

A | !A
--+---
F | T
T | F

## algorithmique

q qu'est-ce qu'une expression ?
r c'est du code qui, une fois exécuté, se réduit à une seule valeur

q à quel type de bloc correspond un if ?
r un if est un bloc conditionnel

## wamp

q qu'est ce que wamp ?
r w = windows
  a = apache2
  m = mariadb (ex mysql)
  p = php

q qu'est-ce qu'une DLL ?
r DLL = Dynamic Link Library
  c'est du code écrit par un tiers, qui est prêt à être utilisé

q qu'est-ce que composer ?
r c'est l'outil qui permet d'installer des packages (des extentions) php

## diff (kdiff3, meld, windiff)

q à quoi sert un outil de diff ?
r comparer deux codes ou commit
  fusionner deux codes

## github

q comment ajouter un collaborateur dans un repo ?
r aller dans settings > collaborateur > add people > taper le nom du collaborateur

q comment récupérer un repo depuis github ?
r copier le lien SSH du repo et lancer la commande `git clone [lien_ssh]`

q comment voir le lien du repo distant ?
r commande `git remote -v`

## git conflit et rebase

q que faut-il faire avant de commencer à modifier son code ?
r
  1. `git checkout main` pour aller dans la branche main
  2. `git pull` pour récupérer les mises à jour
  3. `git checkout [ma_branche]` pour aller dans sa branche de travail
  4. `git rebase main` pour importer les mises à jour de la branche main dans la branche de travail

q comment voir le détail ce qu'on a modifié ?
r commande `git diff` ou `git add -p` (ajoute tout de suite dans le staging)

q à quoi sert la commande `git rebase [nom_commit]` ?
r elle permet de repartir avec la base d'un commit spécifique

## dev front et back

q quels sont les langages côté client ?
r HTML, CSS, JS

q quels sont les langages côté serveur ?
r PHP, Python, Java, JS (nodejs), SQL

q quelle est l'utilité d'un langage côté client ?
r interaction avec l'utilisateur, user experience, aspect visuel

q quelle est l'utilité d'un langage côté serveur ?
r stabilité, gestion des données, sécurité des données

