git branch dev  ==>  création de la branche : dev

git branch  ==>  affiche toutes les branches créées

git checkout dev  ==>  déplacement du HEAD sur la branche dev

git checkout -b (nom_branche)  ==>  Création + déplacement sur une branche donnée

git branch -d (nom_branche)  ==>  suppression d'une branche si rien ne l'en empêche (si l'espace de travail est propre)

git branch -D (nom_branche)  ==>  force la suppression d'une branche

git merge (nom_branche)  ==>  Fusion de 2 branches différentes : la branche définie et la branche du HEAD. Elles doivent etre dans la même liaison de branches

git merge (nom_branche) --no-ff  ==>  fusion de 2 branches peu importe leur positionnement

git branch --no-merged  ==>  affiche toutes les branches qui n'ont pas étées mergées.

git log --oneline --graph  ==>  affiche le graph des commit

git stash  ==>  enregistre le code dans le stash, utilisable plus tard

git stash list  ==>  affiche tous les stash

git stash apply  ==>  applique les éléments stockés dans le stash

git stash drop  ==>  supprime les éléments de la remise du stash

git stash apply --index  ==>  remet les éléments de stash dans l'index au lieu du work directory

git stash apply stash@{1}  ==>  applique uniquement le 1er stash

git stash drop stash@{1}  ==>  drop uniquement le 1er stash

sh stash_name.sh  ==>  création du dépot stash

git tag -a v1.0 -m "(texte)"  ==>  Création d'un tag annoté

git tag v1  ==>  Création d'un tag léger sans annotations

git tag -a v1.0.1 -m "(texte)" commit_tag  ==>  ajoute un tag sur le commit précisé

git show v8.2  ==>  affiche le tag de la version demandée (un tag annoté)

git remote add origin C:\Labs\my_server_name.git  ==>  donne une origine au serveur local/internet où partager les fichiers

git push origin (branche a envoyer)  ==>  envoie la branche sur le serveur donné

git pull origin (branche a envoyer)  ==>  récupère la branche en question

git remote  ==>  affiche les dépots distants

git remote -v  ==> Lister en mode verbeux (plus en détails)

git remote add [surname] [addresse_du_serveur_distant]  ==>  ajoute l'origine d'un dépot distant

git remote rm [surname]  ==>  supprime un dépot distant

git remote rename [old_surname] [new_surname]  ==>  renomme un dépot distant

git fetch origin  ==>  apporte l'origine de la branche distante

git pull origin  ==>  apporte l'origine de la branche distante et et la merge automatiquement avec le master

git merge origin/master  ==>  merge la branche master de l'origine avec celle du fichier localù

git push [surname_server] [branch_name]  ==>  envoie la branche en question sur le hub en question

git remote show origin  ==>  affiche des infos sur l'origine du serveur distant