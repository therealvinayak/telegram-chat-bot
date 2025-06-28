# 🤖 AI-Powered Telegram Chatbot

A GPT-3.5-powered Telegram chatbot built using Python, Aiogram, and Flask. The bot responds to user messages intelligently using OpenAI's Chat Completion API and remains active via a lightweight Flask web server — ideal for deployment on Replit or similar platforms.

## 🚀 Features

- Handles `/start` and `/help` commands
- Generates AI responses using OpenAI GPT-3.5
- Uses environment variables for secure API key storage
- Keeps bot alive using a background Flask server (suitable for Replit)
- Clean, asynchronous structure with `aiogram`

## 🛠️ Tech Stack

- Python
- Aiogram
- Flask
- OpenAI API
- Telegram Bot API

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/telegram-chatbot.git
   cd telegram-chatbot
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Create a .env file in the root directory and add:**
   ```env
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token
   OPENAI_API_KEY=your_openai_api_key
   ```

4. **Run the bot**
   ```bash
   python main.py
   ```

## 📁 Project Structure

```
telegram-chatbot/
│
├── main.py         # Main bot logic and polling
├── example.py      # Flask web server to keep the bot alive
├── requirements.txt
├── .gitignore
└── README.md
```

## 🔑 Getting API Keys

### Telegram Bot Token
1. Open Telegram and search for `@BotFather`
2. Send `/newbot` command
3. Follow the instructions to create your bot
4. Copy the bot token provided

### OpenAI API Key
1. Visit [OpenAI Platform](https://platform.openai.com/)
2. Sign up or log in to your account
3. Navigate to API Keys section
4. Create a new secret key
5. Copy the API key

## 🚀 Deployment

This bot is designed to work seamlessly on platforms like Replit, Heroku, or any cloud service that supports Python applications.

### For Replit:
1. Import your GitHub repository
2. Add your environment variables in the Secrets tab
3. Run the project

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/therealvinayak/telegram-chatbot/issues).

## 👤 Author

**Vianyak Vinod**
- GitHub: [@therealvinayak](https://github.com/therealvinayak)

---

