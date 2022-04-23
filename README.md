# CodePath-Pre-work
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Jessica DeWitt

Time spent: 6 hours spent in total

Link to project: https://light-and-sound-memory-game-1.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* -[x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* -[x] "Start" button toggles between "Start" and "Stop" when clicked. 
* -[x] Game buttons each light up and play a sound when clicked. 
* -[x] Computer plays back sequence of clues including sound and visual cue for each button
* -[x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* -[x] User wins the game after guessing a complete pattern
* -[x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* -[x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* -[x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![]https://recordit.co/335cCt8Q0h


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
For my project, I used resources from W3Schools, CSS Background generator, and help from CodePath TAs.


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The main challenge I experienced during the project was the playing clues. I followed the instructions thoroughly, however I had a difficult time with creating the pattern and setting the time for the user. In the live preview, it did not seem to work therefore I knew there was an error in my code. I went back to read the references carefully and used W3Schools to learn more about functions as additional help. It turns out that I was missing a key component in my code which was the for loop in the playClueSequence function.

I also encountered another challenge while creating the style and layout of the game. As the color buttons needed to be changed on click, I wanted to add my own personal style to the buttons. I went to a CSS generator website to find gradient background colors and solid colors. My goal was to have the solid colors on click and have the gradient colors to be off click. After inputting the background colors, the buttons still appeared grey. I figured out that I did not have the parentheses in the correct place. Once fixing the issue, the button colors became visible.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have gained more knowledge in web development after completing this project. Judging from my overall performance, I would say that I can improve more on the back end of web development. 

There are many questions I have regarding web development. For example, is it possible to integrate an API into your website and how? Are other programming languages useful for different web applications? What kind of websites do you use python for and what kind do you use javascript for? And what tools do you use for debugging to improve the site.

I would like to learn and know how much I can accomplish with web development. I have many ideas that I would like to bring into action to share and hopefully become helpful with others. I believe I would be able to do this if I continue to learn more about the back and front end of web development.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, I would definitely add more creative features to the look and layout of the game. I would like to have created a galaxy theme game with an animated background. To accompany the theme of the game, I could have made the buttons into different planets in the solar system. Thus creating an interactive learning game. Insteading of a guessing game,the sequence of the buttons (planets) would have taught the user the planets closest and farthest from the sun. Completing this project has encouraged me to create my own games in my free time and learn more javascript and css styles.





## Interview Recording URL Link

[My 5-minute Interview Recording] https://www.kapwing.com/videos/626378b905ee8c00e8c78301


## License

    Copyright Jessica DeWitt

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
