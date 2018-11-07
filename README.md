# hugbot

> TIME FOR GROUP HUG

A friendly bot for your Discord server.

http://pbfcomics.com/wp-content/uploads/2016/04/PBF115-Hug_Bot.jpg

## !colourme <hex>

 - Checks if the `"🎨 #<hex>"` role exists
 - If it does exist, check if user already has the `"🎨 #<hex>"` role
   - If they do, send hex stripe embed "you already have this colour"
   - If they don't, apply then send hex stripe embed "you now have the colour `<hex>`"
 - If role doesn't exist, create it and apply then send hex stripe embed "you now have the colour `<hex>`"

## !help

 - Help message with list of commands
 - React with :red_circle: to delete message, deletes after 5? minutes