🚀 AI ChatBot using LangChain & Google Gemini API

A powerful and lightweight AI chatbot built with Python, LangChain, and Google Gemini API, designed to generate intelligent and real-time streaming responses. This project follows a clean architecture, uses secure environment variables, and runs smoothly inside VS Code.

📌 Features

🔹 Google Gemini 1.5 Flash / Pro integration

🔹 Streaming responses using LangChain

🔹 Environment variable protection (.env)

🔹 Error handling for API issues

🔹 Easy to run and extend

🔹 VS Code + Python friendly

📂 Project Structure
chat_bot/
│
├── chat_bot.py           # Main chatbot script
├── requirements.txt       # Python dependencies
├── .env                   # API key (ignored by Git)
├── .gitignore             # Files excluded from GitHub
└── README.md              # Project documentation

🔑 Setup Instructions
1. Clone the Repository
git clone https://github.com/ahmedkorai786110-oss/Chat_bot
cd chat_bot

2. Install Dependencies
pip install -r requirements.txt

3. Add Your Gemini API Key

Create a .env file in the project folder:

GOOGLE_API_KEY=YOUR_API_KEY_HERE

▶️ Run the ChatBot
python chat_bot.py

⚙️ Technologies Used

Python 3.10+

LangChain

Google Gemini API

VS Code

dotenv

🛡 Security Notes

Your .env file is included in .gitignore to protect your API key.

Never commit API keys or sensitive data to GitHub.

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to improve.

📄 License

This project is released under the MIT License.

⭐ Support

If you find this project helpful, please star ⭐ the repository — it motivates future updates!
