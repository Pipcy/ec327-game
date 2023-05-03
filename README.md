# EC327 Final Project - Group 7 - Project APEEP
---
## Summary
### Category
Animated Game

### TL;DR
Our game simulates different aspects of memorable moments from EC327, with an added twist of course!

### Description
Dive into the world of EC327 and get a taste of what it's like. Customize your character and explore the classroom. You'll be given a chance to demonstrate your machine code skills and test your knowledge of your fellow classmates and peers. Be careful when answering machine code questions as getting a question wrong might incur the wrath of Professor Trachtenberg. Compete with other players for a place in the leaderboard. See the EC327 Simulator for Dummies pdf for user instruction and the google doc linked bellow for installation instructions. 

## Authors
### Group members
Member name - Wiki Name - bu email:  
Ankita Tiwari   - AnkitaTiwari      - ankita04@bu.edu  
Pippi Pi        - PiyuPi            - ppp@bu.edu   
Elena Berrios   - ElenaBerrios      - eberrios@bu.edu  
Ethan Liang     - EthanLiang        - ethanl66@bu.edu  
Pranav Shrihari - PranavShrihari    - pranavsh@bu.edu  

### Roles
Lead: Pippi (50%), Ankita(50%)  
Front End: Pippi (55.1%), Ethan (17.69%), Pranav (17.69%), Ankita (7.69%), Elena (1.83%)  
Back End: Elena (25%), Pranav (10%), Ankita (22%), Pippi (28%), Ethan(15%)  
Documenter:	Ankita (80%), Elena (20%)  
Tester: Ethan (57%), Pranav(43%)  

---
## Accomplishments

### Minimum requirements

Completion:  
100% - Moving graphical pieces.  
100% - The ability of the user to control some of the moving pieces through input.  
100% - Include a score that is changed based on the user satisfying requirements.  
100% - A menu item that allows the user to pause the game that the user can access at any point in the game  
100% - mini-game within the game  



### Possible features


Completion:  
50% - Implement a health system that is calculated/decreased based on time and player performance [5%]  
    The health system does not decrease based on time but it decreases based on player performance
    
100% - Provide a hints system that the user can access to get a text prompt on how to proceed. [5%]  
100% - Allow the user to customize some aspects of their character’s appearance. [5%]  
100% - Provide a high-score list that persists when the app is closed and then reopened. [10%]  
100% - Incorporate audio components and sound effects in the game [10%]  
100% - Gameplay mechanics that involve randomized events and calculations. [10%]  
N/A% - Allow the user to choose between light mode and dark mode and customize the placement of controls. [15%]  
    Decided we would not include this option in order to maintain consistency with the art.  
100% - Comprehensive graphical design and fine-grain animation for game components. [15%]  
100% - Incorporate online leaderboard where user can see their placement against other users. [20%]  
                                                                    Total: 77.5%  

---
## Execution

### Project source and Installation
Follow [this Google Doc](https://docs.google.com/document/d/1GzOz6lCIO9-j1esVCNZ64J18vl1_PMV1DgRqveJSo84/edit?usp=sharing) for a detailed cloning/downloading instructions!

1. After cloning the project, please select ****Pixel 2 + upsideDownCake + landscape**** as your emulator setting! (detailed instructions above)  
2. The game has great audio, so ****turning audio on**** is recommended, 
Wifi connection is required for the online leaderboard to work properly. All other parts do not. If you go to the leaderboard and nothing shows up, try going back and clicking sync data.  
3. When you play the game for the first time, you receive a ****unique ID**** number that is binded to that device. You can change your username but the score would be updated to the same ID.  
4. If you get sent back to the beginning of a game after finishing it - ****it is a glitch that we are experiencing****. Simply continue to the game and exit by hitting the pause button and “return to main menu.”  

### Usage
[Clear, terse instructions on how to use your app.  What do the different interface elements (buttons, menus, etc.) do?  How does one see the various requirements and features in action.]
View EC327 Simulator for Dummies pdf for more detailed user instructions. 




---
## Miscellaneous

### Extra features
Our project went above and beyond and created pixel art for every visual asset used in the game. This helped enhance the theme of our game and make it more visually appealing. 

### Challenges
Our group struggled to deal with intents and shared preferences as it was our first time handling them. We in particular had bugs where it would send the user to random activities when you returned to the main menu. Additionally it was challenging figuring out how to link chalkActity and chalkGameActivity to each other without restarting chalkActity everytime you went back to it. Shared preferences were difficult to figure out and work our way around since you had to figure out how to access the data from different activities and if you made one major mistake at any point it often persisted even when you tried fixing it including recloning the project. 
In addition to this, the firebase was extremely difficult to figure out and implement and finding a way to implement a unique ID instead of using the username since two usernames could have updated the same scores. Figuring out the hashmaps and retrieving data from the leaderboard was difficult as well and we found out how easily manipulated and abused the activity could be. In addition to this, the database required constant maintainence to avoid it being broken. 

By the end of the project, we had better grasps of intents, shared preferences and databases but the struggle was real. 

### Supporting material
Follow [this Google Doc](https://docs.google.com/document/d/1GzOz6lCIO9-j1esVCNZ64J18vl1_PMV1DgRqveJSo84/edit?usp=sharing) for a detailed cloning/downloading instructions!

### Release
We are comfortable making this public. 

