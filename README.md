# <span style="text-align: center; color:white; margin: none; padding: 15px 0; background-color: gray; display: inline-block; width: 100%;">*TERMINAL GIT*</span>

---

- **git init**
    * *création du directory git*
<br>

- **git remote add origin "remote url"**
    * *préparation pour envoyer projet existant vers serveur (faire un push par la suite)*
<br>

- **git fetch**
    * *récupère les données distantes sans rien modifier en local*
<br>

- **git clone afficherUrl**
    * *copie du repository distant sur votre machine locale*
<br>

- **git branch**
    * *indique le nom de la branche où nous nous trouvons*
<br>

- **git branch NomBranch**
    * *création d'une branche*
<br>

- **git checkout nomBranch**
    * *sélection de la branche sur laquelle nous voulons travailler*
<br>

- **git checkout -b nomBranch**
    * *création + sélection de la branche*
<br>

- **git add .**
    * *ajout de tous les fichiers dans l'Index*
<br>

- **git add fichier.txt**
    * *ajout du fichier dans l'Index (préparation de la validation => staging)*
<br>

- **git add dossier**
    * *ajout du contenu d'un dossier dans l'Index (préparation de la validation => staging)*
<br>

- **git commit -m "description"**
    * *validation des modifications (en local)*
<br>

- **cliquer "q" pour sortir**
    * *sortir de la zone ouverte de message commit*
<br>

- **git push**
    * *pousse le travail sur le serveur (vers exterieur --> vers serveur)*
<br>

- **git merge nom branche à merger**
    * *indique la branche où nous voulons prendre le code pour le fusionner*
<br>

- **git pull**
    * *mise à jour du repository local à partir du serveur (pull = fetch + merge)*
<br>

- **git status**
    * *permet de voir l'état du repository (fichier unstaged ou staged...)*
<br>

- **git log**
    * *permet de voir l'historique des commits*
<br>

- **git log --oneline**
    * *permet de voir l'historique des commits de manière plus courte*
<br>

- **git reset HEAD "nom fichier"**
    * *enlève le fichier de l'Index (unstaged)*
<br>

- **git revert HEAD**
    * *Annuler le dernier commit (inverse les modifications)*
<br>

- **git rebase main**
    * *modifier la base de votre branche d'un commit à un autre, ce qui donne l'impression que vous aviez créé votre branche à partir d'un commit différent (exemple mise à jour à partir de main)*
<br>

- **git -v**
    * *voir Version*
<br>

- **git config --list**
    * *pour voir les informations de configuration*
<br>

- **git config --global user.name "votre nom"**
    * *ajouter votre nom aux infos de la config*
<br>

- **git config --global user.email "votre email"**
    * *ajouter votre email aux infos de la config*
<br>


> <span style="text-align: center; color:white; padding: 15px 0; background-color: gray; display: inline-block; width: 100%;">*Hugo L. Clavinas : BeCode 2023*</span>

---