---
layout: post
title:  "Documentation for the Meteor social website"
date:   2017-02-26 13:50:39
categories: others
---

A social-network that I made and I use to grow my developer skills, and I found that is very suitable for that role, as I tried a lot of CSS techniques for its responsiveness and look, also wrote a lot of JavaScript methods, functions and plane JavaScript code: and this is how it looked when I started: <a href= "https://zhivkoz.github.io/Portfolio/static/projects/Old-but-nocomment.PNG">PREPARE tab</a>.. was such a long time ago(2 years), and this is how it looks now:
<a href="https://zhivkoz.github.io/Portfolio/static/projects/change-is.PNG">PREPARE tab</a>.

I chose lightcyan, grey, black and white, which are the funny colors of the website and the pallete as I wanted something unique and simple to work with for a start. The name.. of the social network is because, I wanted the website to have a lot of hidden features and to feel like playing a game with other people- finding new features of the website collecting likes and making the users more powerful and only a gossip about how that happen to be left of, maybe too ambitious but could be done yes.. MeteorJS with its connected clients feature seems like a perfect choice.
Also I wanted to make a cool website to get a developer job, not to be a competition to facebook :D.. just to make that clear.



Also it is on a Heroku hosting: <a href="http://enigmatic-lowlands-70396.herokuapp.com">http://enigmatic-lowlands-70396.herokuapp.com</a>, and here are accounts to login:

    username: Guest1, password: 123456
    username: Guest2, password: 123456

The website runs poorly on a Safari web browser.

Meteor packages used:

    meteor-base@1.0.4               # Packages every Meteor app needs to have
    mobile-experience@1.0.4         # Packages for a great mobile UX
    mongo@1.1.14                    # The database Meteor supports right now
    blaze-html-templates@1.0.4      # Compile .html files into Meteor Blaze views
    reactive-var@1.0.11             # Reactive variable for tracker
    jquery@1.11.10                  # Helpful client-side library
    tracker@1.1.1                   # Meteor's client-side reactive programming library

    standard-minifier-css@1.3.2     # CSS minifier run for production mode
    standard-minifier-js@1.2.1      # JS minifier run for production mode
    es5-shim@4.6.15                 # ECMAScript 5 compatibility for older browsers.
    ecmascript@0.5.9                # Enable ECMAScript2015+ syntax in app code
    shell-server@0.2.1              # Server-side component of the `meteor shell` command

    accounts-ui@1.1.9
    accounts-password@1.3.2
    session@1.1.7
    iron:router
    npm-bcrypt@0.9.2
    mrt:moment-timezone
    themeteorchef:bert
    msavin:mongol
    meteortoys:toggle
    cfs:standard-packages
    cfs:gridfs
    easy:search
    easysearch:elasticsearch
    easysearch:autosuggest
    check


Rules:
The social network has features where one can easily register with only a username and password, a user can - post into the main front page, a Post cannot be empty or longer then 4368 characters, each user can delete his own posts, and each post can be liked once by every other user but cannot be liked by the author of the post, the most liked post goes into the header of the website under the logo, as a greeting message of the website. Each Posted Post has the username and the user's profile picture, and the time when it has been posted. Every user can upload 1 profile picture .jpg, .png or a .gif file directly into the database as their profile picture. Every user of the social network can follow other users, and they are being listed on ones own front(main) page, and if one clicks on the followed user, that user's posts will be filtered and showed on the front(main) page. The main page is designed to be an infinite scroll with no restrictions. The website also has a Search Page where one can see all the users that has been registered or can search for a username and can follow them. There is also a chat where the chat is limited to 200 Post-like messages and the other are being hidden, the chat shows a timestamp of the messages and the users profile picture.
