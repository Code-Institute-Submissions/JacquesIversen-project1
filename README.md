# Project 1.    Formula 1. 

This project is the first of four in which we are to hand in for the Code Institute Full Stack Diploma. In this project we were asked to: Design an interactive Front-End web application using HTML and CSS based on the principles of user experience design, accessibility and responsivity.

This site will describe the last race of the formula 1 season of 2021. Who due to its controversy, have an obscure amount of partial viewpoints from journalists and fans. This site aims for describe the race without political interference. 

<a href="https://ibb.co/sPxvSWr"><img src="https://i.ibb.co/9vK9XZj/Screen-Shot-2022-11-29-at-10-22-07-PM.png" alt="Screen-Shot-2022-11-29-at-10-22-07-PM" border="0"></a>

# Features

Navigation bar - Takes you to the three pages this site contains. 
- Home / index.html (Takes you to the homepage)
- Max / max.html (Short description of Max Verstappen's accomplishments upon the 2021 season)
- Lewis / lewis.html (Shorthand describtion of Lewis Hamilton on his upcoming 2022 season) 

![navbar](https://i.ibb.co/QdP9vvX/Screen-Shot-2022-11-29-at-4-50-07-PM.png)

The Navigation bar enables the user to easily navigate the site. 

# Top Section

<a href="https://ibb.co/MZDSLHp"><img src="https://i.ibb.co/ckc3d9t/Screen-Shot-2022-11-29-at-5-34-36-PM.png" alt="Screen-Shot-2022-11-29-at-5-34-36-PM" border="0"></a>

This sections is build by a black background with white textboxes containing narrow, but exciting information regarding the upcoming content of the site. 

<a href="https://ibb.co/KjMxQMC"><img src="https://i.ibb.co/ccGhpGz/Screen-Shot-2022-11-29-at-10-33-06-PM.png" alt="Screen-Shot-2022-11-29-at-10-33-06-PM" border="0"></a>

In this img section, a red Ferrari 458-GT3 is used instead of an actual F1 car, due to insecurity concerning copyright. When this matter was solved, this actual picture (From shutterstock) had grown familiar to the developer, hence it wasn't replaced. 

5 red dots, sitting on top of 5 green dots indicates the 10 lights of the F1 paddock. 
The text inside the the dots/lights is the very notorious phrase of David Croft "Crofty" (F1 TV commentator)

# Qualifying section 

<a href="https://ibb.co/8848FDf"><img src="https://i.ibb.co/DKgK3Dv/Screen-Shot-2022-11-29-at-10-39-21-PM.png" alt="Screen-Shot-2022-11-29-at-10-39-21-PM" border="0"></a>

A small black-background box with a silver merc (from pexels.com) pushed to the 2/3 side of the frame. A red border was added to both fight the quite boring theme of black & white, bbut also create clear boundaries for in regards to any ADA concerns. The text sections sums only the Q3 element of the race. 

# Race Section

<a href="https://ibb.co/5YX7PjH"><img src="https://i.ibb.co/FskPFYT/Screen-Shot-2022-11-29-at-10-43-32-PM.png" alt="Screen-Shot-2022-11-29-at-10-43-32-PM" border="0"></a>

Last two sections of the site contains of similar sections, but with different color scheme. Each paragraph concludes approximately 1/3 of the actual race, with the last desribing the aftermath. 

Youtube videos are added, chosen NOT to run automatically. However, due to F1-TV's strict copyright-statements independent sites are not allowed to play videos outside of Youtube. Hyperlink was considered instead, but "meme-makers" were chosen instead to keep the intented design.

# Footer Section

<a href="https://imgbb.com/"><img src="https://i.ibb.co/TTcx6ZM/Screen-Shot-2022-11-29-at-5-37-47-PM.png" alt="Screen-Shot-2022-11-29-at-5-37-47-PM" border="0"></a>

- Footer is designed with Fontawesome icons. 

- Icons are taken from the LoveRunning, also viewable in repository. 
Twitter is then replaced with Formula One's Official site. (Because who do Twitter except Trump)

- Each page has individual accounts linked, except for the F1-page. 

(Ex. Facebook icon on home page will direct you to Formula1's Fb page. Fb icon on Max's page will direct you to Max Verstappens Fb page, same with YT and IG and Lewis's page)

- Footer will change color to red when taken into smaller screens.

# Max Verstappen, and Lewis Hamilton Page

- This site contains a very brief introduction to Max Verstappen impressive career so far. 

<a href="https://ibb.co/ThcsfxJ"><img src="https://i.ibb.co/3h1n39V/Screen-Shot-2022-11-29-at-10-57-24-PM.png" alt="Screen-Shot-2022-11-29-at-10-57-24-PM" border="0"></a>

Both pages are simular in design and shares design from CSS. 


<a href="https://ibb.co/NjBrtY5"><img src="https://i.ibb.co/G2S9nPy/Screen-Shot-2022-11-29-at-10-59-03-PM.png" alt="Screen-Shot-2022-11-29-at-10-59-03-PM" border="0"></a>



# Testing

- Font // Intended was an actual font completely simular to F1's official font, but hard to optain. Therefore Font is chosen to come as close to official font. 

- Nav bar has an active design feature, almost simular to the one you'll find in the official F1 website. This follows through down towards 300px 

- Image with red Ferrari will keep its sharpness throughout wider screens, and "Lights out" design will change size matching current screensize. 
Text within 'lights' will be removed in smaller screens.

- Qualifying section will keep its integrity in larger screens, but the 'silver car' will vanish when smaller screens are used. 

- Race section uses on-site YT-videos, but aren't official F1 production material due to copyright. This design will change from side/side to top/bottom on smaller screens. 

- Testing on smaller screens is only down from 300px 

- All Youtube-videos are checked for viewable content.
- All Icons are checked for correct landing location.

- Youtube-links were comprised due to copyright issues from F1 TV and devoloper not agreeing to sacrifice intended design.

# Validator Testing

## HTML 
- Index.html / 2 errors found, and solved, but if solved removes 'lights out' from their intended placement. Errors due to h1 placement.

<a href="https://ibb.co/y5LZZpY"><img src="https://i.ibb.co/ZKyFFSY/Screen-Shot-2022-11-29-at-11-25-40-PM.png" alt="Screen-Shot-2022-11-29-at-11-25-40-PM" border="0"></a>


- max.html / No errors or faults.
- lewis.html / No errors or faults.

- style.css / No errors or faults.


# Unfixed Bugs
Validator Errors - When solved causes the whole site to crash completely.

# Deployment

Site is deployed to GitHub pages and found within: The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab

- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

(Used from LoveRunning ReadMe)

Livelink : https://jacquesiversen.github.io/project1/

# Credits 

## Design:
- Color scheme from Formula one wesite : https://www.formula1.com/en.html
- Colors found with devtools in Chrome. 
- Active design with devtools in Chrome.
- W3 Schools for help, especially with CSS issues. 

## Content:
- Homepage from Wikipedia : https://en.wikipedia.org/wiki/2021_Abu_Dhabi_Grand_Prix, Content is not edited. Irrelevant infomation spared for simplicity and ease of reading for users/visitors. 
- Icons not only from FontAwesome, but also from the LoveRunning project. 

## Media:
- Youtube videos, not accurate, but satirical, 
- Photos on homepage from Shuttershock and Pexels.
- Photos on page Max and Lewis, taken from Google image search. 
