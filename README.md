"# chatbot" 
# Get Started With Tightrope Chatbots
Tightrope's chat functionality is built on BotPress, an open-source chatbot project that enables the development of intelligent and flexible chatbots. You can read more about BotPress on [their website](https://botpress.io) or [their GitHub](https://github.com/botpress/botpress).

Embedding your bot
--------------------
You can find the embed script in your Tightrope account under the 'Acquire' tab. Paste the embed scipt anywhere you want the bot to interact with visitors, before the closing body tag. Ensure you do not change or delete the brokerage ID field in the init script, as tha is required for bot functionality.

# Options
Adding A Bot Name
--------------------
You can set the bot's name with the botName field in the init script. The bot name will be displayed at the top of the bot window and helps to personalize your bot to your brand. If left blank, the bot's name will be 'Bot'.

Adding A Conversation Description
--------------------
You can add a conversation description with the botConvoDescription field in the init script. The conversation description will show up directly below the bot's name in the top of the chat window. This is a good place to provide context. Let users know what the bot's goal is (ex. 'I'm here to help you find deals') or add a witty line (ex. 'I'm a bot, beep beep boop boop') that fits your brand's style. If left blank, the bot will not have a conversation description at all.

Adding custom CSS
--------------------
You can add a custom CSS file to the embed script. A list of example classes that can be styled can be found on [Botpress' GitHub](https://github.com/botpress/botpress/blob/archive/10.x/packages/channels/botpress-channel-web/README.md#customize-the-look-and-feel). Do note that these classes may change from time-to-time and Tightrope cannot guarantee the current or future functionality of any 3rd-party code.
