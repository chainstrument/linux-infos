# linux-infos

### navigation fichier

se connecter en tant que root
> su root

pour executer une commande sans changer de user mais en tant que root

> sudo commande

Aller dans un repertoire 

> cd /chemin/repositories 

Monte d'un repertoire 
> cd .. 

Voir la liste des elements du repertoire 

> ls 

Affiche la liste des fichiers cachés et visibles dans un repertoire 

> ls -a 

### commande "cat"

creer un nouveau fichier 
>cat > nomfichier.txt

fusionne nomfichier1.txt et nomfichier2.txt et stocke le résultat dans nomfichier3.txt.
> cat nomfichier1.txt nomfichier2.txt > nomfichier3.txt

### Commande "cp"

> cp nomfichier.txt /home/nomd’utilisateur/Documents


> cp nomfichier1.txt nomfichier2.txt

Copie tous le contenu du repertoire dans un autre spécifié
> cp -R /home/username/Documents /home/username/Documents_backup

### commande "mv" 

Sert a deplacer et rennommer des fichiers dans un repertoire 
> mv nom_de_fichier.txt /home/nom_d’utilisateur/Documents.


possibilité de renommer un fichier 
> mv ancien_nom_de_fichier.txt nouveau_nom_de_fichier.txt

### commande "mkdir" 

Creation d'un dossier 

> mkdir musique 

### commande "rmdir"

Pour supprimer un repertoire 

### commande "rm"

> rm nomfichier1 nomfichier2 nomfichier3
* demande au systeme de cofimer la suppression d'un fichier 
* -f permet au système de procéder à la suppression sans confirmation.
* -r supprime les fichiers et les répertoires de manière récursive.

### commande "touch"

La commande touch permet de créer un fichier vide ou de générer et de modifier un horodatage dans la ligne de commande.

> touch /home/nom d’utilisateur/Documents/web.html


### commande "locate"

La commande locate permet de trouver un fichier dans le système de base de données.

> locate -i école*note


### commande "passwd"
 se mettre en sudo pour changer le mdp d'un user
 > sudo passwd nomuser
 




