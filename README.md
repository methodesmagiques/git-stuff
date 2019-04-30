# Git Commande

Il y a, l'espace de travail, l'index et le dépot.
- L'espace de travail correspond au répertoire local du développeur. C'est le dossier du projet ou se situe les fichiers que l'on ajoute, modifie.
- L'index correspond à la zone intermédiaire ou le développeur place ces fichiers en attendant le commit (tous les fichiers verts)
- le dépôt c'est l'espace ou git va enregistrer les groupes de modifications, versionner les fichiers, après avoir réaliser un commit.

## Set Alias
dans C:\Users\debartot ouvrir le fichier .gitconfig
Puis ajouter à la suite du contenu déjà present
```
[alias]
	co = checkout
	br = branch
	ci = commit
	st = status
	gr = rm -r
	cm = commit -m
	po = push origin
	pom = push origin master
```