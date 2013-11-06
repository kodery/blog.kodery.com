---
published: true
category: update
layout: post
---

The core reason for making Kodery is so we could share a library of code snippets with teams we work with. But everyone has their own way of working, so we needed to make it easy to integrate into any work-flow.

Since day one, we've known Sublime Text is a crazy-popular editor, it's actually what we use on a daily basis, so naturally, our first intergration is a Sublime Text plugin!

To use it, all you need to do is:

1. Install the [Kodery package](https://sublime.wbond.net/packages/Kodery) in Sublime Text.
2. Generate a token in [account.kodery.com](http://account.kodery.com)
3. Add that token to your Sublime User preferences (Prefrences > Settings - User), like so:

        "kodery": {
            "token": "your_64_character_token_will_go_here_without_these_underscores"
        }

Remember to make sure your prefrences is valid JSON!

Enjoy!

![](/_posts/kodery-sublime.gif)
