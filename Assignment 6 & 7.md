# Practicing Mindfulness in the Elderly Population

## Assignment 6 and 7: UI Design and High-Fidelity Prototype

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

## Interactive Prototype

Access the Figma Prototype [here](https://www.figma.com/proto/DQYDyb8Gm5FjaaHCEz0uCD/DH-110-Spring-2021?node-id=66%3A663&scaling=scale-down&page-id=66%3A0).

## Updated Wireflow

### Overall

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/Overall%20Wireflow.png width="1000"> 

### Changing language preference

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/Lang%20Preference%20Task.png width="1000"> 

### Finding meditation video, accessing its settings, and saving the video

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/Meditation%20Video%20Task.png width="1000"> 

### Finding the Reflection article and sorting by author

<img src=https://raw.githubusercontent.com/lyt251/DH110-TinaLy/main/Article%20Filter%20Task.png width="1000"> 

## Cognitive Walkthrough

### First Runthrough

I had my sister complete the tasks listed above using the prototype; the video of her walking through it the first time can be found [here](https://drive.google.com/file/d/1a6p3yF8kkVdH53F9N0ILMvmTJDLc_zhq/view?usp=sharing). We were not able to finish the tasks during this runthrough because we reached a dead end specifically when trying to adjust various Meditation video settings. I then discovered that a certain page was not connected so I altered my design and also added more interactions to ensure the prototype was working at when looking at the meditation video. I also connected the word "Back" as needed to the correpsoing screens because I noticed that after changing the language preference, she first clicked on the word "Back" before the arrow head pointing to the left.


### Second Runthrough

As a result, I had my sister walk through the tasks once again using the prototype after making the necessary changes and the video of that can be accessed [here](https://drive.google.com/file/d/1mciUC-c1I5ctatDJpeaxjekZh6spS9U-/view?usp=sharing). It went pretty smoothly except for a meditation video, she tried sliding the volume to see if she could adjust the volume. 

### In-class Walkthrough

My classmates overall liked the color palette and simplicity. After describing the desired persona I was targeting, it made more sense to my classmates why I made the graphical choices. They suggested adding more labels to the back arrow and the filter for the Reflection articles page.

One of my classmates' testimony:

“This seems to be a kind of mental health/meditation app, and I think the forest green is very fitting for that. At first glance, the interface looks very simple and the text seems too big, but after understanding that the app is meant for the elderly these design choices make a lot of sense.”

## Reflection

Initially, when connecting the screens I connected it simply based on the wire flow. After receiving feedback based on the first and second run throughs, I further edited the prototype accordingly. I found it easier to edit my prototype and connect my screens while I was previewing the prototype on another tab to see it work. For example, while editing the features and icons for the Meditation video, I was planning to overlay the component over the screen but while previewing the prototype after I made that change, the screen reached a dead end after the overlay. As a result, instead of using an overlay, I ended up duplicating and altering  certain aspects of the screen and adding that to the flow. This allowed me easier manipulation when connecting other screens to the flow as well. During the cognitive walkthrough, I had not expected my sister to try physically adjusting the volume like a slide bar. Overall, the second run through went pretty well as she was able to identify the actions and icons needed to complete the tasks. Before the in-class cognitive walkthrough,  I tried creating a mockup of a sliding volume which involved creating several circles over the extended volume bar and then creating other states that show the varied lengths of the current volume. I also played around more with the transitions of the pages. For instance, subpages with a back button would transition in from the left or right and transition out the same way. When performing the in-class cognitive walkthrough, I was surprised to find none were interested in how the volume would perhaps change but rather on the layout of the Meditation Video page and the specific labels used next to the icons. Throughout the whole process from wireframing all screens to making changes to the interactions, I truly learned the importance of iteration. After making an interaction, I would notice how another interaction may be added and put myself in the users’ shoes to consider what they may click on first. 
