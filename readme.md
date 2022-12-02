# Tutoriel Git
Bienvenue sur ce tutoriel Git ! Ici nous allons découvrir quelques points essentiels de Git (et de Github par extension) :
- Comment créer une repository
- Comment envoyer vos fichiers
## Préparatifs
Pour ce tutoriel, vous aurez besoins de [Git](https://git-scm.com/) (nous utiliserons la version Bash pour que ce dernier fonctionne sur Windows, macOS et LInux de la même manière). Prenez la version adaptée à votre système d'exploitation. Par exemple si vous avez un PC sous Windows 11, prenez la version `Windows` !
## Créer un répertoire
Commençons par les bases, pour commencer votre nouveau projet, rendez-vous sur [Github](https://github.com/) et connectez-vous (ou inscrivez-vous). Ensuite, vous pouvez passer à ces étapes :
- Cliquez sur le bouton vert `New` pour créer un nouveau reperroire.
- Donnez un nom à votre repertoire, comme par exemple `mon-premier-repertoire` !
- Vous pouvez choisir de mettre un `readme.md` pour détailler votre projet aurpès de la communauté !
## Paramétrer Git
Pour pouvoir commencer à importer vos fichiers sur votre répertoire il vous faut paramétrer votre compte sur Git. Pour se faire :
- Ouvrez Git et tapez la commande `git config --global user.name "[nom]"`, faites bien attention à remplacer `[nom]` par votre nom d'utilisateur (ou pseudonyme) !
- Et enfin, effectuez ensuite la commande `git config --global user.email "[adresse email]"`, et encore une fois, faites attention à remplacer `[adresse email]` par l'**adresse e-mail de votre compte Github** !
## Envoyer vos fichiers
Si vous n'avez aucuns fichiers, copiez simplement le lien, sinon cliquez sur `Code` et copiez le lien de votre projet, il va nous servir pour importer vos fichiers !
- Ouvrez `Git Bash`
- Sélectionnez la destination que vous désirez sélectionner avec des `cd` (pour sélectionner une destination) et des `ls` (pour afficher le contenu de vos dossiers). De préférences, mettez-le dans un dossier sur votre compte !
- Mettez tout vos fichiers dans ce dossier
- Effectuez la commande `git clone [url-du-projet]` (en remplaçant encore une fois `[url-du-projet]` par le lien de votre projet)
- Effectuez vos actions (comme créer le fichier `readme.md` ou n'importe quel fichier)
- Effectuez ensuite la commande `git add *` pour ajouter tout les fichiers de votre répertoire
- Effectuez ensuite la commande `git commit -m "[Votre commit]"` (remplacez le `[Votre commit]` par le commentaire de votre commit, comme par exemple `Ajout de différents fichiers`)
- Effectuez enfin la commande `git push origin main` pour poster vos changements
**Félicitations !** Vous venez de poster votre premier projet sur Github !
## Notes 
Vous retrouverez bientôt un tutoriel plus complet directement sur le [site officiel](https://enioaiello.github.io/Tutoriel-Git) !
