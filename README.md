# GitHub_LFS
Guide des commandes Git
Installation et connexion

    git init : initialise un nouveau dépôt Git
    git remote add origin <url> : connecte le dépôt local à un dépôt distant sur GitHub
    git lfs track "*.zip" : ajoute les fichiers ZIP au système Git LFS (Large File Storage)
    git add <fichier> : ajoute un fichier au prochain commit
    git commit -m "<message>" : crée un nouveau commit avec un message descriptif
    git pull origin main --allow-unrelated-histories : fusionne les modifications locales et distantes (si nécessaire)

Gestion des branches

    git branch : affiche toutes les branches locales
    git branch <nom> : crée une nouvelle branche avec le nom spécifié
    git commit -a <branche> : crée un nouveau commit pour la branche spécifiée
    git checkout <branche> : change de branche courante
    git branch -a : affiche toutes les branches locales et distantes

Historique des commits

    git log : affiche l'historique des commits
    git checkout main : change de branche courante pour la branche "main"
    git rebase -i HEAD~<nombre> : ouvre une interface interactive pour modifier l'historique des commits
    git rebase --continue : continue la modification de l'historique des commits (après avoir quitté l'interface interactive)
    git push --force origin main : pousse les modifications locales vers le dépôt distant (avec écrasement des modifications existantes)

N'oubliez pas que certaines commandes peuvent avoir des effets irréversibles sur votre dépôt, alors utilisez-les avec précaution et faites toujours des sauvegardes régulières de vos fichiers importants.
