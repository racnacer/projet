# Git par équipe

## Objectif

Manipuler Git et Github en équipe.

## Instructions

Faites 3 groupes de 2.

Manuel - 

### Création du dépôt (Personne A)

Une personne sur les 2 du groupe (à décider entre vous) va créer un dépôt sur Github. Puis créer un premier commit et l'envoyer vers le dépôt à distance.

* Créer le dépôt "projet" sur Github
* Donner les droits d'accès au partenaire
* Créer un dossier "projet" à la racine de sites/
* Taper la commande *git init*
* Créer un fichier *index.php* avec un peu de code
* Ajouter le fichier au suivi *git add -A*
* Faire un commit *git commit -m "first commit"*
* Modifier la branche *git branch -M main*
* Pousser les modifications vers la branche distante *git push -u origin main*

### Récupération du dépôt et des fichiers qu'il contient (Personne B)

* Accepter la demande par mail sur Github
* Depuis le terminal, se positionner au niveau du dossier "sites/"
* Lancer la commande *git clone https://github.com/{pseudo du partenaire}/projet.git* (demander à votre partenaire l'adresse exacte si vous n'êtes pas sûr)

Après ces commandes, si tout se passe bien, un dossier "projet" aura été créé dans le dossier "sites/".