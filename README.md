# [Flip It!](https://morphy80.github.io/Memory-Game/) - Milestone Project

## Table of Contents

- [**About**](#About)
    - [Why This Project?](#Why-This-Project)
- [**UX**](#UX)
  - [User Stories](#User-Stories)
  - [Research and Design](#Research-And-Design)
  - [Wireframes](#Wireframes)
- [**Features**](#Features)
  - [Functionality](#Functionality)
  - [Existing Features](#Existing-Features)
  - [Features Left To Implement](#Features-Left-To-Implement)
- [**Technologies Used**](#Technologies-Used)
  - [Version Control](#Version-Control) 
- [**Testing**](#Testing)
  - [Testing User Stories](#Testing-User-Stories)
  - [Responsive Testing](#Responsive-Testing)
  - [Validation](#Validation)
  - [Bugs And Errors](#Bugs-And-Errors)
- [**Deployment**](#Deployment)
  - [Repository Link](#Repository-Link)
  - [Running Code Locally](#Running-Code-Locally)
- [**Credits**](#Credits)
  - [Content](#Content)
  - [Media](#Media)
    - [Images](#Images)
    - [Sounds](#Sounds)
  - [Acknowledgements](#Acknowledgements)
  - [Disclaimer](#Disclaimer)

## About
The main idea of this project was to create and build a single page application with enough complexity that proves my skills as a front-end developer.
The creation of the game is targeting both my apprehention of Java Script and jQuery but the intrest of all categories of players , youngsters and adults, as well.

### Why This Project?

I created this game for the Interactive Frontend Development project. 
The project scope was to create the game using HTML, CSS and JavaScript, with the core focus being the functional logic created with JavaScript.

## UX 

### User Stories

As a player I want:
* to create a game that suits for all ages to improve visual memory, but focuses on children between 4-12 years old to learn colors and simple logical tasks.
* a simple, intuitive and user friendly game.
* that the player can select through 3 difficulty levels: easy mode, moderate and hard mode, that are available at any point of the game.
* an Info Modal about how to play the game.
* a reset button that can restart the game any time.
* that the timer can show me the actual time spend on this game.
* that the score can be presented as "Moves" which alows the payer to see how many cards are clicked upon.
* to hear relaxing nature sounds on the background when playing the game.
* to see a joyfull and neutral background.
* to hear sounds when I click and flip the cards.
* to hear a sound when I matched a pair of cards.
* to know when I have finished the game and to have the results displayed in a modal.
* to hear and notice when I win the game.
* to stop the sounds/mute whenever I want with a click of a button.
* to refresh the page at the end of the game.
* availability of the game on all the screen sizes and all platforms.
* no extra dependency, but the game itselft!

### Research And Design
For a better understanding how the game works and what functionalities should be implemented, I have researched multiple existing versions of the game. 
With all the information and sources founded on the internet as YouTube, Google Play Apps, Udemy, I have gained a clear idea for the design of my game version.

I have found out that the majority of the versions have either very colorful images or very pitchy tones which will make the player have difficulty focusing and memorizing the cards. 
Due to this reason I have chosen this particular design that renders only basic colors that are very easy to understand and keep a visual representation in the memory. 
Besides, all the colors are named accordingly as the game targets mainly children and has an educational purpose.

### Wireframes

I have created my wireframes using Balsamiq and I've done separate wireframes for each difficulty level.
There are 3 mockups including both desktop and mobile in each version of difficulty level, easy version of the mockup having also the Win Modal Pop-up shown. 
The links to the files are below:
* [Mockup easy mode](https://github.com/morphy80/Memory-Game/blob/master/assets/wireframes/Mockup%20Easy%20mode%20-%20MS2.CI.png)
* [Mockup medium mode](https://github.com/morphy80/Memory-Game/blob/master/assets/wireframes/Mockup%20Medium%20mode%20-%20MS2.CI.png)
* [Mockup hard mode](https://github.com/morphy80/Memory-Game/blob/master/assets/wireframes/Mockup%20Hard%20mode%20-%20MS2.CI.png)
The wireframes target as much as possible the final result of the project and I consider there are no major differences.

## Features

### Functionality

* Game starts by pressing one of the difficulty selector buttons.
* Pointer changes to hand when hovered over the cards and buttons.
* Cards have different color-images on front and the same pattern on the back.
* Cards flip has an according sound for realism.
* Timer that starts once the difficulty is selected.
* Clicks are counted throughout the game and rendered into the "Moves" dashboard counter.
* Button selector for all 3 difficulty levels: easy, medium and hard, which increase the number of the cards by 1 row for each level.
* Restart button that restarts the current game "Timer" and "Moves".
* Mute audio button that enables and disables all the sounds in the game, including background music.
* "Win Modal" that appears when the game is completed that contains: time spend, number of clicks and a refresh page button.
* Each game starts with a new shuffle cards array and displays only 2 selected at a time, making it impossible to 'cheat' what cards are rendered.
* If the cards are matched they remain flipped and a matching sound plays.

### Existing Features

* Mobile friendly with a large spectrum of responsivness.
* Game starts by pressing the difficulty level selector button.
* There are two extra buttons, one for "Restart" and one to "Mute" the game at any point, which are displayed after the game starts.
* Refresh page button displayed at the end of the game on "Win Modal".
* "How to Play Modal" that can accessed whenever user wants to know how to play the game. 
* When hovered over the buttons or cards cursor changes to a "pointer hand" 
* Cards display different images, back-side and when it's flipped over on the front-side that are visually appealing.
* Timer counter in seconds and minutes. 
* Moves counter as number of clicks.
* Multiple sounds for each functionality: background music, flipping cards, matching cards, all buttons, win sound when the is game over. 

###  Features left to implement

- [ ] **Different themes** to be choosen from.
- [ ] **Axial rotation** of the cards when flipped - keyframes.
- [ ] **Cards display** zoomed in when hovered - keyframes.
- [ ] **Lucky-sound**: matching a pair from the first attempt - special sound.
- [ ] **Super-lucky**: combo for 2 or more matched cards - special sound.
- [ ] **Parental advise modal** to inform all the children's parents about playing this game and if the children are allowed to play it.
- [ ] **Timer** starts on the first click of the card and not when the game mode is selected.
- [ ] **Pause** game button that can pause the entire functionality of the game.
- [ ] **Leaderboard** that will imply that the user enters his chosen data to be stored locally before entering the game and then accessing the database whenever pleases.

## Technologies used
- This project utilizes HTML, CSS and JavaScript as main programming languages.
- [Google Fonts]()
- Visual Studio Code with the Live Server
- [Github]
- [Markdown](https://guides.github.com/features/mastering-markdown/) 
- [Google Fonts](https://fonts.google.com) 
- Google Chrome developer tools for test and debugging 
- [Balsamiq](https://balsamiq.com/wireframes/) to create and edit the wireframes.
- [Imgur](https://imgur.com/) to store all images
- [Favicon.io](https://favicon.io/favicon-converter/)

## Testing
- [HTML validator](https://validator.w3.org/#validate_by_input)
- [CSS validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
- [JsHint](https://jshint.com)

### Manual testing
1. Pressed on every button and check functionality on several stages
2. Turning all cards, clicking on all cards fast and rapidly

### Errors & Debugging
* Restart function 

## Deployment

### How to deploy code locally
If you wish to run this code locally: 

- Download or clone the code from the Github [repository](https://github.com/morphy80/Memory-Game)
- Click on "Clone or download" to Download ZIP or clone by copying the link
- Uncompress the ZIP folder to view or clone into VS Code using Source Control and paste the link in "Clone" window

## Credits

### Code
- Javascript [tutorial](https://www.udemy.com/course/jquery-game-course/) 
- [StackOverflow](https://stackoverflow.com/questions/49425137/how-to-stop-timer-in-javascript) for accurate timer in seconds and minutes.

### Images
- [Imgur](https://i.imgur.com/bTu45F0.png?1) for back-side of the cards

### Audio
* All the sounds were taken from the same audio source[Orange free sounds](http://www.orangefreesounds.com/)
- [Button click](http://www.orangefreesounds.com/switch-sound-effect/)
- [Card flip](http://www.orangefreesounds.com/card-flip-sound-effect/)
- [Matched-correct](http://www.orangefreesounds.com/coin-collect-sound-effect/)
- [Victory](http://www.orangefreesounds.com/quiz-correct-wining-victory-sound-effect/)
- [Background music](http://www.orangefreesounds.com/calm-garden-sounds-for-relaxation/)

### Acknowledgements

Special thanks to:
- Code Institute team, speacial big thanks to my mentor [Aaron Sinnot](https://github.com/aaronsnig501) for the kind and professional suport and understanding
 and to all my fellow students from [Slack](https://app.slack.com/client/T0L30B202/C7W83ABJ7) comunity for helping, guiding and supporting me.
- Laurence Svekis from [Udemy](https://www.udemy.com/course/jquery-game-course/) for the wonderful tutorial.

### Disclaimer
The content of this website, including the images and sounds used, are for educational purposes only.