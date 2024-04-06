[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [your name]
### Student number: [your student number] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay (~400 words)

### 2.1. Acid and Checkpoints
The acid and checkpoint were introduced at the start as it helps the player understand at the beginning that when they die they start at their last checkpoint and acid aids in that. 

 ![Storyboard of the Acid and Checkpoints interaction!](DocImages/AcidandCheckpoint.png)

### 2.2. Chompers
The chomper was introduced to the player at this stage as the player has no choice other than passing through the chomper, which also helps them learn that a melee enemy decreases the player's health by one heart.

![Storyboard of the Chomper interaction!](DocImages/Chomper.png)
### 2.3. Health Pickups and Passthrough Platform
The passthrough platform and the health pickup are introduced in this section as the player would have already lost some health from the acid and the chomper so after accessing the health pickup they will regain some health. The passthrough platform hints the player on accessing such pickups when they are below the floor. 

![Storyboard of the Passhtrough Floor and the health pickup interaction!](DocImages/PassthroughfloorAndHealthpickup.png)
### 2.5. Keys and Moving Platforms
The moving platform was introduced in this part as it made the player learn that they must time their movement to escape this section. The key was there as small goal that the player has to achieve by overcoming the challange of the moving platform.

![Storyboard of the Moving platform and Keys!](DocImages/MovingplatformAndKeys1.png)
![Storyboard of the Moving platform and Keys!](DocImages/MovingplatformAndKeys2.png)

### 2.6. Spikes, Weapon pickup (Staff) and Spitters
The player now has to jump to the next platform but there are spikes in the way, if they time their jump correctly they can avoid the spikes otherwise they land on them and loose health. If they time their jump correctly they land on the Weapon pickup (Staff) but as they pickup the weapon they get damaged by the spitter but since they have the staff they can attack the spitter and kill them. The above series of events are connected and help the player in this section learn about weapons, spikes and spitters.

![Storyboard of the Spikes, Weapon and spitter interaction!](DocImages/SpikesWeaponAndSpitter.png)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1
![Storyboard of Section 1!](DocImages/Section1.png)

### 3.3.	Level Map – Section 2
![Storyboard of Section 2!](DocImages/Section2.png)

### 3.4.	Level Map – Section 3
![Storyboard of Section 3!](DocImages/Section3.png)

## 4. Iterative Design (~400 words)
Iterative design can be a powerful tool in improving the level design. In this case, the iterative design helped me set goals for each iteration and achieve them by the end of each iteration. For example, while storyboarding I placed the health pickup where I thought it would be the most beneficial for the level, however by playtesting the level multiple times in multiple iterations it was revealed to me that the initial placements for the health pickup need to be changed in such way that they appear after an encounter where the player has taken or received some damage. The iterative design also helped me in deciding where to place the checkpoints, In each iteration with playtesting I found out that the best place for the checkpoints is before the next encounter or where the player has completed some obstacle. Each iteration also helped me evaluate the difficulty of that section and allowed me to adjust the difficulty curve to match the aimed player experience. 

In my iterative process for making each section, I started by looking at different gameplays online for platformers to take inspiration from, later, I made a storyboard for what I wanted to achieve with that particular section. Then I made a prototype section in Unity to test out the storyboard and based on the playtesting I evaluated the issues i.e. the gap to jump is too narrow that the player can walk over it.  With the evaluation I set the goals for the next iteration similarly with each iteration, I got a better knowledge and understanding of the section I wanted to design. With a refined storyboard after evaluating the previous iterations I designed a level map and started Implementing it in unity. After that, I playtested the level multiple times to find any bugs and tried to resolve them.

Below are some of the earlier storyboards:

![Early Storyboard of Section 1!](DocImages/EarlySection1.png)
![Early Storyboard of Section 2!](DocImages/EarlySection2.png)
![Early Storyboard of Section 3!](DocImages/EarlySection3.png)

Changes:

Section 1: I changed the height of the platform where the key is located as I found a bug where the player was able to jump to the key.

Section 2:  I changed the distances from the top moving platform to the platform with the checkpoint as I found that if the platform moved too close to the other platform it decreased the game's difficulty.

Section 3: I changed the location of the key door as the depth of the level was not able to fit the key door and falling on the platform after collecting the key without getting hit by the spikes was nearly impossible which would have increased the difficulty more than aimed for. 

In the future iteration the placement of the enemies, health pickups, weapon pickups and checkpoints can be vastly improved. For example, the weapons in my level design are not that useful as all of my sections are more focused on obstacle avoidance.


## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


