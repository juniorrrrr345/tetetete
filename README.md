# Telegram Bot (Telegraf + MongoDB)

## Installation

```bash
npm install
```

## Lancement local

Créer un fichier `.env` avec :

```
BOT_TOKEN=TON_TOKEN
MONGODB_URI=URI_MONGODB
```

Puis :

```bash
npm start
```

## Déploiement sur Render

- Type de service : **Background Worker**
- Ajouter les variables d'environnement BOT_TOKEN et MONGODB_URI
