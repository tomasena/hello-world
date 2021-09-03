Bonjour !!
Commandes de git

git --version
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
>>>> avant il faut se placer dans le repertoire à suivre
git init
git status
git add readme.txt
git commit -m "Création du fichier readme"
git diff
git remote add origin https://github.com/tomasena/hello-world.git
git push origin master


>>>>>>>>>>>>>
Vérifiez l'état des modifications dans un dépôt
git status
Afficher les modifications apportés aux fichiers
git diff
Ajouter les modifications d'un fichier à soumettre
git add <FILENAME>
Pour ajouter toutes les modifications d'un seul coup
git add .
Pour soumettre les modifications que vous avez ajoutées avec un court message décrivant les modifications
git commit -m "your commit message"
Ajouter un remote
git remote add <REMOTENAME> <URL>
Modifier l'URL d'un remote
git remote set-url <REMOTENAME> <URL>
Tirer des changement à partir d'un remote
git pull <REMOTENAME> <BRANCHNAME>
Afficher l'adresse d'un remote
git remote -v
Pousser des modifications
git push <REMOTENAME> <BRANCH>