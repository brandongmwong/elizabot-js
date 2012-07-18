elizabot-js
===========

Eliza JS bot based on www.masswerk.at/elizabot and http://en.wikipedia.org/wiki/ELIZA

Usage:

var elizabot = require('./elizabot.js');

elizabot.start()          // initializes eliza and returns a greeting message

elizabot.reply(msgtext)   // returns a eliza-like reply based on the message text passed into it

elizabot.bye()            // returns a farewell message