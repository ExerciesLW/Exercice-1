# Exercice SJT
## Guide Arborescence 

* dist : Endroit oú les fichiers compilé sont générés (Utilisation de Parcel-Bundler)

* node_modules : oú sont stocker les modules NPM

* src : Dossier de développement

* src/css : Emplacement des fichiers CSS & LESS

* src/css/styles.less : Point d'entrée du dossier CSS oú on importe tout les fichiers LESS pour la compilation

* src/img : Dossier contenant les images brutes utilisées qui seront optimisées par parcel

* index.html : Fichier de la page HTML

## Utiliser parcel

### Prérequis 
Installer NodeJS et NPM sur la machine de développement

### Modification du projet
* Faire un `npm install` à la racine du projet

* Installer parcel-bundler avec la commande `npm i -g parcel-bundler`

* Lancer la commande `parcel ./src/index.html` pour lancer l'environnement de développement 