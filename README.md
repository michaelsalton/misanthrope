Game: misanthrope
Developers: Benjamin Oliveria, Michael Salton
----------------

Play the game: https://michaelsalton.itch.io/misanthrope

In our demo for "Misanthrope", players will get to play as Timon in a small level with collectibles that present different endings and enemies that are in your way. Below are the core features players will find in this demo.

![image (1)](https://github.com/michaelsalton/misanthrope/assets/58754252/838674ca-e585-4348-ad85-3db4edb9a169)


**Exploration/Collectibles:**
For this demo-level, there are numerous collectibles players can find and the ending of the game changes based on how many collectibles the player finds. Some are out in the open for the player to see but some are hidden in paths that deviate from the main one. To help players explore the world more, we have a camera system that allows players to rotate it so that they can view the world in different ways and see paths they might not have been able to without changing the camera. This gives players the ability to explore around the level and feel like they are getting something out of it. In addition, having multiple endings can entice players to replay the demo so that they can experience all of the endings.

![image (2)](https://github.com/michaelsalton/misanthrope/assets/58754252/3b561e35-0e72-4e61-a250-1e3a42a746c8)


**Movement/Combat:**
Timon has a basic 3-hit moveset that can be timed input or spammed with “E”. The first two hits are regular slashes that go diagonal then horizontal but the third move is a small AOE in which Timon spins around damaging everything around him. With the way the code was done, spamming can allow players to execute their combos as fast as possible for an aggressive playstyle whereas timing the attacks present opportunity for the combo to be canceled with a dash. The dash is a movement and combat ability binded to “Space” that allows players to get through the map faster as well as evade enemies whether it be dashing away from them or right through them. 

![image (3)](https://github.com/michaelsalton/misanthrope/assets/58754252/c8e7c097-2f0a-4348-9d12-a234d7c52510)


**Audio/Details:**
We wanted to make this demo feel like a legit game instead of a school project so we added audio to everything and other small details/additions that make the game more immersive and enjoyable to play. Audio for Timon includes swing sounds and effects for his combo, randomized footstep sounds, dash sound, and a sound for when an enemy hits to help the player know they have been hit. Enemies have been given spawn animations so that they don't just "appear" in front of the player and this too comes with its own sound effect along with sounds for when enemies are hit and die. In addition, we chose to add background "ambience" instead of music to fit the theming of our game better. Furthermore, we created a different kind of HP indicator for enemies in that a “life force” in the shape of a diamond is lost when they take damage as opposed to a standard “bar” of health that depletes as they take damage. The HUD also features an icon and similar “life force” HP for Timon that appears on the bottom left of the screen.

![image (4)](https://github.com/michaelsalton/misanthrope/assets/58754252/268f6ffb-a3f3-4dd7-bbde-2303711ee3a2)


**Level Design**
The game features numerous level design features such as procedural object spawning, various shaders, and dynamic lighting.The game uses an algorithm called Poisson Disc Sampling to instantiate objects like detail meshes around the world. The algorithm ensures no two objects spawn on top of eachother which maximizes performance.The game features a toon shader to give some of the elements a cartoony or retro feel. The game also features a dynamic day cycle where as time passes by the sun will go down, simulating a sunset. The game was meant to have a sort of sketchbook look to it. The trees and other details were hand drawn and placed around the world as billboard sprites. This gave the game a cool effect and used an interesting blend between 3D and 2D.

![image (5)](https://github.com/michaelsalton/misanthrope/assets/58754252/9d586091-7204-4d11-932a-e41599c7dd7a)
