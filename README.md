# Git Projet 1
Ce projet est un projet teste pour l'apprentissage de Git et de GitHub.
La creation de ce ficher "README" est une description  de mon projet.

Ce projet est un exemple de REPOSITORY que nous allons etudier etape par etape.

Cette ligne a ete ajouter sur GitHub lui meme.

# Cette section explique les commande GIT LOG, STATUS, BRANCH, COMMIT, Staging Environement, CHECKOUT, MERGE.

Toutes ces commandes sont preceder de "GIT", On va les enumerer dans l'ordre d'utilisation :

-Staging Environement: "git add -A" ou "git add (fichier)" permet d'ajouter plusieur ou un seul fichier pour les preparer a etre commit c'est a dire vraiment enregistrer dans la branche. Toujour effectuer cette etape avant un "commit".

-Commit: "git commit -m 'Message'" pour valider ou enregistrer les modifications apporter sur le ou les fichiers, le message est tres important pour decrire les modifications apporter.

-Branch: "git branch" => pour verifier tous les branchs disponible; "git branch (Nom)" => pour cree une nouvelle branch; "git branch -d (nom)" pour supprimer la branch.

-Checkout: "git checkout (Nom Branche)" pour changer de branche; "git checkout -b (nom branch)" pour cree une nouvelle branch avec l'option "b" si le nom mis n'existe pas sinon juste changer de branch.

-Merge: "git merge (nom)" pour fusionner la branch mentionner dans cette commande avec la branch actuelle avec laquelle on travail.

-Log: "git log (nom Branch)" permet de voir toutes les modifications effectuer sur une branch en particulier.

-Status: "git status" permet de voir les problemes ainsi que les suggestions, les fichier non enregistrer et non commiter sur la branche.

# Quelque note a propos du repository Distant

Le repository distant on peut lui donnee un nom (origin).
Donc pour l'invoque c'est avec l'expression "origin/(nom branch distant)"

# Les commande disponibles pour le repository distant

Pour ajouter lier le repository distant et celui en local voici la commande:
=> "git remote add (nom) (lien vers le repository distant)" il est conseiller d'effectuer la tache avec une CLI local (CMD, Powershell, etc...).

puis nous devons envoyer nos branch vers le repository distant:
=> "git push --set-upstream (nom) (nom Branch local)" le (nom) utiliser pour lier le distant et le local plus haut.

On peut voir la difference entre les deux branch (local et distant) avec Diff
=> "git diff (nom)/(nom Branch)"

#----- Cette section est ajouter pour montrer  l'utiliter de Pull :

Pull permet de faire un Fetch et un Merge en meme temps.
fetch et merge permet de mettre a jours les modification effectuer des repository Distant => local.
(Voir capture d'ecran pour mieux comprendre "fetch" et "merge").

apres chaque modifications sur le repository distant et qu'on veut utiliser cette modification en local alors on peut utiliser PULL pour obtenir les mises a jours.
 
 Ex: "git pull (nom)" (nom) utiliser pour lier le distant et le local.


#----- Cette section explique l'utiliter de Push

Contrairement a pull, 
PUSH permet de mettre a jours les modifications effectuer des repository Local => Distant.

 Ex: "git push origin"
