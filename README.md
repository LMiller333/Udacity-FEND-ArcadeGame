# Classic Arcade Game Clone (for Udacity FEND Nanodegree)

This is a modified version of the classic arcade game "Frogger." Although the example from Udacity showed the bugs as the enemies, I decided to flip the paradigm a bit and show the human as the enemy that the bug needs to dodge. 

## How to Load the Game

There are two ways to play. You can either check out the live version available on my GitHub personal page (https://lmiller333.github.io/frontend-nanodegree-arcade-game/index.html) or you can download or clone this repository and launch the index.html file in your browser. 

## How to Play

You are the bug, and you are trying to cross the road to enjoy a nice swim in the lake. Use your arrow keys to cross the road, but be careful! There are many boys walking (and running) across the road and they will squish you. 

## Key Functions & Files

/js
* engine.js includes the game engine, which performs the initial rendering and then redraws/updates the screen over and over, to create the appearance of moving enemies
* app.js includes the properties and methods for the game objects (enemy and player), including functions for moving the player, managing a collision, recording a win, and resetting the game
* resources.js is an image loading utility

/images
* contains image assets for the game

/css
* contains (minimal) styling 

/audio
* contains audio files for sound effects


## Built With

* JavaScript game engine, image loading utility, & assets (provided by Udacity)
* Audio files from Mativve and HonorHunter

## In Development

Upcoming features include levels with increased difficulty, more player stats, and the ability to choose your player.

## Acknowledgments

Thank you to Mativva and HonorHunter for the audio clips!
* win.wav file created by Mativve via https://freesound.org/people/Mativve/sounds/391539/ licensed under Creative Commons attribution license 3.0 unported https://creativecommons.org/licenses/by/3.0/
* collision.wav file create by HonorHunter via https://creativecommons.org/publicdomain/zero/1.0/. Licensed under Creative Commons CC0 1.0 https://creativecommons.org/publicdomain/zero/1.0/
