To run the bot with Telegram integration follow these steps.

On a terminal:
```sh
ngrok config add-authtoken <NGROK TOKEN GOES HERE BUT IT WAS HIDDEN FOR SECURITY REASONS>
```
```sh
ngrok http 5005
```

You will see the new URL on the ngrok interface.
Copy it and paste it on [credentials.yml](https://github.com/pinnpin/Rasa_Chatbot_wTelegram/blob/main/AISTP2/rasa/credentials.yml) webhook_url for Telegram, leaving the /webhooks/telegram/webhook at the end of the URL.

Now, on another terminal:
```sh
rasa run
```
