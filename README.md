# Mass Gmail Telegram Bot 🚀

A **Telegram Bot** for handling multiple Gmail accounts with ease.  
Built for power users who need **mass email automation** without compromise.

---

## ✨ Features
- 🔑 OAuth2 Gmail authentication (IMAP & SMTP)  
- 📥 `/inbox` — read latest emails  
- 🔍 `/find` — search emails by sender  
- 📖 `/readall` — mark all emails as read  
- 🗑 `/delete` — delete emails by sender  
- 📤 `/send` — send emails 
- 🔔 `/notif` — enable/disable real-time notifications  
- 👤 `/id` — view user/chat ID  
- 📩 Auto detect forwarded messages in private chat → show original sender/chat info  

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourname/gmail-telegram-bot.git
   cd gmail-telegram-bot
   ```

2. **Create Google Cloud Project**, enable Gmail API, and download `client_secret.json`.

3. **Setup `config.json`**
   ```json
   {
     "TELEGRAM_TOKEN": "YOUR_TELEGRAM_BOT_TOKEN",
     "ADMINS": [123456789, "adminusername"],
     "GMAIL_EMAILS": ["account1@gmail.com", "account2@gmail.com"],
     "MY_CHAT_ID": -1001234567890
   }
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the bot**
   ```bash
   python bot.py
   ```

---

## 📞 Contact
For purchase or setup assistance: [t.me/fadhilaziz](https://t.me/fadhilaziz)
