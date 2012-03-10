---
layout: post
title: "All fun and games"
date: 2012-03-09 23:24
comments: true
categories: [Multi Mega Man, EiT, Garbage Alert, Large and Heavily Armored Warships]
---
As a part of my courses this uni semester, I am expected to make no less than two games as part of two different teams on two different platforms. I also like to keep myself busy on my afternoons off. These projects are the (unfinished) results of these endeavours.


## Garbage Alert
This semester I'm enrolled in the course *Experts in Teamwork*, a course where the goal is to experience teamwork across diciplines. Here I'm a part of a band of students set out to make a game with a purpose: encouraging recycling and reuse. Drawing inspiration from Jane McGonigal's book ["Reality is Broken"](http://realityisbroken.org/) ([obligatory inspiring TED-talk](http://www.ted.com/talks/jane_mcgonigal_gaming_can_make_a_better_world.html)), the goal is to explore the possibilities for making recycling more fun by the use of video games.

With the group growing up fond of real time strategy games such as Age of Empires and Red Alert, the solution we came up with is *Garbage Alert*. *Garbage Alert* is (set to be) a multiplayer real time strategy game where the objective is to compete with each other in in having the cleanest, most habitable (utopian) island. Here, garbage and waste are resources that the players are to utilize in achieving this goal, by upgrading and improving their island infrastructure, attacking other players and repelling attacks on themselves.

{% img left http://farm8.staticflickr.com/7061/6968022307_27d6852376_m.jpg 240 235 'The epic title screen of Garbage Alert' 'Garbage Alert title screen' %}

Development has started, and is set to commence rapidly in the following weeks.

### Technologies
Even though our main platform for the game, *Garbage Alert* is to be realised as a HTML5 and JavaScript game. This is mostly due to the groups experience in such technologies, as well as not everyone having the correct tools and neccessary equipment to be able to efficiently develop natively for smart phones. Additionally, *Garbage Alert* is set to be a rather simple tech demo
illustrating our game concept, rather than having a complete product at the end. HTML5 and JavaScript is thus deemed to be an appropriate platform for such a game.




## Large and Heavily Armored Warships
As part of another course I'm taking this semester, where the goal is to be taught and exercise use of software achitectural patterns and best practices, an Android game is to made. As the goal here is to have a more or less complete game at the end of the semester, the game is to be a clone of a well known game: *Battleships*. Here, players are taking turns in trying to hit and destroy the other player's battleships.

### Technologies
The game is to be developed using the vanilla Android API, drawing on a canvas element. Third party helper frameworks and toolkits has been considered, but due to lack of documentation (I'm looking at you, [AndEngine](http://www.andengine.org/)), and/or the software being too costly for such a small project as LaHAW, we quickly decided not to use such software.




## Multi Mega Man
{% img right http://farm8.staticflickr.com/7192/6968016805_b0f4174ee9_m.jpg 235 240 'Multi Mega Man screenshot' 'Multi Mega Man screenshot' %}

As part of a series of weekend projects that I've tinkered with, resulting in among other things, a persistent world multiplayer *Conway's Game of Life*, I now have embarked upon the journey og making a game on my own. 
Me being a huge fan of old school platformers, I started cloning [*Mega Man*](http://en.wikipedia.org/wiki/Mega_Man). Drawing upon my experience from the *Game of Life* project, I quickly realised one thing 10 year old (and 25 year old) me would have loved: multiplayer. Thus, Multi Mega Man was born. The game is still in a very infantile state, but has working multiplayer, weapons, projectiles, powerups and more or less pixel perfect emulation of the classic Mega Man physics.


### Technologies
Both Muli Mega Man and Conway's Game of Life are realised with use of HTML5 canvas and JavaScript. Server-wise, I'm using [node.js](http://nodejs.org) and [socket.io](http://socket.io).

[Multi Mega Man is available on Github.](https://github.com/tkbremnes/Go-Right-)


## Level editor
{% img right http://farm8.staticflickr.com/7204/6968016873_28841fe1a8_m.jpg 240 165 'Level editor screenshot' 'Level editor screenshot' %}

To aid in the development of Multi Mega Man, Garbage Alert and future grid based games, a simple level editor is in the making.

[The level editor is available on Github.](https://github.com/tkbremnes/Simple-Map-Editor)