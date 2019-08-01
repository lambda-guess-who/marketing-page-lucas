# Marketing Page Guess Who

This is the README.md for the Guess Who Lambda School Build Week project.

# Project

## Game

The basis of the game is a high-score based guessing game, where the player guesses who was the author of a given tweet from 2 or 3 choices. The player continues to play so long as they get answers right. When the get one wrong, they lose and their score is the number of correct answers they provided.

## Objective

Build a marketing page for a mobile application

## Challenges

In starting this build week, there were several challenges:

1. Team size was 11 people.
2. There was no formal Team lead
3. There were no initial UI / UX designs

# UI / UX Designs

Given our lack of a UI / UX designer on the team, I took the initiative to design our mobile application from scratch.

[Here is a link to the Figma Designs](https://www.figma.com/file/d34mD8cxoaqJfwWJhRodei/Lambda-1-Guess-Who?node-id=6%3A19604)

## Design Decisions

1. From within the Figma file in the Brain Dump file, I started with a level based game modeled off of the game "Tweet Stars" and other level based games like Candy Crush.

...This proved to be a little too complex to complete within the course of 4 days, so we collectively agreed to narrow the game down to a "Streak / High Score" based Game.

2. Because it's a game, I focused on large buttons, color, consistent UI components, and a very simple UX pattern.

3. I also made accessibility a priority in the game with large contrast, bold fonts, and icons (not just color) throughout to indicate state

## Landing Page Design Decisions

This was very straight forward, as I modeled the landing page off the mobile application design:

1. Mobile first design
2. Horizontal scrolling to increase mobile interaction
3. Large buttons and modeled off UI for application
4. Accessibility with alt tags, rems on sizing
5. Sizing with phone, tablet, and desktop

# Tech Choices

1. Not using a CSS framework

...I decided against using a 3rd party library like Boostrap in order to build the responsiveness and layout of the application. This was primarily because there was going to be too many css overwrites in order to achieve the behavior I was looking for.

2.  Choosing Sass

...I chose Sass in order to challenge myself to learn another css pre-processor and after some initial research, it seemed as though Sass is used more often in the professional environment.

3. Netlify for Deployment

...Even with familiarity with Heroku, Netlify made deployment and automatic builds from my git repo just too freaking easy.

# Challenges during development

-   Getting overflow to work properly
-   Deciding to use display / not display
-   Challenges with Deployment
-   Netlify NOT displaying properly on mobile
-   Starting with mobile first design and not considering the needs of the desktop
-   Media query Sizing
-   Dealing with Sass and Sass compiler

6. Learnings

-   Using Netlify for Deployment
-   overflow issues
-   background gradient
-   Using Trello more extensively

7. Future Goals / Wants

-   Fadein animations on scrolling
-   actually getting the scrolling overflow to work instead of display none / flex
-   I want to build the actual game personally
