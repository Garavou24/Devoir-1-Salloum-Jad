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

