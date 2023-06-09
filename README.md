# Chatbot IA pour Discord

Ce chatbot IA pour Discord est construit en utilisant le modèle #text-davinci-003 d'OpenAI et Discord.js. Le bot permet aux utilisateurs d'interagir avec le modèle IA via des commandes textuelles et vocales. Le bot peut rejoindre et quitter les salons vocaux, et il peut répondre aux questions des utilisateurs par texte ou parole.

## Fonctionnalités

- Le chatbot IA répond aux messages mentionnant le bot
- Il peut rejoindre et quitter les salons vocaux
- Il répond aux questions des utilisateurs par texte ou parole
- Il prend en charge la langue française avec Google Text-to-Speech (#gTTS)

## Prérequis

- Node.js v16.6.0 ou supérieur
- npm

## Dépendances

- openai
- discord.js
- gtts
- @discordjs/voice
- fs
- @discordjs/opus

## Configuration

1. Clonez le dépôt ou téléchargez le code source.
2. Installez les dépendances en utilisant `npm install`.
3. Remplacez `<API_KEY>` par votre clé API OpenAI dans le code.
4. Remplacez `TOKEN_DISCORD` par le jeton de votre bot Discord.
5. Exécutez le bot en utilisant `node index.js`.

## Utilisation

- Pour inviter le bot à rejoindre un salon vocal, tapez `!join` dans le salon textuel lorsque vous êtes dans un salon vocal.
- Pour faire quitter le salon vocal au bot, tapez `!leave` dans le salon textuel.
- Pour faire parler le bot avec un message texte dans le salon vocal, tapez `!speak <votre texte>` dans le salon textuel.
- Pour poser une question au chatbot IA ou entamer une conversation, mentionnez le bot dans votre message (par exemple, `@AIChatbot Comment est le temps aujourd'hui ?`).

## Avertissement

Ce chatbot IA est à des fins de démonstration uniquement. Veuillez prendre en compte les limitations de text-davinci-003 et être prudent lors de l'utilisation du bot dans des salons publics. Il est recommandé de vérifier et de filtrer les réponses de l'IA avant de les utiliser dans un environnement en direct.
