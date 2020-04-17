# The Prince Of Piano

## Elevator Pitch
*You are a concert pianist in competition, who must learn to play the piano to win each round. Starting with 2 note songs, up to entire pieces, you will learn to associate piano notes with their keys, and eventually learn to play sheet music.* 

## Influences (Brief)

- *Influence #1*:
  - Medium: Guitar Hero 3
  - Explanation: Guitar hero 3 lets the player feel as if they are playing the guitar through simple game mechanics, which will follow a similar play style
- *Influence #2*:
  - Medium: Rousseau
  - Explanation: Rousseau is a youtube pianist who uses top down visuals to accompany his pieces. The artistic value and music both represent an ideal quality for my game
- *Influence #3*:
  - Medium: voez
  - Explanation: voez is a fast paced rhythm game. In my game, the player will learn to play at a faster rate as they go, and match a similar style of pace for score.

## Core Gameplay Mechanics (Brief)

- (first game mode)The player must click the correct key on a visual section of a piano, as notes are flashed on the screen. They are scored on time and accuracy
- (second game mode)The player must play a section of a virtual piano using their keyboard, as notes move horizontally across the screen, as if they were playing sheet muisc
- The player can enter competitions and preform the second game mode, where the more notes and the more difficulty, the better they do
- As the player improves, they receive money to unlock new notes, which improve their score in "competition"


# Learning Aspects

## Learning Domains

Introduction to playing piano sheet music

## Target Audiences

Piano Beginners and people who have learned the piano but do not know how to read sheet music

## Target Contexts

- Someone attempting to teach themselves the piano on their own
- A piano teacher providing practice for their students

## Learning Objectives

- *Find Keys*: By the end of the lesson, the player will be able to find common keys from piano sheet music
- *Play Piano*: By the end of the lesson, the player will be able to preform a simple musical piece on the piano
- *Identify flats and sharps*: By the end of the lesson, the player will be able to read flats and sharps from sheet music

## Prerequisite Knowledge

- Prior to the game, players should be generally familiar with the mechanics of a piano

## Assessment Measures

- Given a line of sheet music, be able to play it at the correct tempo
- Shown notes in a sequence, be able to choose the correct note letter for each

# What sets this project apart?

- *Reason #1 There are very few games out there that teach how to play the piano*
- *Reason #2 This game will have a campaign that emmerses the player and provides a more rewarding experience*
- *Reason #3 Other piano games do not provide multiple game modes for learning*
- *Reason #4 The scoring and money system encourages the player to continue learning*

# Player Interaction Patterns and Modes

## Player Interaction Pattern

This is a game for one person, who plays levels with their keyboard to advance in the game

## Player Modes

- *Player mode #1*: The player is show a note and must click the associated key in levels
- *Player mode #2*: The player is given a piece and must play it using their keyboard
- *Player mode #3*: The palyer enters a competition where they must compete in rounds against bots

# Gameplay Objectives

- *Get the high score*:
    - Description: Each level is scored by preformance, and the player must compete with their high score to improve
    - Alignment: This encourages the player to associate the notes with their keys better
- *Earning in game money*:
    - Description: Players receive money for their score on levels. This money can be used to unlock harder levels
    - Alignment: The money forces the player to learn at an appropriate rate, and helps motivate them to learn more
- *Win competitions*
    - Description: Winning competitions advances the storyline and gives the player a chance to test their skills
    - Alignment: The storyline and competitive mechanic give the player more practice while giving feedback as to how well they are doing

# Procedures/Actions

You can either type notes as they move across the screen or click them as they are flashed on the screen

# Rules

- When a level is started, the new note in the level flashes on the keyboard and must be clicked by the player
- If the player clicks the wrong note their score decreases and a buzzer is played
- If the player clicks the correct note then their score increases and the note is played
- If the player types the correct key then the note is played and the notes continue across the screen (score increase)
- If the player types the incorrect key then a buzzer is played and the notes stop until the player gets it correct (score decrease)
- Based off the player's score, the user accumulates money they can use to advance the game and play more difficult levels
- Once they unlock enough levels, they can join different level competitions
- After winning a competition a story clip is played

