# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Luis Chure

Time spent: 8 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![]((![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/102558066/161198286-1479dfa7-2406-4b52-9e17-b507039c4171.gif)
))
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Codepath Courses- required steps

https://youtu.be/PvUexC0-D2s - Create Repository, Commit, and Push using GitHub Desktop 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I faced when completing this assignment was understanding the fundamental keys of these frontend languages such as JavaScript, html, and CSS but after quickly understanding a lot of the basic concepts it began to flow more naturally. I was stuck on a part of programming the memory game where after each failed attempt the game did not restart back at position one instead it started where it fell off, where the player guessed incorrectly. After looking over and analyzing the portion of the program that handles guesses and the game logic with guesses, I was able to pinpoint my mistake. I studied and reviewed back to understand this concept of guesses and realized that I had not put this code of line “guess counter = 0;” to the beginning of the “playCluesequence” function. The importance of this line of code tells the computer to reset the counter which then restarts the sequence all over instead of allowing the computer to play the next clue sequence and therefore confuse the player and skew the game. One more area of difficulty I had to overcome was understanding the concept of playing a sequence of clues. I had a challenging time grasping this but after taking it one step at a time studying the functions “setTimeout” and the constants “clueHoldTime” everything began to make sense. The importance of these two functions supports the program to give the players the clues of the sequence. “setTimeout” schedules when a clue is to be called out and to be more intricate, we apply a delay for the sequence of clues. The delay comes from the “clueHoldTime” which makes the clues to come out one after the other instead of all at once and each clue being spaced out by a set time of 333 milliseconds. Getting each button to correspond to the correct pattern of secret clues played a significant role in allowing me to understand my mistakes from the sequence of clues portion of the program. The pattern array that was done in the initial stages of the program was referred to in the “playCluesequence()” function through the use of the “i”th element. This determined which button should be used for the next “i”th clue in other words, which button should be used according to the order of the secret pattern array. This program had its challenges but once completed it gave me an amazing understanding of new concepts.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After experimenting with these frontend languages, seeing how different it is from a backend language which is what I'm more used to it makes me question how exactly could both frontend and backend languages be merged to produce a full stack developed program. The two seem to be behaving similarly in some ways but applying both together seems to be very intricate and difficult, which makes me curious how that process is done. I would assume that a full stacked program with backend and front-end languages would work beautifully as on paper they sound as if they work together, it would be great communication on both ends but just figuring out where to start really takes me out of my comfort zone as it's something I'm not familiar with but I am open to learn it.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project I would focus on the sequence array of clues portion of the program. I would like to implement a way to randomize the secret array of sequences after each failed attempt. I will do this to increase the difficulty of the game if a player restarts after guessing incorrectly, they can't rely on the same repetition of sequences to eventually win the game. I would like to make that sequence random each new attempt with new clues. In addition, if a player is great at the game implementing a score board I feel as though it would be a great addition to the game. Letting the player see their high score and record allows an increase in competitiveness and therefore creates a longer duration of gameplay.  



## Interview Recording URL Link

[My 5-minute Interview Recording](

https://user-images.githubusercontent.com/102558066/161196839-77aac7f2-2104-4c58-b9ad-c2b1a0eedb4d.mp4

 ) 


## License

    Copyright Luis Chure Ortiz

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
