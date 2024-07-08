# Meubl&Co - Site  factice de vente de meubles d'occasions - Projet Collectif Ada Tech School
Credits : Maud, Adriana, Cindy, Hassen, Caroline

# DOCUMENTATION Back-End Symfony

I. INSTALLER PHP : https://www.php.net/manual/fr/install.php

Sur MacOs, et Linux télecharger avec Homebrew https://brew.sh/

II. INSTALLER COMPOSER, ici c'est detaillé pour tous les systemes, il faut faire l'installation GLOBALE (c'est indique sur la doc)

https://getcomposer.org/doc/00-intro.md

III. INSTALLER SYMFONY

https://symfony.com/download 

Debian/Ubuntu — APT based Linux

curl -1sLf 'https://dl.cloudsmith.io/public/symfony/stable/setup.deb.sh' | sudo -E bash
sudo apt install symfony-cli

Pour MacOs

1) Homebrew: install Homebrew https://brew.sh/
2) brew install symfony-cli/tap/symfony-cli

Pour Windows
1) Installer Chocolatey (il faut s'inscire pour le telecharger)https://chocolatey.org/install c'est un gestionnaire de paquets qui va installer Symfony ou scoop, celui cité dans la doc Symfony: Scoop install Scoop
scoop install symfony-cli


Vous pouvez Telecharger PHP STORM si vous voulez comme IDE, vous pouvez avoir la licence gratuite (pack etudiant Jet Brains) avec votre adresse mail de lovelace

IV. TUTOS

OFFICIELLE Symfony (for Dummies) tutos video : https://symfonycasts.com/
On conseille les chapitres 1, 2, 3 et 8

GRAFIKART
https://grafikart.fr/tutoriels/installation-symfony-2180#autoplay
On conseille fortement de gagner du temps, en regardant ces chapitres d'abord
Decouverte
Installation
premieres pages
L ORM doctrine
ORM relation ManyToONe si on veux faire des tables relationnelles
Creer une API : le serializer, et suivre les autres si vous voulez aller plus loin

PROJET

voici la doc officiele
https://symfony.com/doc/current/setup.html



Dans le terminal, va dans le dossier où est le projet, ecris cette ligne de commande :

$ composer require webapp

et verifie que ton environement de travail est pret avec: 

$ symfony check:requirements

ATTENTION le serveur XAMPP, LAMP, WAMP, MAMP doivent etre allumes pour faire tourner la base de donnes, mais il est inutile
de mettre le projet dans htdocs.

ouvrir le projet, et sur le terminal, allumer le serveur

$ symfony server:start

Note 1 : INSTALLER ADMINEREVO pour visualiser les bases de donnees, c'est un gestionnaire de basses de donnes GDBD

en français : https://download.adminerevo.org/4.8.4/adminer/adminer-mysql-fr.zip

une fois téléchargé, le deziper, copier/coller dans  le dossier public du projet,  et le renommer adminer.php  avec l'explorateur de fichiers.

Note 2 : Installer Nelmio Bundle pour les problèmes de CORS
https://symfony.com/bundles/NelmioApiDocBundle/current/index.html

$ composer require nelmio/api-doc-bundle

Configuration rapide à conditions d'avoir dans le fichier composer.json la ligne symfony:flex
Si jamais il y a symfony:symfony, suivre la documentation.

Généréré automatique dans le fichier d'environnement .env :
###> nelmio/cors-bundle ###
CORS_ALLOW_ORIGIN='^https?://(localhost|127\.0\.0\.1)(:[0-9]+)?$'
###< nelmio/cors-bundle ###

Sinon, le rajouter.


# DOCUMENTATION Front-End - Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)






