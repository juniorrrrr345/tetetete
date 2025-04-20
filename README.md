# Telegram Bot avec Telegraf

## Lancement

1. Crée un fichier `.env` à la racine avec :
   ```
   BOT_TOKEN=ton_token
   MONGODB_URI=ton_uri_mongodb
   ```

2. Lance le projet :
   ```
   npm install
   npm start
   ```

## Déploiement Render

- Type : **Background Worker**
- Start Command : `node index.js`
- Root Directory : (laisse vide si tout est à la racine)
