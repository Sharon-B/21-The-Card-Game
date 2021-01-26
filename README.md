# 21 The Card Game


# Project Summary

This website aims to demonstrate my skills of Javascript, HTML & CSS as learned from the Code Institute Full Stack Software Development course. In order to do so I will create my version of the card game Twenty-One. The project will be created using a mobile first design strategy and will ensure the site is fully responsive across all devices. The project will further the developers knowledge of Javascript and it's implementation.

# Contents


# The origin of the card game Twenty-One

Twenty-One, formerly known as Vingt-Un in Britain, France and America, is the name given to a family of popular card games, the progenitor of which is recorded in Spain in the early 17th century. The game is first mentioned by name as early as 1611 in a Spanish dictionary where, under the entry for "card" (carta), it mentions the game of Ventiuno ("twenty-one")

Twenty-One rose to prominence in France in the 18th century and spread from there to Germany and Britain from whence it crossed to America. Known initially as Vingt-Un in all those countries, it developed into Pontoon in Britain after the First World War and Blackjack in Canada and the United States in the late 19th century, where the legalisation of gambling increased its popularity.

Information gathered from Wikipedia. [Read More here](https://en.wikipedia.org/wiki/Twenty-One_(card_game))

# User Experience (UX) 

# Strategy

## Developer Objectives

To grow my skills as a developer and create a  simple easy to use and enjoyable interactive game. Develop the project from its initial concept to the final finished product. To utilise and expand my skills in Javascript, HTML & CSS.

### Target Audience:

* General public.
* People looking for a fun distraction while taking a break from their day.
* Commuters who like to play games to pass the time on their journey


## User Stories

1.	As a user I want to be able to easily understand the rules of the game so I can get started quickly.
2.	As a user I want the game play to be intuitive so I don’t have to spend much time learning how to play.
3.	As a user I want a fun and interesting game so that I can enjoy playing it when I have some free time.
4.	As a user I want to know if I win, lose or draw a game so that I can keep playing and improve.
5.	As a user I want to know how many games I win/lose/draw so that I can track how well I’m doing.
6.	As a user I want to be able to reset a game so that I can start again.
7.	As a user I want to have a visually appealing interface so that I will enjoy playing the game for longer.
8.	As a user I want a game I can play on all my devices so that I can play while on the go.

## Site Owner Stories

1.	As a site owner I want to present my work in a professional, creative and visually appealing way.
2.	As a site owner I want to provide a good user experience for my users, so that they want to come back.
3.	As a site owner I want to present a game users can start playing quickly and intuitively so that they don’t have to make a big time commitment in learning how to play.
4.	As a site owner I want to provide feedback to my users on how they are doing.
5.	As a site owner I want to give users options so they can style the game to their liking.
 
	

# Scope
This will be a Minimal Viable Product containing the most important core content required.

#### Functional Specifications: 

*	Rules 
*	Game statistics
*	Reset
*	Start game
*	Settings

*	Win/Lose/Draw game outcomes
*	Background music and sound effects


#### Content Requirements:

*	Logo.
*	Brief description of how to play.
*	Option to change theme.
*	Reset button.
*	Game stats for tracking win/lose/draw.
*	Dealer heading
*	Display dealer hand.
*	Display card total for dealer.
*	Player heading.
*	Display player hand.
*	Display card total for player.
*	Display game outcomes – win/lose/draw.
*	Game play buttons.

#### Strategy/Scope Trade Off
Providing background music and sound effects for the game was not deemed to be of high importance at this time. There is a thin line between irritating the user and enhancing the user experience using music and so will not be included in the initial release of the website.

# Structure

### Interaction Design: 

User interactions will be intuitive and allow for easy game play. 
The game play centres around 3 clearly labelled buttons at the bottom of the screen for easy access when playing. One button to start the game, one button to request another card i.e. hit and one button when the player is happy with their hand and wants to hold.

### Information Design: 

Will allow for the prioritisation of the information to be displayed in a clear and concise manner to make it as easy as possible for the user to read and to quickly find the information that is most relevant to their needs.

The 4 game options buttons are displayed above the game play area. These allow the user to change the theme, read the rules, check their game stats using modals The fourth button allows users to reset a game.

Modal pop ups used to deliver information about the game outcome and inform the player if they win, lose or draw.

# Skeleton

Wireframes:

[Mobile](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/wireframes/21-card-game-wf-mobile.pdf)
 
[Tablet](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/wireframes/21-card-game-wf-tablet.pdf) 
 
[Desktop](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/wireframes/21-card-game-wf-desktop.pdf)



## Difference between final design and original wireframes:

### Logo:
In the original wireframes the logo/heading was 21 Card Game this was changed to be 21 The Card Game for better readability.

### Player Heading & Score:
The player heading and score has moved to above the player hand as it gives better structure to the game play area and maintains the same hierarchy as the dealer heading/hand layout.

### Win/Lose/Draw Modals:
The win, lose and draw modals have been expanded to now include more options to give the player more feedback as to how they won or lost the game. Rather than the 3 modals outlined in the wireframes we now have a modal for each of the following game outcomes:
*	Player wins by getting 21
*	Dealer gets 21, player loses
*	Player wins
*	Dealer wins, player loses
*	Player went bust, dealer wins
*	Dealer went bust, player wins
*	A draw

### Deal Button:
The deal button in the original wireframes has been renamed to start, this gives the user a clearer understanding of the intent of the button.

### Game Board Area Border:
A border was added to the game board area to define the space where the game play takes place.

### Game Stats:
No of wins by getting 21 was added to the game stats window as a way of tracking how many times a user gets the coveted 21 score from their hand.

# Surface

#### Typography:

Montserrat Subrayada font is used for the main logo as it’s unique underlined style lends well to being used as a heading/logo which provides immediate impact.

Lora is an well-balanced contemporary serif with roots in calligraphy which offers a great contrast to the graphic heading of Montserrat Subrayada and allows for easy reading of the text content of the Website.


#### Colour scheme: 

##### Classic Theme:
![Green colour gradient classic background](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/colour-gradient.png "Green colour gradient classic theme background")

The classic green colour scheme is a nod to the green felt used in casino tables where the game would often be played. The colours #c9de9 & #398235 are used to create a light to dark gradient from top to bottom to soften the scheme and provide visual interest rather than using one solid colour.

![Font colour](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/colour-font.png "Font colour")

The font colour used is #120202 which was checked for contrast against the background colours using the Webaim contrast checker. This same colour is also used for the border around the game board area.

##### Beach Theme:
![Beach Theme](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/beach-small.png "Beach Theme")

The beach theme uses a beach image as the background. The change of colours from the sea to the sand in the image also echoes the gradient effect of the classic theme. The beach image is given a slight blur effect to ensure the game contents, cards, score etc are still the main focus while providing a tranquil background. All other colours are the same as for the classic theme.


##### Night Theme:
![Night Theme](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/night-small.png "Night Theme")

The night theme uses an image of the night sky as its background. This particular image was chosen as it also echoes the gradient effect first created in the classic theme, with the changing colour of the night sky from top to bottom. This may be a more suitable background for those that prefer a dark background or like to play at night.

![Night font coulour](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/font-night-theme.png "Night Theme font colour")

The font colour was changed to #D6D6D6 and was chosen to give sufficient contrast with the backdrop without being too bright. The border colour of the game board area is also set to this colour.

##### Accent Colours & Modal Windows
![Accent Button colour & Modal colours](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/colours-accent-modals.png "Accent Button colour & Modal colours")

The accent colour #E27D60 is used for all the buttons and the headings in the modal pop ups.  This colour was chosen as it works well in contrast to the backgrounds of the three different themes.

Modals were created with a dark background of rgba(06, 09, 06, 0.761) which includes a slight transparency to still feel connected to the game/background behind. 

The font colour used in the modals with text content is #FAFAD2, this is also the colour of the play again button in the game outcome modals.

##### Cards
![Card colour scheme](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/colour-palettes/colour-cards.png "Card colour scheme")

Card background: #FEF3EC
The white of the cards was chosen as the best contrast to the backgrounds used while also not being too contrasting.

Red cards: #CE070E

Black cards: #120202

Card border: #3D0D0D


# Features 

*	Responsive.

*	Game Statistics button for user to check how many games they’ve won/lost.

*	Reset button so the user can reset a game at any stage, this opens an alert pop up to ask the user if they are sure they want to quit the current game and start again.

*	Rules button to display the rules of the game.

*	Settings button for the user to be able to choose between 3 different backgrounds for the game – Classic, Beach, Night.

*	Game board area where the game play happens.

*	Dealer heading for the dealer area.

*	Dealer card value total display.

*	Dealer area where the dealers cards are displayed.

*	Player heading for the player area.

*	Player card total to display the total of the players cards.

*	Player area where the players cards are displayed.

*	Start button to start the game.

*	Hit button for the user to draw another card.

*	Hold button for the user when they are satisfied with their current hand.

*	Game outcome modals. Modal windows are opened for each of the different game outcomes to tell the user how they did in the game.

*	Collapse cards down when 4 cards or more in a hand.

*	Game play buttons at the bottom of the screen have been given a shadow effect to make them stand out as they are the buttons most used while playing the game.

*	Highlight buttons on hover.


## Future Features

* Difficulty level added where the second dealer card is not revealed until after the player decides to hold.
* Implement a betting system.
* Add background music and sound effects.


# Technologies Used
[Html](https://www.w3schools.com/html/html_intro.asp) - Hyper Text Markup Language, used for creating the website.

[Css](https://www.w3schools.com/css/) - Cascading Style Sheet, used for styling the website.

[Javascript](https://www.javascript.com) – Used for providing functionality to the game play and it’s interactive features

[Bootstrap](https://getbootstrap.com) - Bootstrap grid system.

[Google Fonts](https://fonts.google.com) - The 2 fonts used throughout the website are from Google fonts.

[Balsamiq](https://balsamiq.com) – Used for creating the wireframes.

[Git](https://git-scm.com/) - Used for version control.

[GitHub](https://github.com) - Used to store the project repository.

[Gitpod IDE](https://www.gitpod.io/) - Development environment where the site was built.

[GitHub Pages](https://pages.github.com/) - Where the live site is deployed/hosted.

[Gimp 2.1](https://www.gimp.org/) - Used for editing, scaling images and creating a favicon.

[Tiny png](https://tinypng.com) - Used for compressing images.

[Webaim contrast checker](https://webaim.org/resources/contrastchecker/) - Used to check the contrast between the text font and background colours.

[Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools) - Used throughout the development of the website to quickly see changes, find problems and debug. Also used to view website in different device views.

[Lighthouse](https://developers.google.com/web/tools/lighthouse) in Chrome Dev Tools.

[AutoPrefixer](https://autoprefixer.github.io/) - Used to add vendor prefixes onto the CSS code to ensure compatibility with various browsers.

[W3C HTML validator](https://validator.w3.org/) - Used to validate code.

[W3C CSS validator](https://jigsaw.w3.org/css-validator/) - Used to validate code.

[JSHint](https://jshint.com/) – Used to validate Javascript code

[Coolors](https://coolors.co/) - Used for selecting complimentary colour palettes.

[Unsplash](https://unsplash.com/) – Used for finding background images.


# Testing

## Code Validators & Auto Prefixer:



## Lighthouse from Chrome Dev Tools Testing:


## Buttons Testing:
Each button was tested and passed under the criteria set out below.

### Game Options Buttons:

![Game options buttons](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/game-options-buttons.png "Game Options Buttons")

#### Settings button 
* Highlights on hover.
* Opens settings modal window when clicked.
* Shows theme selection menu when opened.

![Settings](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/settings.png "Settings")

* Theme selection – backdrop changes when click each radio button. 
    Checked all changes:  
    - from classic to night
    - from classic to beach 
    - from beach to classic 
    - from beach to night 
    - from night to classic
    - from night to beach
* X to close modal closes the modal window when clicked.
* Clicking outside the modal window closes the modal window.

#### Rules button
* Highlights on hover.
* Opens rules modal window when clicked.
* Window opens with vertical scroll bar if the content is taller than the screen size available.
* Shows how to play when opened.

![Rules](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/rules.png "Rules")

* X to close modal closes the modal window when clicked.
* Clicking outside the modal window closes the modal window.

#### Stats button
* Highlights on hover.
* Opens stats modal window when clicked.
* Shows game stats when opened.

![Game Stats](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/game-stats.png "Game Stats")

* X to close modal closes the modal window when clicked.
* Clicking outside the modal window closes the modal window.

#### Reset button
* Highlights on hover.
* Opens reset alert pop up when clicked.

#### Reset Alert
* Opens when reset button clicked.

![Reset Alert](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/reset-alert.png "Reset Alert")

* No button :
    - Highlights on hover.
    - Closes the alert window and returns to the game.
* Yes button:
    - Highlights on hover.
    - Clears the game board and resets the game.
    - Closes the alert window.

### Game Play Buttons:

* Hit & Hold buttons are disabled on page load

![Game Play Buttons](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/game-play-buttons.png "Game Play Buttons")

#### Start button
* Highlights on hover.
* Deals 2 cards to each player.
* Enables hit and hold buttons.
* Disables itself when clicked.
* Adds card hand total for each player.
* Checks if either hand is over 21 and if so ends the game and declares a winner.
* Checks if either hand is 21 and ends game.

![Start button](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/start.png "Start button")

#### Hit button
* Disabled on page load.
* Highlights on hover.
* Adds another card to the player hand.
* Updates card hand total for the player hand.
* If card hand is 21 ends game declaring the player as the winner.
* If card hand over 21 ends game declaring the dealer as the winner.

![Hit button](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/hit-button.png "Hit button")

#### Hold button
* Highlights on hover.
* Disables hit button so player cannot draw another card once they have decided to hold.
* If dealer score is 16 or less it adds another card to the dealer hand.
* Checks Score and updates card hand total for the dealer hand.
* If card hand over 21 ends game declaring the player as the winner.
* If card hand is 21 ends game declaring the dealer as the winner.
* If dealer score still 16 or less it will continue to add another card until the dealer hand is over 16 and will declare a winner:
    - If dealer card total is over 21, the game ends and the player is declared the winner.
    - If dealer card total is 21, the game ends and the dealer is declared the winner.
    - If dealer card total is over 16 and less than 21 and greater than the player card total the game ends and the dealer is declared the winner.
    - If dealer card total is over 16 and less than 21 and less than the player card total the game ends and the player is declared the winner.

![Hold button](https://github.com/Sharon-B/21-The-Card-Game/blob/master/documentation/buttons-testing/hold-button.png "Hold button")

### Play Again Button (found in the game outcome modal window)
* Resets the game.
* Closes the game outcome window.
* Clicking outside the modal window closes the modal window and resets the game.


## Device testing:



## Browser Testing:



## Friends & Family User Testing:



## Testing User Stories





## Testing Business Owner Stories




## Implementation 


## Issues/Solutions
		


## Known Bugs

Bugs found and not fixed:



# Deployment

This website was created in the Gitpod development environment. After installing the Gitpod extension for Chrome web browser and creating a new repository in GitHub using the Code Institute template, the green Gitpod button was used to initialise the repository in Gitpod. Throughout the process the git commands `git add` and `git commit` were used to store the work in the local Gitpod environment, `git push` would then be used to push the commits to the GitHub repository. From here the website could then deployed to Git Pages:

## Git Hub Pages:

From the Git Hub repository:
 - Go to settings
 - Scroll down to Git Hub Pages section
 - Select branch to be deployed, in this case the master branch
 - Click Save

## Creating A Local Clone:
You can clone the repository to create a local copy on your computer.

From the Git Hub repository:
- Click `Code` at the top of the file list
- Click the clipboard icon to copy the url provided

Open terminal:
- Change the current working directory to where you want the cloned directory to be
- Type `git clone` and paste the copied url after it
- Press enter and the clone will be created


# Credits

## Code




## Resources

[Code Institute](https://codeinstitute.net/) course material and mini projects form the main resource for this project.

[Bootstrap Documentation](https://getbootstrap.com/docs/4.1/getting-started/introduction/) - General resource.

[W3Schools](https://www.w3schools.com/) - General resource.

[MDN web docs](https://developer.mozilla.org/en-US/) - General resource.

[CSS Tricks](https://css-tricks.com/) - General resource.

Anna Greaves How to Approach Writing Your README File webinar.


## Content

All text content of the website is written by myself.

The origin of the card game Twenty-One section of README.md is extracted from [Wikipedia](https://en.wikipedia.org/wiki/Twenty-One_(card_game))

## Media
Beach Image credit: Photo by [Fezbot2000](https://unsplash.com/@fezbot2000?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

Night Sky Image credit: Photo by [Wil Stewart](https://unsplash.com/@wilstewart3?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)



## Acknowledgements

My mentor @spence_mentor for great support and positivity throughout.

All at Code Institute and Tutor support.

The Slack Community for their ever present knowledge.


##  Disclaimer

This project is for educational purposes only.
