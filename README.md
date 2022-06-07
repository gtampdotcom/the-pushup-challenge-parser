# 2022-06-08
# the-pushup-challenge-charity-scraper for Streamer.bot-0.1.8

C# script for https://streamer.bot (v0.1.7) that scrapes the total donation amount from a https://www.thepushupchallenge.com.au charity page, saves it to a text file and outputs it to Twitch chat.

Copy the big line of text below, run streamer.bot, click on the Actions tab, right click, select import and paste the text into the Import String textbox.

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

If you want it to periodically check the total and post it in chat when it changes, add a Timed Action in streamer bot:

Settings > Timed Actions > pushupchallengeTimer, set the interval to 30 seconds or whatever delay you think is best.

You can also fetch the total on demand with a command, click Commands tab, right click, add command, set action to pushupchallengeCommand

The default text is "Total: $0", you can change it by editing the C# code under "Sub action > Execute code".

This is unofficial and not endorsed or supported by the pushupchallenge. Use at own risk. They may block too many requests or break compatibility at any time.
