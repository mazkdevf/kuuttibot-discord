# kuuttibot-discord
KuuttiBot for Discord!

!!! REMEMBER NOT TO COMMIT THE API. IF YOU DO, YOU CAN RECREATE IT FROM DISCORD DEVELOPMENT PORTAL! !!!

Get token for your bot

1. Go to Discord development portal (https://discord.com/developers/applications/)
2. Create new application
3. From the menu on the left, find _Bot_
4. From there you can find the token
5. Add privileged gateway intents from the same page all three (Presence Intent, Server Members Intent, Message Content Intent)
6. From _OAuth2 -> URL Generator_ you can create invite link with proper permissions.


Setting up development enviroment

1. Clone repository
2. Rename env.example > .env and fill in the token
3. Run "npm install"
4. Ready to go! Run the bot with _node app.js_ or start dev server with _npm run dev_