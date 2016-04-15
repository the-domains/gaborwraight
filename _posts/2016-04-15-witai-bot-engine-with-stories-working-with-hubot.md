---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: A script to get wit.ai intelligence and natural language understanding into hubot
datePublished: '2016-04-15T11:40:13.131Z'
dateModified: '2016-04-15T11:39:59.733Z'
title: Wit.ai Bot Engine with stories working with hubot
author: []
sourcePath: _posts/2016-04-15-witai-bot-engine-with-stories-working-with-hubot.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: witai-bot-engine-with-stories-working-with-hubot/index.html
_type: Article

---
# Wit.ai Bot Engine with stories working with hubot
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/7660d208-3feb-4d2a-977a-41e2e9dd5e0f.jpg)

This week Facebook announced together with wit.ai their new strategy on bots. Microsoft did a similar move two weeks ago and I must say this is very inspiring technology. We have an instance of rocket.chat, an open source slack alternative running in our company and I wanted to give this a try. We already had a hubot running but to be honest, it's not very user friendly. It's just like Siri or OK Google where you have to know the exact commands to trigger something. As an example you have to say: Alfred weather Munich to get a forecast coming from a script. If you said Alfred what's the weather in Munich it wouldn't work because it only responds to the correct trigger. There's a list of commands when you call Alfred help but that list is extensive and not very user friendly. 

wit.ai now does the natural language understanding magic. LUIS is an API from Microsoft which is very similar but requires more coding for the story part. This is why I chose wit.ai for us. Everyone can use the web interface to build stories and teach the system. Our Bot Alfred instantly got so much smarter. You can now write him direct messages about how tracking of hours works or specific company internal tasks should be done and he will point you to the appropriate tutorial we already have. Great stuff for new Employees or if you forgot where to find something. 

Another great feature of wit.ai is the Inbox wehere basically every request is stored. I can now look into this inbox and see what the users asked the bot. If it makes sense, I will then create a story for these requests and the next time this intent is asked, it will be answered. 

If you are interested in how the whole connection from wit.ai via hubot to rocket.chat works you can see what I did here: