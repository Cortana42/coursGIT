"git add --all --dry-run" : liste des fichiers stagés;
"git commit -m {"nom du commit}" --allow-empty : création d'un commit vide;
"git push -u -all"
"git push origin v8" : envoyer un/les tags;
"git push origin --tags" : permet d'envoyer plus simplement tous les tags;
"git branch -a" vérification de l'import des branches distantes;
création de la branche dev: 
    - "git checkout remotes/origin/dev"
    - git checkout -b dev
creation d'une feature à partir de la branche dev:
    - git branch
    - git checkout -b feature_routes
    -git commit -m "feature: task route" --allow-empty
    git push -u origin feature_routes
merger la nouvelle feature dans la branche dev: 
    - git pull --all 
    - git merge --no-ff feature_routes -m
    git push -u origin dev
suppression branche feature_routes: 
    - git pull --all 
    - git branch -d feature_routes
    - push origin :feature_routes