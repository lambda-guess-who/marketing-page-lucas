# Marketing Page Guess Who

This is the README.md for the Guess Who Lambda School Build Week project.

# Project

The basis of the project was to create a mobile first twitter game. The game is a high-score based guessing game, where the player guesses who was the author of a given tweet from 2 or 3 choices. The player continues to play so long as they get answers right. When the get one wrong, they lose and their score is the number of correct answers they provided.

## My Objective

Build a marketing page for a mobile application

## Challenges

In starting this build week, there were several challenges:

1. Team size was 11 people.
2. There was no formal Team lead
3. There were no initial UI / UX designs

# UI / UX Designs

Given our lack of a UI / UX designer on the team, I took the initiative to design our mobile application from scratch.

[Here is a link to the Figma Designs](https://www.figma.com/file/d34mD8cxoaqJfwWJhRodei/Lambda-1-Guess-Who?node-id=6%3A19604)

Example:

<img alt="Guess Who UI Design" src="https://raw.githubusercontent.com/lambda-guess-who/marketing-page-lucas/master/imgs/Game-Correct-Answer.png" width="300" />

## Design Decisions

1. From within the Figma file in the Brain Dump file, I started with a level based game modeled off of the game "Tweet Stars" and other level based games like Candy Crush.

    This proved to be a little too complex to complete within the course of 4 days, so we collectively agreed to narrow the game down to a "Streak / High Score" based Game.

2. Because it's a game, I focused on large buttons, color, consistent UI components, and a very simple UX pattern.

3. I also made accessibility a priority in the game with large contrast, bold fonts, and icons (not just color) throughout to indicate state

## Landing Page Design Decisions

This was very straight forward, as I modeled the landing page off the mobile application design:

[Landing-Page-Design-Image](https://raw.githubusercontent.com/lambda-guess-who/marketing-page-lucas/master/imgs/landing-page.png 'Landing Page Design')

1. Mobile first design
2. Horizontal scrolling to increase mobile interaction
3. Large buttons and modeled off UI for application
4. Accessibility with alt tags, rems on sizing
5. Sizing with phone, tablet, and desktop

# Tech Choices

1. Not using a CSS framework

    I decided against using a 3rd party library like Boostrap in order to build the responsiveness and layout of the application. This was primarily because there was going to be too many css overwrites in order to achieve the behavior I was looking for.

2. Choosing Sass

    I chose Sass in order to challenge myself to learn another css pre-processor and after some initial research, it seemed as though Sass is used more often in the professional environment.

3. Netlify for Deployment

    Even with familiarity with Heroku, Netlify made deployment and automatic builds from my git repo just too freaking easy.

# Challenges during development

During this project, I ran into several challenges that I did not anticipate and overestimate their ease of implementation.

1. Getting overflow to work properly

    This is just difficult overall, and I ultimately didn't achieve the entirety of the desired effect (with additional padding on the far right scroll of the overflow).

2. Deciding to use display / not display

    After wrestling the overflow for a number of hours, I opted to simply use the ability to display and not display items based on screen size.

3. Challenges with Deployment

    Deployment was very easy, but I ran into issues with my original background image, some text styling, and the layout of components when the website was launched to Netlify. I did not anticipate those issues and ran into them much later than I would have liked.

4. Netlify NOT displaying properly on mobile devices

    For some reason the website just acts funny on my mobile device. I doesn't act funny at any screen size on desktop, but on an actual mobile device, it will just remove DOM elements entirely. No known solution and no known cause of the issue.

5. Starting with mobile first design and not considering the needs of the desktop

    From my landing page designs, I started with a mobile first approach, but soon realized that my mobile designs were not going to correctly size to a desktop landing page. I also failed to design the desktop layout before coding. Bad Idea.

6. Media query Sizing

    I sized my components before I did my media queries, which isn't an issue in it's entirety; however, it made it difficult to determine tablet and phone sizes and I had to create 2 additional media queries for <400px and > 1100px specifically for large desktops and small mobile devices.

7. Dealing with Sass and Sass compiler

    The Sass compiler was being a turd most of the time, until I realized that the compiler stops working if causes an error, even after you fix it. I spent too much time needed to kill the compiler and starting it back up again.

# Learnings

During this project I learned the following items that I did not know before hand:

1. Using Netlify for Deployment
2. Using and troubleshooting Overflow issues
3. Getting cards to flip using CSS
4. Using Trello more extensively
5. Understanding the importance of designing first and designing simple, and then working toward more complexity.

# Future Goals / Wants

Moving forward I would want to implement the following:

1. Fadein animations on scrolling
2. Actually getting the scrolling overflow to work instead of display none / flex
3. I want to build the actual game personally
