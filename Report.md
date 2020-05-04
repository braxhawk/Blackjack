## Description
Our final project is an accessible version of the game Blackjack that can be played by visually impaired people. Blackjack is a popular casino game, but is also known as 21 if gambling is not involved. To make the game a little more involved, we will be incorporating Blackjack’s idea of a Dealer. The game has a simple, high-contrast user interface that is keyboard and screenreader friendly. This will assist those who experience visual impairments in playing Blackjack successfully.

## Intended Audience
The intended audience is people of all ages, with addition support for those with visual impairments. While this game is popular among adults, there is also an educational component for children who may be learning basic mathematics. Because the goal of the game is to ultimately reach 21 without going over, or being too low, the player will need to know exactly what their cards add up to, and have critical thinking skills on when to ask for another card or when not to. People with visual impairments can view the large print, high-contrast user interface, use the in-game text-to-speech option, and/or interact with the game using compatible screenreaders detailed below. 

## Frameworks and Technologies
In creating the Webapp, we used React.js, VS Code, the Web Speech API, and Git. This allowed us to collaborate as a team and utilize an environment we were familiar with. The React.js framework allowed us to ensure an interactive user interface that is efficient and flexible. We equipped the Web Speech API in order to provide text-to-speech capabilities. In addition, we utilized aria attributes to all necessary components in our code and equipped WAVE (web accessibility evaluation tool) to help ensure our game was accessible and compliant with W3C-WAIT.

## Compatibility
For screenreaders, we currently support macOS and iOS VoiceOver, in addition to Chrome's browser-based screenreader, ChromeVox. There is also in-game text-to-speech capabilities for reading the dealer and player hands aloud. macOS VoiceOver can be enabled using Cmd-F5 and iOS VoiceOver can be enabled through Siri. For Windows users or any others experiencing difficulty with the native screenreader, we recommend downloading the ChromeVox extension provided by Google Chrome v81. Otherwise, players can use the "Read Cards" option provided in game. 

## How to Play
For simple use and deployment of Blackjack, one would only need to go to https://braxhawk.github.io/Blackjack/src/ to play. Those who are unsure of the rules can learn how to play here: http://www.hitorstand.net/strategy.php.

## Problems and Future Directions
Some problems we encountered were deciding whether to utilize screenreaders or a web text-to-speech API. We first decided with using screenreaders such that users could have full control of the game, as some believe TTS can be too redundant or too brief for a given individual's needs. An issue that we encountered due to this, however, was cross-platform compatibility. Our game was made originally to be compatible for VoiceOver users, but other users who wanted to play experienced difficulties with their native screenreaders. We attempted to address by ensuring compatibility with a browser-based screenreader, ChromeVox. We later also added an in-game text-to-speech option for reading the cards aloud, both of which hopefully resolve compatibility issues. In the future, we hope to continue exploring compatibility with other screenreaders we currently don't have access to such as JAWS, Windows Narrator, and Android TalkBack. We also hope to scale our game into an all-emcompassing, "Casino" version of the game which could include varying Dealer difficulty levels, money/betting scenarios, and perhaps new games as well!


Credit for base game to: jayfreestone
