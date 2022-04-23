# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Joram Bosire**

Time spent: **17** hours spent in total

Link to project: (https://glitch.com/edit/#!/seemly-sprout-pint?path=script.js%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] User can see game stats for that session

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/A1Kh1rZ.gif)
![](https://i.imgur.com/Sb0sQGC.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
**1. Stack overflow**

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

**The main problem I faced during creating the submission was implementing the optional features. 
First of all, it took me quite a while to do the changing playback speeds at each turn. I knew I had to decrease my clue and pause times after each turn/guess but at first it wasn’t working well since the last pause time used in the previous game was being used as the starting pause time for the next game. Considering it was only a matter of placing the time deductions in the right place, I was able to quickly identify the correct function to place them.
The same applies to creating a random pattern for the games. I knew I had to create an array and fill it with random numbers similar to something I had done on a java project earlier on, it was just a matter of finding out the JavaScript syntax for it. A similar problem then arose where the game would create a random pattern for the first game, then the same pattern would persist to later games. Just as in the playback speeds, I was able to use knowledge I have from using java (especially knowledge on loops since all these functions seem to interact in one big loop) to find the appropriate place to place my pattern formation.
It took me quite a while to figure out a way to insert images on my buttons and various tunes instead of the tones provided. I figured out the appropriate methods and where to place them on stack overflow. After that it was easy to just give image path links to the methods to insert images. As for the music, it wasn’t so simple since I needed a particular type of music file and it took me quite a while to find the appropriate sample music files to use for the buttons.**


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

**Similar to the CodePath iOS course I took this semester, I’d like to know how to make data from a particular session persist to the next. For example, if we were keeping track of the stats for this game (number of wins and losses), is the data automatically saved online or does it have to be stored in a backend database like when dealing with iOS development.
I am more experienced with working on the backend aspect of programs so it would be refreshing to learning additional graphical components of web development. How to make the page more appealing other than just the basic color and font changes and add my own designs on the webpage.
I’d also like to learn how testing is done in web development, both unit and systems tests. I’m used to dealing with testing on app development and it would be interesting to also understand the workings of it when it comes to web development.**


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

**Considering it’s a memory game, it would be interesting to implement an algorithm that keeps track of a player’s stats over time and give a rough verdict on their memory ability and whether it’s improving over time as you play the game.
I would also add different game modes (for example easy and hard) to enable users test themselves. For example, have the music mix up for the buttons while the light stays the same or have the lights mix up while music stays the same so that people who primarily depend on either the tone or the lights are forced to approach the game differently. And I could also vary playback and guess speeds. Additionally, I would add special game modes so the game doesn’t become monotonous, such as a “reverse light-and-sound” where the pattern involves all but one button lighting up and sounding, or buttons switch positions on the screen during each sequence.
I would also work on making it more user-friendly by making it customizable. Users would be able to create their own patterns, increase or decrease the number of buttons and change button appearance and sound.**




## Interview Recording URL Link

[My 5-minute Interview Recording](https://vassar.zoom.us/rec/share/5q2UKOoUDWc2Tx4pDXB7JQrmF-WtNL65slt99_GqH3ujjzN3ZkmZr53Yk44uwqiH.q6woBB9duXR3Md2g)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
