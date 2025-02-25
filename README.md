
# Mon Horloge Gaming (Electron App)

Cette application **Electron** vous permet de créer une horloge numérique inspirée du design moderne et gaming avec un effet néon et des secondes animées. Elle est conçue pour être utilisée sur des environnements de bureau, avec une interface utilisateur simple et attrayante.

## Fonctionnalités

- Affichage de l'heure en temps réel au format `HH:MM:SS`.
- Animation des secondes avec un effet de clignotement.
- Interface moderne avec des éléments de style "gaming" (fond sombre, texte néon).
- Écran plein par défaut avec une taille de fenêtre s'adaptant à la taille de l'écran.

## Prérequis

Avant de commencer, vous devez avoir installé sur votre machine les outils suivants :

- [Node.js](https://nodejs.org/) (version 14 ou supérieure)
- [npm](https://www.npmjs.com/) (installé avec Node.js)
- [Electron](https://www.electronjs.org/)

## Installation

### 1. Clonez ou téléchargez le projet

```bash
git clone https://github.com/ton-utilisateur/mon-horloge-electron.git
cd mon-horloge-electron
```

### 2. Installez les dépendances

Dans le répertoire du projet, exécutez la commande suivante pour installer toutes les dépendances nécessaires :

```bash
npm install
```

### 3. Lancez l'application en mode développement

Une fois les dépendances installées, vous pouvez démarrer l'application en mode développement :

```bash
npm start
```

Cela ouvrira la fenêtre de votre horloge gaming avec l'interface.

## Générer le Build

### 1. Préparez le projet pour le build

Avant de pouvoir créer le build de votre application, assurez-vous d'avoir bien configuré votre `package.json` et d'avoir spécifié tous les éléments nécessaires comme le nom de l'auteur, les configurations de build, etc.

### 2. Créez le build

Pour créer une version empaquetée de votre application (exécutable ou installateur pour Windows, macOS ou Linux), exécutez la commande suivante :

```bash
npm run build
```

Cela générera un fichier d'installation dans le dossier `dist/`. Le type d'installateur généré dépend du système d'exploitation ciblé (par exemple, `.exe` pour Windows, `.dmg` pour macOS).

### 3. Installer l'application

Après la génération du build, vous trouverez le fichier d'installation dans le dossier `dist/`. Exécutez-le pour installer votre application sur votre système.

## Dépannage

- **Problème de connexion lors du build** : Si vous avez une erreur comme `dial tcp: lookup github.com: no such host`, cela peut être dû à un problème de connexion réseau ou de DNS. Essayez de vérifier votre connexion Internet ou de modifier vos paramètres DNS.

- **L'application ne se lance pas** : Vérifiez que vous avez bien toutes les dépendances nécessaires. Exécutez `npm install` pour réinstaller les packages.

## Licence

Ce projet est sous AUCUNE licence.
