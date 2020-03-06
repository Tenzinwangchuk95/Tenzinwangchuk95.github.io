---
layout: post
title:      "Variable scope"
date:       2020-03-06 06:32:59 +0000
permalink:  variable_scope
---


For my sinatra project i had built a app that could create user profiles and create multiple character sheets for Dungeons and Dragons. In most games of DnD players need to change their stats because they leveled up or even scrap charaters because they might have died.  Learning about basic CRUD functionallity help set up those features in my app like being able to update characters stats and deleting characters. When first building out my views and controllers i wasnt sure how information would be passed between the two. I had assumed that you could just set variables and they would know what it meant like Ruby usally does. Learning how Views talked to Controllers was a concept i struggled with. How much information can be passed between the two? Turns out a lot can if the right conditions are set. having instance variables hold on to information as its passed from view to post controller was when the customer to waiter analogy really clicked for me. The scope is widened when using instance variables and thats where i thought it would stop. When i learned about sessions i saw that there were ways to have values and information available almost anywhere with a simple addition of code in my application controller. Session are instances created when the app is used and is unique untill the app is logged out or closed. So with this hash that becomes unique evertime we open the app, it allows us to save user data with it so it persists even throughout different view and controllers. Scope of information is key when developing anything that has data being passed back and forth.
