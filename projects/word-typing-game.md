---
layout: project
type: project
image: images/wg.png
title: Word Typing game using SFML
permalink: projects/word-typing-game
# All dates must be YYYY-MM-DD format!
date: 2019-05-04
labels:
  - C++
  - SFML
  - Team Project
summary: My partner and I developed a word typing game with SFML libraries using C++.
---

<img class="ui large centered rounded image" src="/images/wordgame-sfml.jpg">
<p align="center">SFML Libraries were used for graphical features</p>

This word typing game was create as a final project for EE 205. The game took a text file containing 100+ words and placed them on a randomly generated location on the unseen left section of the program screen. The words would then move right at a constant rate. The source code was created using C++ and SFML libraries for the graphical features. SFML was also used for input capture.

<img class="ui large centered rounded image" src="/images/wordgame-title.png">

The player was tasked to type the word before they exited out the left side of the screen. The program would track what the user was typing and highlight a word that matched their input. The words would also change color after they passed a certain section of the screen. The words would turn yellow if they went past half way, and then red when they were near the left side. If the user was to press enter with an incorrect word, the program would count an error. If the user typed a correct word and pressed enter, they would get one point. We also set a timer so that the user could see how much words they could type in one minute.

We also made sure that the user could not use the same word over and over. The words would be stored in a large array and once the user submitted that word it would be removed from the array. This was the longest program I've had to create so far in my studies as all files set the total line count to at least over 500.



