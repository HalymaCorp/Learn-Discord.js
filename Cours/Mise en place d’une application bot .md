# Mise en place d’une application bot

# Création de votre bot

Maintenant que vous  avez installé Node et discord.js vous êtes presque prêt à commencer à coder ! La prochaine étape que vous devez suivre consiste à configurer une véritable application de bot Discord via le site Web de Discord.

Il est facile d’en créer un. Les étapes que vous devez suivre sont les suivantes :

1. Ouvrez [https://discord.com/developers/applications](https://discord.com/developers/applications) et connectez-vous à votre compte.
2. Cliquez sur le bouton “Nouvelle Application”
3. Saisissez un nom et confirmez la fenêtre contextuelle en cliquant sur le bouton “Créer”.

Vous devriez voir une page comme celle-ci :

![Untitled](Mise%20en%20place%20d%E2%80%99une%20application%20bot%2007431bb5076d45d0a104d7af6cefdec9/Untitled.png)

Vous pouvez modifier le nom, la description et l’avatar de votre application ici. Une fois que vous avez enregistré vos modifications, continuez en sélectionnant l’onglet “Bot” dans le volet de gauche.

![Untitled](Mise%20en%20place%20d%E2%80%99une%20application%20bot%2007431bb5076d45d0a104d7af6cefdec9/Untitled%201.png)

# Le token de votre bot

<aside>
❗ Cette section est essentielle, alors soyez très attentif. Il explique qu’est-ce que le token de votre bot, ainsi que ses aspects de sécurité.

</aside>

Après avoir créé un bot user, vous verrez une section comme celle-ci :

![Untitled](Mise%20en%20place%20d%E2%80%99une%20application%20bot%2007431bb5076d45d0a104d7af6cefdec9/Untitled%202.png)

Dans ce panneau, vous pouvez donner à  votre bot un avatar élégant, définir son nom d’utilisateur et le rendre public ou privé. Le token de votre bot sera révélé lorsque vous appuyez sur le boutton “Réinitialiser le token” et confirmez. Lorsque nous vous demandons de coller le token de votre bot quelque part, c’est la valeur que vous devez entrer. Si vous perdez le token de votre bot à un moment donné, vous devez revenir sur cette page et réinitialiser à nouveau le token de votre bot, ce qui révèle le nouveau token, invalidant tous les anciens.

# Qu’est-ce qu’un token, de toute façon ?

Un token est essentiellement le mot de passe de votre bot; c’est ce que votre bot utilise pour se connecter à Discord. Cela dit, **il est essentiel que vous ne partagiez jamais ce token avec qui que ce soit, intentionnellement ou accidentellement.** Si quelqu’un parvient à mettre la main sur le token de votre bot, il peut utiliser votre bot comme si c’était le sien, ce qui signifie qu’il peut effectuer des actes malveillants avec.

Les tokens ressemblent à ceci : `NzkyNzE1NDU0MTk2MDg4ODQy.X-hvzA.Ovy4MCQywSkoMRRclStW4xAYK7I`. S’il est plus court et ressemble plus à ceci : `kxbsDRU5UfAaiO7ar9GFMHSlmTwYaIYn`, vous avez copié votre clé secrète client à la place. Assurez-vous de copier le token si vous voulez que votre bot fonctionne !

[Cours Discord.JS](../Cours%20Discord%20JS%2003ecf82600a547fd8bf5a00a6a4c5454.md)