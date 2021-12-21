![Workflow status](https://github.com/mbilousova/chat-bot-game/actions/workflows/main.yml/badge.svg)

# Simple Telegram based game

This project uses under the hood a popular java abstraction library for accessing Telegram Bot API - [org.telegram.telegrambots](https://github.com/rubenlagus/TelegramBots)

## How to

### Requirements
1. JDK/JRE 1.8
2. maven for dependency management and building stuff

### Step by step installation instruction
1. In your active Telegram account find a special bot [@BotFather](https://telegram.me/BotFather)
2. Then send command `/newbot`
3. Give a unique name to your new bot
4. Copy the telegram token to access the HTTP API
5. In your terminal/cmd run `mvn package`
6. In your terminal/cmd run `java -jar -Dtelegram.secret.key=MySecretKeyFromStep4 target/simpleBot-1.0-SNAPSHOT-jar-with-dependencies.jar`

### How to use

1. Open your Telegram app (mobile/Desktop)
2. Find your bot (which you have created in step 2 see previous section)
3. Start to send your guess to the chat and enjoy

![screenshot](https://raw.githubusercontent.com/devatlant/chat-bot-game/master/res/telegram_screenshot.jpg)


# Bilousova Marharyta
### QA Engineer

## Profil
Ingénieur de test logiciel avec plus de 2,5 ans d'expérience dans le développement d'applications web et mobiles agiles (Scrum, Kanban).

J'ai de l'expérience dans le test d'applications web et mobiles. Forte compréhension du développement Agile et des pratiques de test Agile.
Je suis très réactif aux besoins de l'entreprise et à l'évolution des exigences. 
Orienté client, orienté résultats et équipe, collaboratif et désireux d'apprendre. Mes compétences principales sont les tests fonctionnels.

## EXPÉRIENCE PROFESSIONNELLE
**août 2019 – Présent**

*Software Testing Engineer à EPAM, Khariv*

Projet: CTCO-ORKE, 
Replatform d'un système en magasin de 6 millions de lignes de code.

Le projet utilise des méthodologies agiles pour faire de l'ingénierie inverse du système existant.

**mai 2019 – juillet 2019**

*Stagiaire à EPAM, Kharkiv*

Projet : Portail de test

Projet interne pour la création et le passage de tests - plateforme de quiz pour les epamers.

