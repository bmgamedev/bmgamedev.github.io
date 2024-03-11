---
layout: post
#title: SSAO
description: screen space ambient occlusion
permalink: /projects/ssao/
#weight: 2
---
### SSAO ###

For this project, I tried to implement a working version of screen space ambient occlusion in a custom OpenGL framework. The project was unsuccessful and I have started recreating it in another framework to begin working on another version that I plan to work on until it is successful.

I have tried to implement a standard SSAO algorithm, consisting of four passes:
 1. Calculate and store geometry data
 2. Calculate occlusion based on geometry data and hemisphere sampling data
 3. Apply slight blurring to avoid banding
 4. Apply lighting

Whilst the project was unsuccessful, I spent a great deal of time on the debugging process and learned a lot about OpenGL in the process.

Debugging the various frame buffers identified that the problem was incorrect occlusion calculations. I experimented with changing the depth mapping process but this was also unsuccessful. I also looked into other algorithms and made minor changes to reflect algorithms I found during my research but this was also unsuccessful (see report for details). The hemisphere sampling was the next avenue I wanted to explore to identify any issues, alongside moving to a different framework that was not still in development, but I did not have the time to do this before the submission date.

Links: 
[\[Repo\]](https://github.com/bmgamedev/SSAO)

Credits:
OpenGL Framework: Scott Davidson (https://github.com/WalterPlinge/Engin3D)