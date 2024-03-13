---
layout: post
title: #Projects
#description: short project description
name: Projects
permalink: /projects/
#date: 2019-03-28T15:14:54+10:00
#weight: 5
---

Personal Projects
============

### Nightmarevania/FATALengine ###

Nightmarevania is a 2D platformer being created as the demo for the underlying engine (WEngine). Using the SFML and Box2D libraries, FATALengine started life as a piece of coursework built with a peer in my 3rd year of university. Over time, I have continued to develop it, adding more features and overhauling large amounts of the existing codebase to remove redundancy, and improve reusability. It utilises an Entity-Component System, and while there is no graphical user interface, building games with the engine is similar to using Unity due to the ECM pattern.

Engine features include: tile loader system for building the levels from csv tilemaps; custom composite tile collider generation to overcome the issues with using Box2Ds colliders; an audio system; spritesheet animation system; dialogue system that handles text skipping; saving and reloading game data and game settings/preferences; many of the key components required for gameplay such as health, state machine and decision tree for use in NPC AI, different NPC behaviours, combat system which handles standard and special attacks, item interaction/pick-up; scene handling; button re-mapping and multiple window resolutions. 

For distribution, I used NSIS to make a custom installer.

I still develop this project in my free time, using trello as my main project management tool. 

See also: [\[Download on itch.io\]](https://beckmcgowan.itch.io/nightmarevania) [\[Watch on Youtube\]](https://www.youtube.com/watch?v=i66mSaSfBrw&feature=youtu.be)

---

Academic Projects
============

### Honours Project ###

My fourth year honours project looked at how formal grammars could be used to procedurally generate customisable games with a high degree of re-playability to appeal to non-programmers. This project won second place in the '3rd/4th-year Undergraduates' category at the BSc Women Ada LoveLace Colloquium and the Lawrence Ho second place student prize at my University for best dissertation related to games technology.

See also: [\[Play on itch.io\]](https://beckmcgowan.itch.io/honoursproject) [\[View on Github\]](https://github.com/bmgamedev/Honours)

### Screen Space Ambient Occlusion ###

Coursework for a fourth year module on games engineering concepts. I chose to look into SSAO with the intention of comparing other ambient occlusion approaches, but unfortunately the planned end result was never achieved due to issues in the framework I chose to use. The coursework still passed due to the work that went into it, including the extensive bug testing.

See also: [\[View on Github\]](https://github.com/bmgamedev/SSAO)

### SPARKSUB ###

A project made for a University lecturer to assist with module delivery, created as part of my professional internship while undertaking my degree. The project is used to visually and interactively demonstrate whether a student has written the correct SPARK code with regards to a spec given on submarine behaviour. Any scenario where the expected behaviour has been improperly implemented will result in a player death on the game interface. In addition to the Unity component, I had to build the framework that would allow the student work to be turned into a library that Unity could interact with.

See also: [\[View on Github\]](https://github.com/bmgamedev/SparkSub) [\[Watch on Youtube\]](https://youtu.be/M75ososC8bY)

### NORSEMAN ###

Coursework for the third year group project at University. Created as part of a team of six, Norseman is a first-person escape room style game created using Unreal Engine.

See also: [\[Download on itch.io\]](https://beckmcgowan.itch.io/norseman) [\[View on Github\]](https://github.com/stefan-codes/Norseman)

### COMPUTER GRAPHICS ###

Coursework for a second year module at University looking at various computer graphics techniques, custom shaders and OpenGL. My project focused on post processing effects shaders, colour deficiency, fresnel, masking, and noise textures with procedural generation.

See also: [\[Watch on Youtube\]](https://youtu.be/86b3x9w9SLw)

---

Game Jams
============

### SURFS UP ###

Global Game Jam game created in 2017 using Unity and C#. The player controls a constantly moving character over three levels, ducking and jumping to avoid moving and static obstacles that get progressively more challenging.

See also: [\[Play on itch.io\]](https://beckmcgowan.itch.io/surfsup) [\[View on Github\]](https://github.com/bmgamedev/SurfsUp2.0) [\[Watch on Youtube\]](https://www.youtube.com/watch?v=mmVPk7zm8ss&feature=youtu.be)

### Marathon ###

Global Game Jam game created in 2018 using Unity and C#. The player naviagtes through three levels to exit a compound. Each level requires a key to unlock the exit and the player is forced to sneak around guards as there is no combat.

See also: [\[Play on itch.io\]](https://beckmcgowan.itch.io/ggj18marathon) [\[View on Github\]](https://github.com/bmgamedev/Marathon)

### Snowfall ###

A Ukie Student Game Jam game created in 2018 using Unity and C# as part of a team. Two players battle to be the last one standing in a cavern with only moving platforms, spikes, and snowballs that freeze player movement for a few seconds. Also, the player controls will re-map every 10 seconds to new keys.

See also: [\[Play on itch.io\]](https://beckmcgowan.itch.io/snowfall)

### MORTRIDEN ###

Created as part of a personal Game Jam challenge using Unity and C#. The player has a time limit to escape limbo but needs to answer various riddles along the way. Answers are scattered throughout in the form of notes that the player needs to return to the riddle-giver in order to pass.

See also: [\[Play on itch.io\]](https://beckmcgowan.itch.io/mortriden) [\[View on Github\]](https://github.com/bmgamedev/Mortriden) [\[Watch on Youtube\]](https://www.youtube.com/watch?v=oDz1S-UQvLU&feature=youtu.be)

### SOULGRABBER ###

Created as part of a personal challenge, using Unity and C#, this game is a reskin of frogger with an underworld theme. The player is death and needs to cross styx to fetch souls on the other side to bring them into the afterlife. The boats and fireballs are procedurally generated and each level gets progressively harder for an infinite amount of levels until the player loses all lives.

See also: [\[Play on itch.io\]](https://beckmcgowan.itch.io/soulgrabber)