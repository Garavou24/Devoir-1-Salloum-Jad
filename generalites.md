Configuration de git :

git config --global user.name (Username)
git config --global user.email (mail adress)

Début de session git :

git init  ==>  Crée un dossier .git permettant le bon fonctionnement du reste des actions avec leur entourage.

Commandes générales :

git status  ==>  Indique l'état des fichiers liés à git ou non. Ignore les fichiers dans le .gitignore .

echo "" > (file_name.file_type)  ==>  création du fichier dans la branche donnée .

git rm file_name.file_type ==> suppression du fichier dans la branche donnée. Permet de garder un commit à appeler si besoin.

git rm --cached file_name.file_type  ==> déplacement du fichier dans le .gitignore .

git add file_name.file_type  ==>  ajout du fichier dans la liste des éléments à suivre (suit leur modifications)

git add .  ==>  ajout de tous les fichiers. prend en compte les modifications de fichiers.

git commit -m "(message)"  ==>  permet de créer un commentaire de nos actions entre chaque commit. message de - de 49 charactères

git commit  ==>  ouvre une page qui permet d'écrire un commit plus long. il faut enregistrer le fichier (ctrl + S) et fermer la page.

git log  ==>  affiche les commits faits par tous les utilisateurs dans l'ordre d'ajout (le 1er étant le plus récent)

git shortlog ==> pareil mais de façon abrégée

git blame  ==>  affiche la liste des personnes du groupe ayant modifié les fichiers.

git blame file_name.file_type  ==>  affiche la liste des personnes du groupe ayant modifié le fichier.

git mv ancien_fichier nouveau_fichier  ==>  renomme un fichier déja existant.

git commit -am "(message)"  ==>  modifie le dernier commit

git ls-files  ==>  affiche tous les fichiers suivis