"git branch dev" : permet de créer une branche;
"git branch" : permet d'afficher l'ensemble des branches se trouvant sur le dépôt;
"git checkout dev" : permet de se déplacer sur l'autre branche;
"git checkout master" : permet de revenir sur la branche master;
"git checkout -b feature_header" : permet de créer une branche et se déplacer dessus en une seule commande;
"git branch -d {nom de votre branche}" : supprimer une branche;
"git branch -D {nom de votre branche}" : forcer la suppresion d'une branche;
"git merge dev" : permet de mérger dev dans master;
"git merge dev --no-ff" : permet de commit le merge;
" git branch --no-merged" : liste de toutes les branches non mergées;
"git stash" : permet de remiser le code non terminé;
"git stash list" : permet de lister sur la branche les stash;
"git stash apply" : permet de récupérer ce qui était dans la stash, ce qui récupère le code modifié;
"git stash drop" : supprime ce qui se trouve dans la remise;
"git stash apply --index" : essaie de remettre ce qui était dans l'index;
"git tag -a v1.0 -m {"texte}" : création d'un tag annoté;
"git tag v1" : création d'un tag léger;
"git tag -a v1.0.1 -m {"texte}" : étiquetter après coup sur un commit donné;
"git tag" : permet de montrer la liste des tags;
"git tag -1 {'nom du tag“} : rechercher des tags particuliers;
"git show v9.2" : voir un tag annoté;
"git remote" : lister les dépôts distants";
"git remote -v" : lister en mode verbeux; 
"git remote add [alias] [chemin_du_serveyr_distant] : ajouter un dépôt distant;
"git remote rm [alias]" : supprimer un dépôt distant;
"git remot rename [alias] [new_alias]" : renommer un dépôt distant;
"git fetch origin" : peremet de récupérer la branche distante localement sans fusion avec sa branche master;
"git log master..origin/master" : comparer les différences entre master local et distant; 
"git push [nom-distant] [nom-de-branche]: permet de publier une branche distante;
"git remote show origin" : inspecter un dépôt distant;