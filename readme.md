Basic framework for a twitter bot to retweet posts by hashtag.

Change the params object in bot.js to change the bots behavior.
1. q - is the hashtag that you wish to search for.
2. result_type - can be set to recent or trending.
3. count - number of posts to retrieve.

Twitter limits requests to 
1. 180 requests per user in a 15 min window.
2. 450 requests per app in a 15 min window.