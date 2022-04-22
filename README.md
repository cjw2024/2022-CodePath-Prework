# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Caden Wright**

Time spent: **#** hours spent in total

Link to project: (https://glitch.com/edit/#!/fossil-cooked-troodon)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] List anything else that you can get done to improve the app!
  - Each time a life is lost it alerts the user
  -

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/hMLUbExnmc.gif)
![](http://g.recordit.co/SU6iHzMufK.gif)
![](http://g.recordit.co/QJB4rtdD8c.gif)
![](http://g.recordit.co/XOoxeAfY69.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   [To complete the coding project I referenced the Grasshopper coding application that helped me learn how to code in javascript, CSS, and html]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   [A challenge that I ran into was creating a timer for the user to have a limited amount of time and having the tones be more complex. For the timer, when I tried to implement it would give the user unlimited time or no time at all and after trying to find a resource I was unsuccessful in getting it to work. With sounds, I found audio files to fit each animal pattern and tried to link the file to the button so when it is clicked the sounds play. When trying to add the audio files, no sound was playing, and when the button was clicked. Other than the 2 features that I was unable to get to work I struggled with getting the images on the buttons to all have the same borders and fill the button equally. I ended up having to edit the files themselves so that they were all the same size and shape. The last thing that I thought was difficult but was able to work through was the pattern playing quicker each time through, originally I had it just decrement the hold time but then it would be quick the next game through so I had to make it equal to 1 sec each time a new game starts. Lastly, if the user got the guess wrong it would still decrement the time, so when they have more than one life the time decremented too much. To fix this every time a user had a wrong guess the hold time would increase to counteract the decrease and stay the same time.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   [What I still want to know about web development is how sites like the one I created are implemented to mainstream servers.  I have no idea how sites go from being created to being able for thousands of users to interact.  Another question I have about web development is why some sites crash under high traffic and others don’t if they are created equally.  I don’t have a great understanding of networking and how things are implemented past designing it and would love to learn more.  Web development is so prevalent and the only way I know of designing and creating them is with javascript, html, and css I want to know if there are better/more efficient ways of creating sites.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   [If I had a few more hours to work on this project I would implement other buttons that control the game.  Once a timer is implemented a pause button would be one of the most important buttons that need to be created so that the user can pause if needed.  Another button I would want to add is a replay button so if the player needs the pattern to repeat they can click the replay button and it just replays the same pattern again.  The combination of the pause button and replay button, I believe would make the user interface and interaction more accommodating and enjoyable for the user.  Another visual aspect I would add is showing the lives the user has used in some way shape or form, whether it is with reading X’s showing up when there is a mistake or another form of showing. ]

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/o0gY4A8lutw)

## License

    Copyright [Caden Wright]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
