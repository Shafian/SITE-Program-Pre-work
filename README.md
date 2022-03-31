# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Al Shafian Bari 

Time spent: 8 hours spent in total

Link to project: (https://glitch.com/edit/#!/open-like-train?path=script.js%3A34%3A11)

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
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Required Functions: 1,3,4,5,6. Optional Functions: 1,2,3,4,7
![](https://i.imgur.com/93JJx0F.gif)


Required Functions 2,7 

![](https://i.imgur.com/LOkWtYH.gif)


Optional Functions: 6

![](https://i.imgur.com/7MbVBF7.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

webites: 
https://www.w3schools.com/html/html_images_background.asp

https://www.youtube.com/watch?v=33IinMVJf-M

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge I encountered was getting the game to play multiple clues. When I ran the game it would only play one clue and end. I overcame this problem by looking at my code in the script.js file. I started from top to bottom looking if I missed any brackets or braces. I was missing two in different places but after fixing that syntax error it still would only run once. So I started going more down in the script.js file and looking at every loop. I saw that I had two functions called guess and some code that did not belong there. When I cleaned up that section and tested it, it ran with multiple clues. Another challenge I faced was getting an image to pop up when the button is being clicked. I tried importing the images and linking them to the button in html file but it did not work. After doing some research I saw I had to put background-image: url(link); in the style.css file. I put this line in between each of the button's codes when it's being clicked. Next, I added an image to test it and it worked. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Some questions I have about web development after completing my submission is would I need to create a new html file if I wanted to make new page or a sub-page when clicking on a button? Would the style.css file would be conncted to all the new pages or just one page? Is there a specifc set of space given on the screen for the website? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project I would try adding a scoreboard. For example, the game would count how many buttons you would get correct in a row before losing. Then there would be an area where it would tell you your score during that game. Also, an area to keep your high score on the screen. I would have also tried adding an action when the user won the game. For example instead of just "you win" screen, confetti would pop out plus the screen saying "you won". 


## Interview Recording URL Link

[My 5-minute Interview Recording](https://ccny.zoom.us/rec/share/vXtGQvBtVw0REXVJ0ml7bMf_epUAEID6VGT6PFbCQSDHdIT7LHblLyXUHWZyodgV.EX2knpixGIOuzk8z?startTime=1647197898000)


## License

    Copyright Al Shafian Bari

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
