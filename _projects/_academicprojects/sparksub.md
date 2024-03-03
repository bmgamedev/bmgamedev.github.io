---
layout: post
title: #Sparksub
description: sparksub
#permalink: /projects/sparksub/
#weight: 3
---
### sparksub ###

I was approached by a lecturer during term to see if I had the capacity and interest to create a game over the summer that could be used by 4th students to test and demonstrate their coursework. The coursework involves programming submarine functionality with appropriate pre and post conditions to ensure there are no safety breaches. It is programmed using SPARK and testing/demonstrating this required writing out a list of text commands in GNAT Programming Studio and viewing a text output showing the results of each command. The game was to replace this process, allowing an interactive and fun way to interact with the SPARK code.

The submarine can carry out a range of functions, such as opening/closing doors, shooting torpedoes, or diving/resurfacing. If the SPARK source code does not have the appropriate preconditions to avoid triggering disaster under specific circumstances, the submarine will show a relevant death animation and make it clear what went wrong. This makes it easy for students and lecturers to see where things went wrong.

Since the coursework is written in SPARK, I had to write an interface in SPARK that would allow the outputs to be converted to C, allowing my Unity script to convert this to C#. The coursework is built into a DLL with this interface and placed into the Unity project build. I also created an installer and accompanying documentation to ensure as smooth a process as possible for the students using it.

Links: 
[\[Code\]](https://github.com/bmgamedev/SparkSub)
[\[Demo\]](https://youtu.be/M75ososC8bY)