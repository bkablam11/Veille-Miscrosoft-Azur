# Initialisation et cration du dossier git 
## cloner le dossier oû les fichier seront stocker sur git
* git clone https://github.com/bkablam11/(name_folder).git
* git add . (dans le dossier à poster sur git)
* git commit -m "comment"
* git push

## utiliser un dossier local et envoie sur git
* echo "# nom_folder" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/bkablam11/Veille_SAAS.git
* git push -u origin main

## update files to git
* git status
* git add . (dans le dossier à poster sur git)
* git commit -m "comment"
* git push