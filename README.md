# Security Test Bot
Most discord servers prevent normal bot spamming but not simple selfbot spamming. This tool can be used to test if your moderation bots prevent self-bot spamming.

Please do not use Security Test Bot for malicious purposes.

## Requirements
[Node.js](https://nodejs.org/en/)

## Build Instructions
Install the required modules first by running

`npm install`

To start the bot run

`npm start` or `node bot.js`

## Usage
Create a new user account, get its Discord token (click [here](https://www.youtube.com/watch?v=tI1lzqzLQCs)) and place the token in token.txt on the first line.

Next, create a new channel in your server that the bot can spam in.

Finally, join your discord server, start the bot, and type `!start` in the channel you want to spam.

## Common Errors
Invalid Token: If your token is valid, make sure that tokens.txt is one line with no spaces
