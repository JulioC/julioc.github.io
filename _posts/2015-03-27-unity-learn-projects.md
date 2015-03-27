---
layout: post
---

I believe one of the better features of Unity is its learning resources, including the community made (on YouTube, specially) and [the official ones](http://unity3d.com/learn/tutorials/modules).

Following my plan of start learning the engine from the official tutorial projects, I decided to document the principal topics I would learn from each class, so I'd can recall later if necessary. This post is this a more elaborated version of this "log", accompanied of a brief review of the projects and the resulting game in some cases.

#### [Roll-a-Ball](http://unity3d.com/learn/tutorials/projects/roll-a-ball)

This is the most basic tutorial, presenting the basic tools on the engine: the Editor (navigation, hierarchy, prefabs), simple 3D objects (cubes and spheres), Components (basic physics), scripting, GUI (it still uses the old components) and publishing. The video is a screen cap with the tutor's voice.

Since it's just an introductory material, it does the job, but calls for an updated version.

__Time to finish:__ 1 hour
__Rating:__ :+1:

#### [Survival Shooter](http://unity3d.com/learn/tutorials/projects/survival-shooter)

This is a recorded session from the Unite 2014 training day, with explanations from three tutors and screen captures from the live development. The environment comes as a prefab, as some of the other elements from the game. This helps the game to get a "completeness" feeling at the end.

Even though the project is not so recent, I had no trouble with following it on Unity 5.

The only things I missed was a Menu system and a publishing step.

__Time to finish:__ 6 hours
__Rating:__ :clap:

##### Content Highlights

01. Environment setup
- Editor tools presenting
02. Player Character
- Prefabs
- Animation
- Animation Controller
03. Camera setup
- Scripting (moving the camera)
04. Creating Enemy #1
- Navigation System
05. Health HUD
- UI System
06. Player Health
07. Harming Enemies
- Particles
- Ray casting
08. Scoring points
09. Spawning Enemies
- Manager scripts
- More Prefabs
- Animation Overrider
10. Game Over
- Creating Animations with properties

##### Results

__Play [my version of Unity Learn: Survival Shooter](http://julioc.itch.io/learn-survival-shooter?secret=vfiQ7B5Yb6Fj5xwHUtr1gVeYig) on [itch.io](http://itch.io/)__
The lighting of my environment is really messed up and I couldn't find out why. Other than that, I'm happy with the result.

#### [Space Shooter](http://unity3d.com/learn/tutorials/projects/space-shooter)

This project appears to be made by the same author from Roll-a-Ball in a similar style. A nice a point is the way the tutor refers to the documentation, a good practice for any developer.

The tutorial was made for Unity 4 and, even with some compatibility annotations over the videos, it's quite hard to follow it with Unity 5.

The assets include some stuff that is not used at the end. Combined with the rushed rhythm at some points, it leaves a feeling that this project is missing a continuation.

__Time to finish:__ 4 hours
__Rating:__ :ok_hand:

##### Content Highlights

00. Introduction
01. Setting up the project
02. The player gameobject
03. Camera and lighting
- Camera modes
- Combining lighting
04. Adding a background
- Textures
- Shaders
05. Moving the player
- Scripts
- Serializable classes
06. Creating shots
- Particles shaders
07. Shooting Shots
- Instantiating
08. Boundary
- Triggers
09. Creating hazards
- Debugging
- Tags
10. Explosions
11. Game Controller
12. Spawning Waves
- Coroutines
13. Audio
- Unity 4 audio
14. Counting points and displaying the score
- Unity 4 GUI
15. Ending the game
16. Building the game
- Publishing with web player

##### Results

__Play [my version of Unity Learn: Space Shooter](http://julioc.itch.io/unity-learn-space-shooter?secret=uDKfJHdIF0nClkFs62s9IrT5c) on [itch.io](http://itch.io/)__
Comparing to the tutor's version, my asteroids collision looks a bit weird, maybe because I set the rotation on the collision frame too. I feel the lights are different, due to the Unity 5 new lighting.

#### [Stealh](http://unity3d.com/learn/tutorials/projects/stealth)

This is the biggest projects of all currently available, consisting of 25 videos, each having a duration of around 15 minutes. The classes are screen captures with some schemes used for explaining topics as vectors. The product is a game with interesting mechanics, basic enemy AI and a beautiful look.

As most of the other projects, this comes from Unity 4 and, in various points, it has great differences from Unity 5.

The names used in the classes and scripts sometime differs from the ones used on the assets, leading to some errors you will have to deal by your own. Still on the naming issue, I believe the project follows a bad naming convention for game objects, even thought the tutor talks about this on a class. I also missed a HUD.

__Time to finish:__ 8 hours
__Rating:__ :+1:

##### Content Highlights

__Chapter 1: Game Setup & Alarm Logic__

101. Stealth: Project Overview
102. Game Setup and Lighting
- Collision meshes
- Old lighting system
103. Alarm Lights
104. Tag Management
105. Screen Fader
- Scripting
106. Game Controller
- Sound fading
107. CCTV Cameras
- Animation
108. Laser Grids

__Chapter 2: Player__

201. Player Setup
- AudioSource
202. Player Animator Controller
- Blend Trees
- AvatarMask
- Animation Layers
203. HashIDs
204. Player Movement
- Using Hashes
- Temporary AudioSource
- Getting input
- Look Rotation
205. Player Health

__Chapter 3: Interactions__

301. Camera Movement
- RayCasting
302. The Key
- Apply root motion
303. Single Doors
304. Double Doors
305. The Lift

__Chapter 4: Enemies__

401. Enemy Setup
- Navigation
402. Enemy Animator Controller
- 2D Blending Tree :open_mouth:
- Inverse Kinematics intro
403. Enemy Sight
404. Animator Setup
- Helper classes
405. Enemy Animation
- Vectors
406. Enemy Shooting
- Inverse Kinematics
407. Enemy AI
- Navigation targets
- Using navigation way points
408. Stretch Goals

##### Results

__Play [my version of Unity Learn: Stealth](http://julioc.itch.io/unity-learn-stealth?secret=LSaf50Gcc7YQDHbsAKWNK8JNeY) on [itch.io](http://itch.io/)__
Except from the lighting, that is much brighter in my version, the result is very similar from what I expected.

### Next

There is one more official project available, a [2D Roguelike](http://unity3d.com/learn/tutorials/projects/2d-roguelike). I hope to get some time for it on the next week. There are the stretch goals from Stealth projects, which I'll be doing sometime in the future. I also plan to revisit the other projects and try to fix the issues I have on them as soon I feel more comfortable with Unity. I'll update this project with the information on these plans.
