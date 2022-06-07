# Installer Node.js et discord.js

Installation de Node.js

Pour utiliser discord.js, vous devez installer Node.js. discord.js v13 nécessite Node V16.6.0 ou supérieur.

<aside>
💡 Pour vérifier si Node est déjà installé sur votre machine (par exemple, si vous utilisez un VPS), exécutez `node -v` dans votre terminal. S’il renvois `v16.6.0` ou plus, alors vous êtes prêt ! Sinon, continuez à lire.

</aside>

Sous Windows, c’est aussi simple que d’installer n’importe quel autre programme. Téléchargez la dernière version depuis [https://nodejs.org/en/](https://nodejs.org/en/) , ouvez le fichier téléchargé et suivez les étapes du programme d’installation.

Sur macOS, soit :

- Téléchargez la dernière version depuis le site [https://nodejs.org/en/](https://nodejs.org/en/) , ouvrez le programme d’installation du package et suivez les instructions
- Utilisez un gestionnaire de paquets comme Homebrew avec la commande `brew install node`
- Sous linux, vous pouvez consulter [https://nodejs.org/en/download/package-manager/](https://nodejs.org/en/download/package-manager/) pour déterminer comment installer Node.

## Préparer l’essentiel

Pour utiliser discord.js, vous devrez l’installer via **npm** (le gestionnaire de packages de Node). **npm** est fourni avec chaque installation de Node, vous n’avez donc pas à vous soucier de l’installer. Cependant, avant d’installer quoi que ce soit, vous devez configurer un nouveau projet.

Accédez à un endroit approprié sur votre machine et créez un nouveau dossier nommé `discord-bot` (ou ce que vous voulez). Ensuite, vous devrez ouvrir votre terminal.

## Ouverture du terminal

<aside>
💡 Si vous utilisez **Visual Studio Code**, vous pouvez appuyer sur `Ctrl + `` (backtick) pour ouvrir son terminal intégré.

</aside>

Sous windows, soit :

- `Shift + Right-click` dans votre répertoire de projet et choisissez l’option “Ouvrir la fenêtre de commande ici”.
- `WIn + R` et exécutez `cmd.exe`, puis `cd` dans votre répertoire de projet.

Sur macOS, soit :

- Ouvrez Launchpad ou Spotlight et recherchez “Terminal”.
- Dans votre dossier “Applications”, sous “Utilitaires”, ouvre l’application Terminal

Sous linux, vous pouvez ouvrir rapidement le terminal avec `Ctrl + Alt + T`.

Avec le terminal ouvert, exécutez la commande `node -v` pour vous assurer que vous avez correctement installé Node.js. S’il sort `v16.6.0` ou plus, c’est parfait !

## Initialiser un projet

```bash
npm init
```

C’est la prochaine commande que vous exécuterez. Cette commande crée un fchier `package.json` pour vous, qui gardera une trace des dépendances utilisées par votre projet, ainsi que d’autres informations.

Cette  commande vous posera une séquence de questions, vous devez les remplir comme bon vous semble. Si vous n’êtes pas sûr de quelque chose ou si vous voulez l’ignorer dans son ensemble, laissez-le vide et appuyez sur `Entrée`.

<aside>
💡 Pour commencer rapidement, vous pouvez exécuter la commande suivante pour qu’elle remplisse tout pour vous.

</aside>

```bash
npm init -y
```

Une fois que vous avez terminé, vous êtes prêt à installer discord.js !

## Installation de discord.js

Maintenant que vous avez installé Node.js et que vous savez comment ouvrir votre console et exécuter des commandes, vous pouvez enfin installer discord.js ! Exécutez la commande suivant dans votre terminal :

```bash
npm install discord.js
```

Et c’est tout ! Avec toutes les nécessités installées, vous êtes presque prêt à commencer à coder votre bot.

[Mise en place d’une application bot](Mise%20en%20place%20d%E2%80%99une%20application%20bot%2007431bb5076d45d0a104d7af6cefdec9.md)