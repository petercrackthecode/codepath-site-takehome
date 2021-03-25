# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Peter Nguyen**

Time spent: **1** hour spent in total

Link to project: [CodePath Takehome by Peter Nguyen](https://codepath-site-takehome.glitch.me/)

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

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![Demo gif](https://cdn.glitch.com/ef489ece-1019-43ce-965e-d42ec678da27%2FCodePath%20SITE%20takehome.gif?v=1616637835467)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here:
   - [CodePath SITE prework guide](https://courses.codepath.org/snippets/summer_internship_for_tech_excellence/prework?utm_campaign=CodePath%20SITE%202021&utm_medium=email&_hsmi=112744221&_hsenc=p2ANqtz--oNHagDN6dRCiiFHDuzdLbx1M1UVrfyPGyvb0qfTkFg-kkx3w0YqhbB2-tHBCuUptBxTuTaJ1OMqAUn-LVnDtYqlUjryhe4ZcRRQJcqnPJhUACZ0s&utm_content=112744221&utm_source=hs_automation#heading-1-expectations)
   - [UI Gradients Generator](https://uigradients.com/#Roseanna)
   - [W3 school button styling guide](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_buttons_animate3)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words):
   - I have never used Glitch before, so navigating through the application was a new experience for me. Learning to implement the `JavaScript AudioContext` library also requires reading other materials to help myself familiar with the API.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words):
   - In React we pass in a function reference to the onClick API instead of a full function with parameters like in vanilla javascript like this example. I wonder why do we have that difference?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words):
   - Enhance the UI so the buttons' color get randomly generated as four different colors every time you reload the page.
   - Build the app in React to have a cleaner application.
   - Print the number of rounds that the user has passed, and how many rounds remaining.

## License

    Copyright [Peter Nguyen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
