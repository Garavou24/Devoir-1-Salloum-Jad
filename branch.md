git branch dev  ==>  cr�ation de la branche : dev

git branch  ==>  affiche toutes les branches cr��es

git checkout dev  ==>  d�placement du HEAD sur la branche dev

git checkout -b (nom_branche)  ==>  Cr�ation + d�placement sur une branche donn�e

git branch -d (nom_branche)  ==>  suppression d'une branche si rien ne l'en emp�che (si l'espace de travail est propre)

git branch -D (nom_branche)  ==>  force la suppression d'une branche

git merge (nom_branche)  ==>  Fusion de 2 branches diff�rentes : la branche d�finie et la branche du HEAD. Elles doivent etre dans la m�me liaison de branches

git merge (nom_branche) --no-ff  ==>  fusion de 2 branches peu importe leur positionnement

git branch --no-merged  ==>  affiche toutes les branches qui n'ont pas �t�es merg�es.

git log --oneline --graph  ==>  affiche le graph des commit

git stash  ==>  enregistre le code dans le stash, utilisable plus tard

git stash list  ==>  affiche tous les stash

git stash apply  ==>  applique les �l�ments stock�s dans le stash

git stash drop  ==>  supprime les �l�ments de la remise du stash

git stash apply --index  ==>  remet les �l�ments de stash dans l'index au lieu du work directory

git stash apply stash@{1}  ==>  applique uniquement le 1er stash

git stash drop stash@{1}  ==>  drop uniquement le 1er stash

sh stash_name.sh  ==>  cr�ation du d�pot stash

git tag -a v1.0 -m "(texte)"  ==>  Cr�ation d'un tag annot�

git tag v1  ==>  Cr�ation d'un tag l�ger sans annotations

git tag -a v1.0.1 -m "(texte)" commit_tag  ==>  ajoute un tag sur le commit pr�cis�

git show v8.2  ==>  affiche le tag de la version demand�e (un tag annot�)

git remote add origin C:\Labs\my_server_name.git  ==>  donne une origine au serveur local/internet o� partager les fichiers

git push origin (branche a envoyer)  ==>  envoie la branche sur le serveur donn�

git pull origin (branche a envoyer)  ==>  r�cup�re la branche en question

git remote  ==>  affiche les d�pots distants

git remote -v  ==> Lister en mode verbeux (plus en d�tails)

git remote add [surname] [addresse_du_serveur_distant]  ==>  ajoute l'origine d'un d�pot distant

git remote rm [surname]  ==>  supprime un d�pot distant

git remote rename [old_surname] [new_surname]  ==>  renomme un d�pot distant

git fetch origin  ==>  apporte l'origine de la branche distante

git pull origin  ==>  apporte l'origine de la branche distante et et la merge automatiquement avec le master

git merge origin/master  ==>  merge la branche master de l'origine avec celle du fichier local�

git push [surname_server] [branch_name]  ==>  envoie la branche en question sur le hub en question

git remote show origin  ==>  affiche des infos sur l'origine du serveur distant