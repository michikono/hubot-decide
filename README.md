# Description

A hubot script that runs decide analysis of chatrooms its in. For example:

    you> We need to choose between wine or beer 
    hubot> let's go with beer!

The actual command breakdown:

    [decide|choose|pick] between(:) <option 1> and|or <option 2> (and|or <option #> ...)

# To install

Go to your bot's root directory and run:

    npm install hubot-decide --save

Add it to your `external-scripts.json`: 

    [
      "hubot-decide"
    ]

# To use

1. Invite the bot to rooms 
2. Let people chat

# Note

* The bot does not log chats
* The bot needs brain to work (https://github.com/github/hubot/blob/master/src/brain.coffee)
