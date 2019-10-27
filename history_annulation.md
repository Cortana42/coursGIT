"git --no-pager log --oneline" : sans pagination pas de console bloqué;
"git --no-pager log -3 --oneline" : 3 commits seulement;
"git log --author {"nom de l'auteur"}" : consulter les commits d'un auteur en particulier;
permet de consulter l'historique de différentes manières:
    - "git log --since=1.day"
    - "git log --before={"entrez une date}"
"git log {nom d'un fichier}" : permet de consulter l'historique d'un fichier en particulier;
"git log -p {nom du fichier}" : permet de visualiser les modification au sein d'un fichier ou de l'ensemble/d'un ensemble de(s) fichier(s);
"git log -E -i --grep:{'mot recherché}" : rechercher des logs (messages des commits);
"git blame {nom du fichier}" : explique ou corrige la/les modification(s);
"git diff" : visualiser les modifications avant d'indexer le fichier;
"git diff --cached" : affiche les différences entre le dernier commit et l'index;
"git diff HEAD~1" : affiche les différences après avoir commité les changement, recule d'un commit en arrière;
"git diff HEAD~3 HEAD" : différences entre le HEAD et 3 commit avant;
"git log --oneline" : récupérer les haches des deux derniers commits;
"git diff --stat" : faire des stats sur les différences opérées dans les fichiers;
"git restore" : permet de remettre le dépot dans l'état dans lequel il se trouvait juste avant cette modification;
"git restore --staged" : permet d'ajouter le fichier dans l'index en refaisant la modification;
"git reset HEAD~1" : annule le dernier commit et met tout dans le WD sans perte (revient au commit précédent);
"git reset --soft HEAD~1" : annule le dernier commit et met tout dans le staging area sans perte; 
"git reset --hard HEAD~1" : annule le dernier commit et supprime les modifications (dangereux);
"git checkout" : permet de remettre un fichier dans son état initial;
"git revert" : permet d'annuler un commit en créant un commit d'annulation;