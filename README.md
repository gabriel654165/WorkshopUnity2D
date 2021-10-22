# WorkShop Unity 2D <h1>
<h4>
 In this workshop your going to make the begginin of a village manager game.

Your game at the end is going to looks like a clash of clan or a sims like (with much less functionalities)

# Prerequieres : <h3>
  - Download UNITY HUB
  - Add an account or create one
  - Add a licence to your unity hub
  - Download UNITY 2020 (lts)
  - Create a new 2d project
#
# Step 1 : Tilemap

 We are going to create a tilemap isometric (ISO).

Your objects in scene are on the left of your screen. You normaly starts with a MainCamera and thats all.

 - Create a tilemap with an ISO grid
 - Open your tile palet in : Window/2D/TilePalet, with this your going to create the base of the level
 - Create a new palette, and drag the assets Isometric sliced level in
 - Lets create a simple map then
 
![alt text](https://github.com/gabriel654165/WorkshopUnity2D/blob/master/images/Screenshot%20from%202021-10-13%2020-51-11.png)

# Step 2 : IU -> Create an inventory of objects

- Create an empty object named "IUManager"
- As child of it create a new objects : a canvas (in IU->canvas)
- Create a child object to your canvas, an image which going to be your inventory
- Create as many images for the objects you want to use

Now you have juste images no clickable or dragable

# Step 4: Scripts -> class and functions

 - New script assigned to your IUManager
 - Assign a GameObject for each of your objects in the inventory
 - Assign via the IDE your objects to your objects slots

You can create functions for : 
 - hight light the GameObjects 
 - play a sound
 - Instantiate a new object from you inventory (you probably write another script for the new objects in order to make it follow your mouse when you drag it, so now juste make it pop on positions x:0 y:0 z:0)
 
And in the next step your going to call them

# Step 5 : Events IU -> interact with your IU

 - For each object, add a new component : event trigger

Create an event for when your mouse is above your inventory items : 
 - when your mouse click down your items
 - when your mouse is survoling your item
 - ...
And call the functions you have made for theses events in the event trigger put the object which contains the scripts and choose the right function

# Step 6 : Make your object follow your mouse

 - Now you have an objects instantiate() for each click on your inventory's items.
 - In the objects that you instantiate, create a new script
Make sure when your objects is created :
 - He display at the screen (object.SetActive(true))
 - His position follow the moves of your mouse (you might convert the mouse position in world position)
 - And when the mouse release the click let the objects to his actual positions

![alt text](https://github.com/gabriel654165/WorkshopUnity2D/blob/master/images/Screenshot%20from%202021-10-22%2019-59-48.png)

# Step 7 : be able to remove the yet landed objects
Found a way to when you click on your objects instantiate and landed on your map, to drag them another time.
Advices : 
- You may check the psoitions of you mouse and the positions of your object, if the positions are the same check if the mouse is clicked and use the same script to make move it twice
- You might use the collider of your object (if it has no, create one)
- You might use a RaycastHit2D

#BONUS

If you arrived here well played, your going to add some cool features to your game so choose a boonus step and try to implement it (by level of difficulty)

# BONUS Step 1 : SoundDesign BONUS
Play sound on landing objects, survoling your items or just play music in loop in your game

# BONUS Step 2 : Camera moves
Add a script to your camera to make move it with your arrow keys