---
layout: project
type: project
image: img/circle/circle-game-cover-image.png
title: Circle Projectile Game
permalink: projects/circleprojectile
# All dates must be YYYY-MM-DD format!
date: 2020-12
labels:
  - Java
  - Processing
summary: A simple mouse game made for ICS 111
---

<div>
    <iframe
        width="640"
        height="480"
        src="https://www.youtube.com/embed/6IGUEUj7Cbw"
        frameborder="1"
        allow="autoplay; encrypted-media"
        allowfullscreen
    >
    </iframe>
</div>

## Overview
This is a simple circle projectile game I made for ICS 111 (introductory Java course) where the player controls a circle and has to dodge other projectiles. The game ends when the player hits a projectile enemy. This was made using the software sketchbook [Processing](https://processing.org/). The game consists of the player (small blue circle) and the following **three types of enemies** spawning at random times:
 - Common **dark purple circle** projectiles which enter and leave the game window. They spawn at random locations, and have random velocities
 - Smaller **pink circle** projectiles which are slightly rarer, and bounce off the edges of the game window, staying in the game until it ends. There is a maximum of 3 that have a possibility of spawning
 - A **stalker** identical to the common enemy that slowly moves toward the player and follows it around. There is only a maximum of 1 stalker that can spawn

## What I learned and Improvements
This project utilized skills we had been learning in the class all semester including Java and object-oriented programming. It was also the first time I did anything that wasn't text-based in the console window, so I ended up learning a lot. I learned about taking input from a mouse and having that carry over player character on screen, while also dealing with the variety of ways the enemies could move with differing velocities and locations. I think the three enemies I created had a good enough variety so it could hopefully keep the game interesting and challenging for the player. And through using Processing, I gained experience in using new, unfamiliar technologies and syntax.

The above gameplay footage was made by combining clips of multiple attempts at the game. So it is evident that one improvement I can make is to have a start window and a prompt asking if the player wants to play again. This would be much more intuitive than having to exit the window and run the program again each time.

Source: <a href="https://github.com/KaileeHung/circle-projectile-game"><i class="large github icon "></i>KaileeHung/circle-projectile-game</a>

<br><br>


