# Practicing Mindfulness in the Elderly Population

## Assignment 6: UI Design and Prototyping

Tina Ly | DH 110 | Spring 2021

## Project Description

Be You is an app that builds and improves upon the features in the Mindful Living app. Since no well-known platform exists that focuses on the elderly population and improving their well-being, Be You provides meditation and simple to digest articles for senior citizens that tailors to the elderly population in its visual design. It uses color-blindness friendly color scheme, bigger font sizes, simple navigation buttons, and even allows for a language preference and provides a search and filter feature with categories. This prototyping phase helps highlight the aforementioned features that makes the app unique.

## Prototype Tasks

* Changing Language Preference (ie from Spanish to English)
* Watching a meditation video (access the volume settings, adding captions)
* Saving a meditation video
* Filtering Reflection Articles by Author

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/First%20Iteration%20Prototype.png width="1000"> 

## Detailed Prototype Description

With the current prototype, to demonstrate the capability of changing the language preference, the user enters the application in Spanish with the settings icon in the lower left-hand corner. By tapping on the settings icon, the user is led to the Settings page with the language options purposefully in English. The user can then tap on the dropdown icon next to the word “Spanish” and then hover and tap on English. A color change indicates the choice has been selected. After clicking on the desired language, the dropdown of options collapse and the user can now save the changes made in the Settings page. After clicking on the “Save” button, the button not only changes color but also changes to “Saved!” The user can then press the back arrow key in the upper right-hand corner to be led back to the Home Page. At the Home Page, the three options make it clear the main categories and purposes of the app. The user can first explore the Meditate page and again, by tapping on the “Meditate” button, which changes color, and the user is led to the page with a search bar and videos.  The current flow presses on the first recently uploaded video, a feature that specifically allows users to remain up-to-date with content. The user first adjusts the volume and then clicks play with the button displayed big and prominently. The user can then click on the CC in the lower right-hand corner of the video image to allow captions. The CC changes color to indicate that it has been activated. The user cna then save the current video by pressing the bookmark icon and after clicking on it, the bookmark fills and “Saved!” appears right next to it. Now navigating back with the back option in the upper right-hand corner, we can see that the video saved now appears at the top of the Meditate page. To explore the other pages, the user can press on the Home icon in yellow in the lower left-hand corner. The button changes color and we are then led back to the main page. Hovering on and pressing on the Read button on the Home page acts the same way as the Meditate button. The Read button goes to a page of article category options with the button choices also being responsive by changing color. After clicking on the “Reflection” button, the user is led to a page of article titles with snippet quotes from each article. By tapping on the filter icon, a Sort by box with options appears and the user can, for instance, sort the articles by author by clicking on the Author option and confirming the selected choice by tapping on the Confirm button which changes color when pressed upon. The articles are then sorted as desired and there is a note at the top of the Reflection Articles page next to the filter icon that the articles have been sorted by Author

## Design Decisions

### Initial Color Contrast

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/orange%20color%20contrast.png width="500"> 

### More Color Contrasts 

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/green%20orange%20color%20contrast.png width="500"> <img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/orange%20green%20color%20contrast.png width="500"> 

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/green%20white%20color%20contrast.png width="500"> <img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/white%20green%20color%20contrast.png width="500"> 

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/yellow%20green%20color%20contrast.png width="500"> <img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/yellow%20green%20contrast.png width="500"> 

Performing some outside research on which fonts are best for the elderly population, I found that it was best to have at least a 12 point font and not use any fonts that were extra fancy in any way ([Health Literacy 2016](https://health.gov/healthliteracyonline/display/section-3-3/)).  As a result, I settled on the Open Sans font and all words on the app are at least 30 point font size. I originally wanted to use a warm orange color for the background of all the screens but white font on an orange background failed the color contrast test as displayed in the image. Instead, green was used for the background because I found that the color green is associated with being restful and healthy and is easier on the eyes ([Mark@ElderTech 2017](https://eldertech.org/color-in-designing-technology-for-seniors/). The color contrasts tests showed that green in combination with a peach color, pale yellow, and white met all the levels of Web Content Accessibility Guidelines, including the high level WCAG AAA. Considering that my user would be a senior citizen, meeting this condition is essential. 

When playing around with light versus dark modes, I found it better to use the HSL option in Figma to adjust the lightness and get the dark mode not as dark that it appears black as seen by the third set of screens in the left photo below. As for spacing, I made sure all headings were consistent and after the 100 px from the top edge of the screen unless there was a symbol such as the back icon on the screen.

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/dark%20mode.png width="700"> <img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/gridlines.png width="300"> 

The below picture shows the basic outline of the color scheme I chose, the font typess used as well as several inactive and active button states and the minimum size of icons used. 

<img src="https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/color.png" width="1000"> 

## Impression Test

What my classmates had to say about my prototype:

* “\[T\]he app is about providing various ways for people to meditate/relax”
* “\[L\]ove your design! There are some buttons that are not in a loop (no back/cancel options) but it is super clear in general!”
* “The app seems to offer options for self care in the form of meditation, reading and listening”
* “I really like the dark green and white colour scheme- it’s minimal but makes a good contrast, and the large font is easy to read.”
* “This seems to be an app about meditation and relaxation. The app allows usrs to listen to various guided meditations, read articles.”
* “Maybe provide a button to unsave and if the user accidentally pressed it \[bookmark icon for a meditation video\] wrong.”

Overall, I received positive feedback from my classmates who were able to identify the main purposes of the app. I did get a suggestion to provide an unsave button when users save a meditation video so to make it clearer to the user that all they had to do to unsave the video was click on the bookmark again, I decided to then display the saved video differently so that when the user lands on the Meditation video page, instead of a filled bookmark, there is a clearly displayed “Unsave” button. I also ended up adding some more space for the Meditation video page so that it was not too crowded between the button to see all saved videos and the heading “Recently Uploaded.” Lastly, I added a page to show the color change of the Home button when clicked on. The revised design can be viewed below.

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/Second%20Iteration%20Prototype.png width="1000"> 

## Impression Test

What my classmates had to say about my prototype:

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FDQYDyb8Gm5FjaaHCEz0uCD%2FDH-110-Spring-2021%3Fnode-id%3D66%253A663%26scaling%3Dscale-down%26page-id%3D66%253A0" allowfullscreen></iframe>

