---
layout: post
title: #"Honours Project: Formal Grammars"
description: short project description
#permalink: /projects/honours/
#url: honours/
#date: 2018-11-18T12:33:46+10:00
#weight: 1
---

### honours ###

For my honours dissertation, I chose to explore procedural content generation and how formal grammars and rewrite systems could be used.

I entered the BCSWomen Lovelace Colloquium poster contest with an academic poster based on this project and won 2nd place in the 3rd/4th year undergraduate category.

I was originally inspired by the use of l-systems within computer graphics and through my research, discovered that formal grammars and other rewrite systems have been used for other areas such as map creation for a range of games. I wanted to explore the success of trying to combine the creation of various aspects into one project. 

I created a basic game description grammar that would allow a player to describe a game using a range of predetermined values in order to influence the end result (such as size, style, number of players). I then extended this out and implemented a probabilistic rewrite system within my Unity scripts that would create the map, allowing for an incredibly high number of possible different maps that would generate endlessly as the player progressed.

The approach for map generation involved defining allowed segment combinations through the grammar production rules and choosing one of these at random every time a new segment was required. The dungeon map was more complex than the platformer as I wanted the increase uniqueness by having the option of moving predominantly North, East, South, or West. This meant production rules had to be considered carefully to ensure no overlap of segments or backtracking, as this would likely result in an unplayable map. Full details of how I implemented this are available in my dissertation (available on request).

While there were occasional bugs that I could not fix before my deadline, the finished version is a fully working game generator that generates different variations of the game based on the options chosen. It can be played in the browser at my itch page.

Links: 
[\[Game\]](https://beckmcgowan.itch.io/honoursproject)
[\[Code\]](https://github.com/bmgamedev/Honours)
