## Git fonctionnalitées(local)
### git init
### git config 
### git add ( --all)
### git rm --cached file
->retirer un fichier dans le staging area
### git commit 
### git log (--stat) | (--number)-> recuper le number de commit 2 = les 2derniers | (--p) ->pagination page par page
###git log file 
->commit fait sur tel fichier (le nom du fichier)
### git status
###git commit --amend 
###git --amend
->reviens sur le commit precédent (fusionner le dernier commit avc lavant-dernier)
###git --revert id
->annule le dernier commit -> suppression et modification -> reviens en arrière
### git rm --cached lire.txt 
-> pour retirer le fichier lire.txt
### git revert a85b49b38f74cb7c1a72bf26dc2c30b9b4c50f83 
-> suprime les dernieres modificatiosn jusqu'à l'ancien commit(je recuper clé de cryptage avec un git log)
### git resset
-> suprime normalement de l'historique
###git push
->envoi sur le gitub
###git clone avec l'adresse fournie lors du clonage pour recupere le repository de qlq 
*.md tu n'indexera jms les .md
###git pull 
->recupere avec les modifications faites
### git remote add origin https://github.com/lordelaure/gitweb.git
->configuration en local du remote
### git push -u origin master
->envoi du premier repository
### git push
->envoi suivant
### git clone url
->recuperer un repository distant
### git pull
->recuperer un repository
### git remote remove origin 
->changer le repository distant
### git flush???

## Git fonctionnalitées (remote)
### 

##Exercices
Créez un dossier css avec 2fichiers
Créez un fichier admin.php, lire.txt
Lire.txt ne sera pas indexé, commiter la nouvelle version 