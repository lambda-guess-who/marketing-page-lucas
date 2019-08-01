# Marketing Page Guess Who

This is the README.md for the Guess Who Lambda School Build Week project.

## Game

The basis of the game is a high-score based guessing game, where the player guesses who was the author of a given tweet from 2 or 3 choices. The player continues to play so long as they get answers right. When the get one wrong, they lose and their score is the number of correct answers they provided.

#Objective

Build a marketing page for a mobile application

#Challenges

In starting this build week, there were several challenges:

1. Team size was 11 people.
2. There was no formal Team lead
3. There were no initial UI / UX designs

# UI / UX Designs

Given our lack of a UI / UX designer on the team, I took the initiative to design our mobile application from scratch.

[Here is a link to the Figma Designs](https://www.figma.com/file/d34mD8cxoaqJfwWJhRodei/Lambda-1-Guess-Who?node-id=6%3A19604)

##Design Decisions

1. From within the Figma file in the Brain Dump file, I started with a level based game modeled off of the game "Tweet Stars" and other level based games like Candy Crush.

...This proved to be a little too complex to complete within the course of 4 days, so we collectively agreed to narrow the game down to a "Streak / High Score" based Game. This means that the player will continue to play until they lose, winning 1 point for each correct guess.

    -   Converted to streak based game
    -   Modeled off of Tweet Stars and HigherLower from Google searches
    -   Large simple buttons
    -   Accessibility considerations
        -   Colors and Icons

3. Landing Page Designs

-   Design Decisions
    -   Mobile First design
    -   Scrolling "activity" based design
    -   Large buttons and modeled off UI for application
    -   Accessibility with alt tags, rems on sizing
    -   Sizing with phone, tablet, and desktop

4. Tech Choices

-   Not going with a pre-builder
-   Choosing Saas
-   Choosing Netlify

5. Challenges during development

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