# Objects/Entities

- There is a piano visual
- There is a piano note visual for each note on left and right hand
- There are piano sounds for each key at different note lengths
- There is a flashing animation for each piano key
- There is a menu with options "memorize levels", "play levels", "competition", and "settings"
- There is a level selection menu for each selection on the main scene
- There is a return button on each scene to return to main scene

## Core Gameplay Mechanics (Detailed)

- (first game mode)The player must click the correct key on a visual section of a piano, as notes are flashed on the screen. They are scored on time and accuracy. The player is timed, and once the timer runs out the level is over and their score is final. The player receives a higher score addition for longer streaks of correct answers. The player score, and number of correct answers will be displayed at the end
- (second game mode)The player must play a section of a virtual piano using their keyboard, as notes move horizontally across the screen, as if they were playing sheet music. Each level is a song, and the level is over once the player finishes playing the song. The player gets a combo score for getting multiple correct in a row and also gets a score for timing the notes well. The high score is saved so the player can revist any song and attempt to beat their score.
- The player can enter competitions and preform the second game mode, where the more notes and the more difficulty, the better they do. Once the player wins a competition that they have never won before, it progresses the story, and a "cut scene" is played of the story. The player must play pieces they have learned, and defeat their opponent by draining their healthbar before they drain theirs. The opponents notes and preformance is shown, but no sound is played for them.
- As the player improves, they receive money to unlock new notes, which improve their score in "competition"

    
## Feedback

- *If a player gets something wrong, a buzzer is played*
- *If the player plays the correct note then the associated piano sound is played*
- *In memorization mode, a streak sound is played for long combos to show they are doing well*
- *Notes flash green when correct before disapearing*
- *The score is printed on the screen*
- *The player sees their high scores and total money*
- *The background becomes more colorful as the player improves*

## Longterm Feedback

- *The competitions are the primary long-term learning objective. You can compare your preformance to the bots, and see if you've learned the material well enough.*
- *The accumulation of money is a long-term feedback as to how the player is doing*

# Story and Gameplay

## Presentation of Rules

- *The new key for a level will flash before the level begins, and the player musct input the note to begin the level*
- *The keyboard input for a piano key will be on each key as well as the note letter*
- *On the first level there will be flashing text saying "Click the flashing key to play the note shown..."*

## Presentation of Content

*Most of the core material will be taught through the memorization levels of the game, where the player must click notes as they flash on the screen, sometimes in short sequences.*

## Story (Brief)

*You are sipping coffee at a cafe when piano thugs challenge you, you play the tutorial level to beat the thugs, you are then put on the main menu to select from options, you play the memorization game and learn new notes on the piano, you then play pieces using those notes, you then use those skills to win competitions and progress the story*

## Storyboarding

# Assets Needed

## Aethestics

*The game should feel like you're in a casual lodge setting, with different places depending on what game mode you are in. Relaxing and natural*

## Graphical

- Characters List
   (characters are presented in a anime visual novel fashion)
  - *Characters 1: You, the main character. You wear a semi-casual outfit, and look swav.*
  - *Characters 2: The piano thugs. The piano thugs are the first bad guys and wear comical leather jackets*
  - *Characters 3: Several arbitrary looking pianists that you face in competition*
  - *Characters 4: Your best friend who frequently needs your help getting out of trouble, he is blonde and slightly less formal*
- Textures:
  - *Texture 1*: Background texture that changes as the combo improves to be more colorful, starting out pitch black
- Environment Art/Textures:
  - *Environment Texture 1: The cafe scene of a piano in a cafe*
  - *Environment Texture 2: The concert piano for official competitions*
  - *Environment Texture 3: An outdoor piano for street competitions*


## Audio

- Music List (Ambient sound)
  - *Menu*: *calm piano and guitar*
  - *In competition music*: *Music played before competing*
  
- Sound List (SFX)
  - *Playing a note correctly*: *The piano note played*
  - *Incorrect note*: *A buzzer sound signify the wrong key was played*


# Metadata

* Template created by Liam Dwinnell <liamd@udel.edu>
* Version 0.0.3
