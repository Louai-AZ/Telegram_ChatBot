# Telegram_ChatBot

## How to run the code :

1. Clone this repository :
```ini
git clone https://github.com/Louai-AZ/Telegram_ChatBot.git
```
2. Create a virtual environment and activate it :
```ini
conda create -n OpAIenv python=3.7 -y 
conda activate OpAIenv 
```
3. Install the dependencies : 
```ini
pip install -r requirements.txt
```
4. Create a `.env` file in the root directory and add your OpenAI API key and Telegram TOKEN :

```ini
TOKEN = ""
OPENAI_API_KEY = ""
```

5. Start the bot :
```ini
python src/bot.py
```
6. Open Telegram and search for your bot username
7. Enjoy chatting with your bot!

## Telegram Sertup :
1. Search for "BotFather" in telegram 
2. Start Conversation : 
    - /newbot :
        - choose your bot name 
        - choose your bot username 
3. Copy Telegram Token
4. Click on the URL to start the conversation with your bot
