git --no-pager log --oneline  ==>  même chose que log, mais sans pagination

git --no-pager log -3 --oneline   ==>  pareil mais n'affiche que les 3 derniers log

git log --since=1.day  ==> affiche les log datant de hier

git log --author "(nom)"  ==> affiche les modifications apportées par un utilisateur donné

git log --before="year-month-day"  ==>  affiche tous les log après une date donnée

git log file_name.file_type  ==>  affiche tous les log qui ont un rapport avec un fichier donné

git log -p file_name.file_type ==>  affiche toutes les modifications apportées au fichier à chaque commit

git log -p  ==> affiche toutes les modifications apportées à tous les fichiers à chaque commit

git log -2 -p  ==>  affiche les modifications apportées aux fichiers dans les 2 derniers commits

git --stat file_name.file_type  ==>  affiche les ajouts et les suppressions de lignes dans un fichier donné

git log -E -i --grep='mot'  ==>  recherhe un log où on retrouve le mot en question. -E trouve les occurences et -i ignore les majuscules/minuscules

git diff  ==>  montre les différences dans tous les fichiers

git diff --cached  ==>  montre les différences entre le dernier commit et l'index. si on fait add, diff n'affichera rien

git log (ref commit) (ref commit2)  ==>  montre les log entre 2 commits.

git diff --stat  ==>  montre les différences dans tous les fichiers

git restore file_name.file_type  ==>  annule la dernière action faite à ce fichier

git restore --staged  ==>  si le fichier est dans l'index

git commit "(message)" --amend --no-edit  ==>  modifie uniquement le message du dernier commit

git reset ( )  ==>  supprime le dernier commit d'un fichier

git reset --soft  ==>  garde les commit

git reset --hard  ==> supprime tous les commit (et les modifs par conséquence )

git checkout (ref commit) file_name.file_type  ==>  modifie le fichier pour qu'il revienne à l'état du commit désigné

mkdir file_name  ==>  Création de dossier (vide)

cd file_name  ==>  déplace le module git vers un dossier désigné. Necessite les origines si dans un dossier différent.

git revert (ref commit)  ==>  annule toute modification effectuée depuis le commit en question. Garde les commit d'avant.