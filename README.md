#imamaquaman
This is a shooter game.

This little project contains 3 levels.

#how to play it?

Spam your spacebar while moving your character (or just use AC)

You can control your character by using the "a" and "d" key.

There are several rules tho :
1. Don't miss the enemies more than 3 times.
2. Don't get hit by the enemies.
3. Get your best score.

#How i create this game

I use the Pygame libary for this project.

By the way, the FPS limit is 60.

Created the GameSprite class as the main class for the game
  By this way, i created the player, enemiems, bullets sprites (by inherite the GameSprite class to other classes).

I choose an outerspace theme for this project (so that's why the enemies are aliens and the background is in the space)

I create a simple condition for charactor motion:

 Eg :  If key "a" is preseed : 
         move the character 10 pixels to the left

       If the key "d" is pressed :
         move the character 10 pixels to the right

       If the spacebar is smashed:
         Fire...
          

The game still contains many bugs, glitches, lags, etc :
- The hitbox is inaccurate
- The aliens sometimes went "crazy"
- The window sometimes lagged if you have POTATO END PC
- ...

Have fun!
