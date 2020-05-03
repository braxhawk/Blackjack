## Description
Our final project is an accessible version of the game Blackjack, that can be played by visually impaired people. Blackjack is a popular casino game, but is also known as 21 if gambling is not involved. It will utilize sounds to allow them to have a full experience without the limitation of relying on a solely visual user interface. This will assist those who experience blindness in playing Blackjack successfully. To make the game a little more involved, we will be incorporating Blackjack’s idea of a Dealer. This will allow for a more standardized measure of playing, and can make the game more accessible to visually impaired individuals. 

## Intended Audience
The intended audience is people with visual impairments, as the game will say all the possibilities and cards during the game. While this game provides great entertainment, there is also an educational component for children who may be learning basic mathematics. Because the goal of the game is to ultimately reach 21 without going over, or being too low, the player will need to know exactly what their cards add up to, and have critical thinking skills on when to ask for another card or when not to. 

## Frameworks and Technologies
In creating the Webapp, we used React.js, VS code, and Git. This allowed us to collaborate as a team and utilize an environment we were familiar with. The React.js framework allowed us to create an interactive user interface that is efficient and flexible. In addition we utilized Aria attributes to all necessary components in our code to ensure our game was accessible and completely compliant with W3C-WAIT.

We also used macOS VoiceOver compatibility to allow all the elements of the game to be read by a user. We created the user interface to have extra large extra large buttons and text, as well as high contrast, for low-vision users. VoiceOver can be enabled using Cmd-FN5 keys. An additional techology used was ChromeVox. This was added to make the game further accessible to those who may not have VoiceOver, another compatiable screen-reader.

## How to Play
For simple use and deployment of Blackjack, one would only need to go to https://braxhawk.github.io/Blackjack/src/ to play.

## Problems and Future Directions
Some problems we encountered were deciding whether to utilize VoiceOver or a Web to Speech API, because a visually impaired user can use VoiceOver, but has to manually go through all the elements on the page to read the card. In addition, if we utilize both the VoiceOver and API, then everything on the page is announced multiple times. Another problem we encountered is cross platform development. Our game is compatible for Mac Users, and does work properly for Windows users. In the future, we hope to scale our game into an all emcompassing, "Casino" version of the game. This would include adding an beginner, intermediate, and advanced game mode that would adjust the max hit of the dealer to varying levels. Additionally, adding VoiceOver compatiable betting scenarios would be a neat and further interactive feature to add.
