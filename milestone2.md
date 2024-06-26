---
title: Milestone 2
layout: template
filename: milestone2
--- 

## Milestone 2

For our second milestone, after doing some rough development from milestone 1, we were able to have a better vision of the gameplay. Therefore, we made some changes to the game mechanics.

- Instead of 2 conveyor belts, there is a single conveyor belt
- Customer orders that you need to match with the correct color boba
- You either get all the fish or none. You can save 3 drinks at a time that have no fish
- A shutter that can be toggled with a button so that you can only catch the fish when the shutter is down, and you can only see and deliver the orders when the shutter is up. (In lore, this is because the customers can't see a cat sucking fish out of the boba of course!)
- Simplified score system to add and subtract money

<img src="Assets/brainstorm2-1.png" alt="first-brainstorm" style="display: block; margin-left: auto; margin-right: 20px; float: left; width: 45%; margin-bottom: 50px;"/>

<img src="Assets/brainstorm2-2.png" alt="first-brainstorm" style="display: block; margin-left: 20px; margin-right: auto; float: right; width: 45%; margin-bottom: 80px;"/>



## Progress video

<iframe width="560" height="315" src="https://www.youtube.com/embed/myoKa336WG0?si=zb7Xc-G3D-WG2Sxp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Cup game and spotlight (Kailee):

- Finished up implementation of the cup game so that the spotlight worked properly. Before, the spotlight was off-center and wasn't properly aligned with the mouse.
- Implemented color to carrying over from the drink conveyor belt to the background color of the cup game. Needed to create a HexToColor converter in the process.
- In addition, formatted our project site and added the functionality for multiple pages.

### First mockup of the shop screen (Carol):

- Implemented the customer spawner where a new customer will spawn in every 5 seconds, unless there are already 3 customers at the counter.
- Each customer has a timer that dictates how long they will stay at the counter before getting upset and leaving.
- Every order has a randomized color of one of three boba flavors that they can order, which are the same as the three that is going down the conveyer lines.

### Redesign and random movement of boba (Kristyn):

- Made a transition from the shop scene to the cup scene where the camera pans over to the boba the cat was dragged to
- In the cup scene, when clicking on a fish, made the fish counter in the bottom left corner count down. When it reaches 0, the scene shifts back to the shop screen.
- Made the boba move back and forth randomly in a radius aroumd its initial spawn point 
- When going back to the shop screen after all fish have been taken out of the boba drink, a boba drink with the corresponding color appears on the table. The table can hold up to 3 boba drinks and if the table is full, the player can't go into the cup scene. 
