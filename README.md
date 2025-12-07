# ⚽ ScoreFlow WebApp

Telegram WebApp per visualizzare partite di calcio in tempo reale con widget API-Football integrati.

## 🚀 Deploy su Vercel

1. **Collega questo repository a Vercel:**
   - Vai su [vercel.com/new](https://vercel.com/new)
   - Importa: `preziosicanicatti-beep/scoreflow-webapp`
   - Click **Deploy**

2. **Ottieni l'URL:**
   - Dopo il deploy, copia l'URL (es. `https://scoreflow-webapp.vercel.app`)

3. **Configura Telegram Bot:**
   - Apri [@BotFather](https://t.me/BotFather)
   - Usa: `/newapp`
   - Inserisci l'URL di Vercel
   - Aggiungi al bot con bottone WebApp

## 📱 Features

- 🔴 **Live Matches**: Partite in corso con aggiornamento automatico ogni 30 secondi
- 📊 **Widget API-Football**: Widget ufficiale integrato
- ⚙️ **Filtri personalizzati**: Imposta gol minimi e campionati preferiti
- 💾 **Cache intelligente**: 60 secondi di cache per ridurre chiamate API
- 🎨 **UI Telegram**: Tema adattivo Telegram con colori dinamici

## 🛠️ Tecnologie

- **Frontend**: HTML5 + Vanilla JavaScript
- **Telegram**: Web App API
- **Widget**: API-Sports widgets v2.0.3
- **Hosting**: Vercel (CDN globale)
- **Caching**: Cache-Control headers (1 ora)

## 📊 Struttura

```
scoreflow-webapp/
├── index.html      # WebApp completa
└── vercel.json     # Configurazione deploy + cache
```

## 🔗 Links

- **Repository Bot**: [scoreflow](https://github.com/preziosicanicatti-beep/scoreflow)
- **API-Football**: [api-football.com](https://www.api-football.com)
- **Telegram WebApps**: [core.telegram.org/bots/webapps](https://core.telegram.org/bots/webapps)

---

Made with ⚡ by ScoreFlow Team
