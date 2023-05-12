# twitterbot

This project was a short experiment with the Twitter API. 

Watsky is one of my favorite hip hop artists and he's hanging up his spurs, this year. I designed this Twitter bot with him in mind, basically as a way to "favorite" tweets with the hashtag "Watsky".

I used separate config and app files, bringing over my API keys, secrets and everything else from Twitter. I set up a function using specific parameters to run on execution of the file and, provided it doesn't run into any errors, it files a request to favorite whatever post it is currently looking at that matches the criteria.
