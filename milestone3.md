---
title: Milestone 3
layout: template
filename: milestone3
--- 

## Milestone 3

Our third milestone consisted of finishing implementation of all the mechanics of the game as well as improving our aesthetic features such as sprites, sound effects, and music.

## Final video

<iframe width="560" height="315" src="https://www.youtube.com/embed/Lztm7CF4xOU?si=606fs1I6pTSfp0h0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Kailee:

- Added the score system to subtract revenue and added the skeleton for gaining revenue. Made sure the score was visible and carried over between scenes.
- Made sure that customer orders and their timers persisted between scenes, but weren't visible when they were in the cup game. The order game objects included multiple children which meant a way needed to be found to toggle all children as well.
- This introduced a bug that made fish sometimes spawn under the persistent game objects (the customer orders) and couldn't be clicked.
- Another bug was that it would spawn new instances after switching scenes which was also corrected
- Created and designed the end screen which included making sure all the objects were destroyed but keeping the final score shown
- Additionally, did a lot of writing for the website and started on the tutorial

### Carol:
- Drew and animated the cat 

<img src="Assets/catbob.gif" height="150px" alt="Cat idle animation" style="border-radius: 5px;">
<img src="Assets/catdrag.gif" height="150px" alt="Cat being dragged animation" style="border-radius: 5px;">

- Added background music that muffles when the player enters the cup screen.
- Added other additional sound effects: Customers making angry noises when they receive the wrong order or don't receive an order in time, having a cash register sound when successfully completing a customer's order, and the slurping sound effect when sucking up a fish
- Implemented customer order success, verifying that you brought the correct order to the customer and awards points accordingly
- Implemented the overall game timer so that the game ends after approximately 3 minutes
- Implemented pressing escape will close the game
- Fixed bugs regarding boba color and audio issues

### Kristyn:

- Implemented the trash can functionality to the game. Players can drag a boba drink from the table to the trash can and it will be thrown away. The free space can be filled with a new boba drink.
- Created 2 new boba assets. One without a straw and with a straw. New colors were choosen to reflect reaslistic boba colors.

<div style="padding: 20px;">
<img src="Assets/boba.png" height="150px" alt="Cat idle animation" style="border-radius: 5px;">
<img src="Assets/strawBoba.png" height="150px" alt="Cat being dragged animation" style="border-radius: 5px;">
</div>
- Implemented the logic for the shutter. When pressing the button on the counter, the shutter will go up and down. When the shutter is down, the player is unable to go to the cupscene. The shutter stays up or down between scenes.
- Made a table asset and fixed a bug with the completed boba layering 

<img src="Assets/table.png" height="150px" alt="Cat being dragged animation" style="border-radius: 5px;">
