Configuration de git :

git config --global user.name (Username)
git config --global user.email (mail adress)

D�but de session git :

git init  ==>  Cr�e un dossier .git permettant le bon fonctionnement du reste des actions avec leur entourage.

Commandes g�n�rales :

git status  ==>  Indique l'�tat des fichiers li�s � git ou non. Ignore les fichiers dans le .gitignore .

echo "" > (file_name.file_type)  ==>  cr�ation du fichier dans la branche donn�e .

git rm file_name.file_type ==> suppression du fichier dans la branche donn�e. Permet de garder un commit � appeler si besoin.

git rm --cached file_name.file_type  ==> d�placement du fichier dans le .gitignore .

git add file_name.file_type  ==>  ajout du fichier dans la liste des �l�ments � suivre (suit leur modifications)

git add .  ==>  ajout de tous les fichiers. prend en compte les modifications de fichiers.

git commit -m "(message)"  ==>  permet de cr�er un commentaire de nos actions entre chaque commit. message de - de 49 charact�res

git commit  ==>  ouvre une page qui permet d'�crire un commit plus long. il faut enregistrer le fichier (ctrl + S) et fermer la page.

git log  ==>  affiche les commits faits par tous les utilisateurs dans l'ordre d'ajout (le 1er �tant le plus r�cent)

git shortlog ==> pareil mais de fa�on abr�g�e

git blame  ==>  affiche la liste des personnes du groupe ayant modifi� les fichiers.

git blame file_name.file_type  ==>  affiche la liste des personnes du groupe ayant modifi� le fichier.

git mv ancien_fichier nouveau_fichier  ==>  renomme un fichier d�ja existant.

git commit -am "(message)"  ==>  modifie le dernier commit

git ls-files  ==>  affiche tous les fichiers suivis