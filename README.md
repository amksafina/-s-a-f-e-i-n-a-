{
    "name": "Video x Music Stream Bot",
    "description": "Telegram bot for Streaming Video & Music trought the Telegram Group Video Chat, powered by pytgcalls and pyrogram",
    "logo": "https://telegra.ph/file/541813404cfcafdd29127.jpg",
    "keywords": [
        "pytgcalls",
        "telegram bot",
        "video stream",
        "pyrogram"
    ],
    "website": "https://t.me/VFF35",
    "repository": "https://https://github.com/SDFGQ12",
    "success_url": "https://t.me/hama_refaat",
    "env": {
        "API_ID": {
            "description": "قم بوضع الايبي ايدي هنا",
            "required": true
        },
        "API_HASH": {
            "description": "قم بوضع الايبي هاش",
            "required": true
        },
        "BOT_TOKEN": {
            "description": "قم بوضع توكن البوت الخاص بك هنا",
            "required": true
        },
        "BOT_USERNAME": {
            "description": "قم بوضع يوزر بوتك بدون علامة @",
            "required": true
        },
        "BOT_NAME": {
            "description": "قم بوضع يوزر بوتك بدون علامة @",
            "required": true
        },
        "ASSISTANT_NAME": {
            "description": "قم بوضع يوزر الحساب المساعد بدون علامة @",
            "required": true
        },
        "SESSION_NAME": {
            "description": "قم بوضع كود تيرمكس هنا",
            "required": true
        },
        "SUDO_USERS": {
            "description": "قم بوضع ايدي المطور الاساسي",
            "required": true
        },
        "GROUP_SUPPORT": {
            "description": "ضع هنا يوزر جروبك بدون علامة @",
            "required": true,
            "value": "VFF35"
        },
        "UPDATES_CHANNEL": {
            "description": "ضع هنا يوزر قناتك بدون علامة @",
            "required": true,
            "value": "S_F_M_1"
        },
        "OWNER_NAME": {
            "description": "ضع هنا يوزر المطور بدون علامة @",
            "required": true,
            "value": "Safeina1bot"
        },
        "ALIVE_NAME": {
            "description": "اتركها كما هي",
            "required": true,
            "value": "Safeina..🎶"
        }
    },
    "addons": [],
    "buildpacks": [
        {
            "url": "heroku/python"
        },
        {
            "url": "heroku/nodejs"
        },
        {
            "url": "https://github.com/jonathanong/heroku-buildpack-amksafina.git"
        }
    ],
    "formation": {
        "worker": {
            "quantity": 1,
            "size": "free"
        }
    },
    "stack": "container"
}
