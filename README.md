ImageTwitterBot
===============

A small script that takes a folder as an input and twitts a random image in that folder every time you execute the script. If you combine it with cron or other task scheduler, it efectively becomes a very simple twitter image bot.

Also [check out my blog post about it](http://joaquinlp.me/blog/simple-twitter-image-bot-in-python/), there are examples and a bit more informartion. 

Setting it up
===============
You'll need tweepy. If you don't have it, run:

``` pip install tweepy ```

You'll also need to modify the script to specify your twitter authentication keys and the source folder for your images.

Usage
===============

Execute it. That's it.
You probably want to set it up on your crontab (or your favorite task scheduler) too :)

Full automatization
==============

If you use a scrapper and a couple of other tools you can automatize the hole process of downloading images and removing duplicates.

Live examples
==============
You can check out [@gentelindaOK](http://twitter.com/gentelindaOK) to see the result of executing the script every hour.
