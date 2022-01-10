# The Amazing Dinosaur Adventure

## Game Description:

In this game, the user plays as a big green dinosaur that has to evade through various obstacles such as dangerous piranha plants from Mario and deadly blue birds. The player avoids these impediments by jumping over them before they hit each other. The user clicks the left button on the mouse in order to jump and dodge these objects. The player's score is continuously incremented on the top left side of the screen. If the user clashes with either one of the obstacles, the game ends, and the score resets to 0. Each time the game is restarted, the player's highest score is remebered and saved. See below for more information of different objects, their classes, and how the game works.
### Usage:

Left button on the mouse = Makes the dinosaur jump up and down.

#### Classes:

##### Background Class:

This class is made to set up the jungle/forest background that can be seen in the game.

###### Dinosaur Class:

This class is made to create the green dinosaur that the user plays as. Only one dinosaur object is created in frame. It was originally created in pixilart.com, and it was custom drawn by me.
![4892843bb6f725d](https://user-images.githubusercontent.com/90793175/148822474-2b6a9513-c408-4bf4-8af9-8813520255f1.gif)


**Plant Class:**

This class is made for the piranha plants, one of the objects that the player has to evade. Similar to the dinosaur, only one plant object is created in frame. However, several loops are placed in the code that makes it seem like there is an endless amount of piranha plants that spawn after the user jumps over one. It was originally created in pixilart.com, and it was custom drawn by me.
![60e35049feb3497](https://user-images.githubusercontent.com/90793175/148823150-ad626640-8153-459a-990e-55f6ac71a1e4.png)


**Bird Class:**

This class is made for the blue birds, another obstacle that the user has to avoid. There is only one bird object created in frame, but also includes loops that makes it seem like there is an infinite number of birds that appear after the dinosaur clears one. It was originally created in pixilart.com, and it was custom drawn by me.
![7010c4ed1e1564c](https://user-images.githubusercontent.com/90793175/148823328-d6be1b18-4131-4c83-b4f0-ecf9abd8add6.gif)

**Paint Method:**

This class is responsible for drawing all the objects to the screen. It is also in charge of updating all the behaviors of the objects, and what they need to do. This is why the lines of code that create the collision of the game are included underneath the paint method.
![IMG_3748](https://user-images.githubusercontent.com/90793175/148826533-a445534c-aa1e-419f-97c3-8fc582da71e4.jpeg)

**Collision:**

Collisions between the dinosaur and the various obstacles are a very important factor in this game. This is because when the dinosaur comes in contact with either the plants or the birds, the game stops and the user's score is reset to 0. Collisions are coded by using if statements that check to see whether or not the position of the dinosaur is overlying the position of either the plant or the bird.

**How objects are created:**

The objects in the game are created under Frame(). The individual objects in my game are created regularly without any for loops.

**Support:**

For support you can speak to Mr. David, my AP Computer Science teacher.

**Roadmap:**

If any future updates were to happen, I would most likely add power-ups that the dinosaur can use throughout the game. Some ideas that I have for power-ups that I could incorporate into the game would be a power-up that makes the dinosaur invincible to all the objects for a few seconds, a power-up that allows the dinosaur to shoot laser beams from its eyes or fireballs from its mouth that can defeat the objects for a short time, and a power-up that makes the dinosaur grow bigger and stronger. With this power-up it would take three hits for the obstacles to kill the dinosaur. I think it would also be nice to have the background of the game change every so often as the dinosaur is running.

**Contributions:**

Contributing is available to anyone who chooses to do so.

**Authors and acknowledgement:**

The background image is from google. All other images are from pixilart.com, and are custom drawn by me. This game was coded by me. Big thanks to Mr. David for guiding me through this entire project, helping me with any problems I had, and showing me the basics of how to code a massive project just like this. I would also like to thank Isaac Valle for helping me to fix considerable issues I had while coding this game. This game was based on the popular no wifi google dinosaur game.

