# Command the Dungeon

## Elevator Pitch

You wake up in some weird, dimly-lit room, not knowing where you are or how you got there. All you know is that you need to escape this room. Throughout the game, you the player will be navigating various rooms and solving puzzles via a command terminal with bash commands. Be warned though, as one mistake could cost you your life.

## Influences (Brief)

- Kings Quest:
  - Medium: Video Game (Text Base, DOS, Exploratory)
  - Explanation: Uses a large variety of command inputs for the controls and actions, matches stylistically.
- Oregon Trail:
  - Medium: Video Game (Text Base, DOS, Resource Management)
  - Explanation: Uses command inputs for most of the controls, resource management is key.
- Riddle School:
  - Medium: Video Game (Flash, Newgrounds, Puzzle Solving)
  - Explanation: Focus on puzzles and room navigation, clear linear flow on progression, one of the more popular games in the genre our game is in.

## Core Gameplay Mechanics (Brief)

*Give a very high-level description of any core gameplay mechanics*

- Use commands to go in and out of items/file directories (I.E., if you are in a dorm, you would do `cd` refrigerator to go to the refrigerator).
- Use ls to list all items in a given are or room (I.E., I would do `ls` after I `cd` into a fridge to see its contents).
- Use color coding to indicate what items you can pick up or not(I.E., An item that can be picked up would be coded white).
- Use commands to equip and move items(I.E., if you had a key lying around, then you would use `mv` to equip the key in a locked room).
- Different items will be color coded to match their equivalants in bash (I.E., something you can go into will be color coded like a folder, something thats runable will be color coded to match, items that are white can be picked up).
- Use commands to utilize items(I.E., use the `./sh command` to utilize what item you want to use via executing the file).
- In case someone is stuck, there will be a `help` command that lists all of the embedded commands in the game(I.E., if someone is having trouble with the `cd` command, `help` can be used to further explain and elaborate on how to use the `cd` command).
- If there is a possibility, be able to combine the two items(I.E., if there was an item that needed two or more inputs, then the `cat[item1][item2]` command could be useful).
- If a player wants to, they can have the ability to quit via the ctrl + c command.
- For running an overall level, the command `sudo` can be utilized.

# Learning Aspects

## Learning Domains

- Navigating the Terminal
- Bash Command Programming

## Target Audiences

* Intermediate programmers with some prior knowledge
* Puzzle Solvers, particuarly those adept with escape rooms
* Users who frequently interact with the terminal/Bash

## Target Contexts

*Describe what kinds of formal and informal learning contexts this will be used in (e.g., courses, k-12 computer labs during free time).*

## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

- Movement Through Files: By the end of the lesson, players will be able to competently use the cd command to move up and down different file systems.
- Listing Every File: By the end of the lesson, players will be able to competently use the ls command to list all of the files in a given directory.
- Executing Files: By the end of the lesson, players will be able to competently use the sh command to run files inside of the terrminal.

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- Prior to the game, players need to be somewhat familiar with the terminal.
- Prior to the game, players need to be familiar with file navigation.
- Prior to the game, players should have a basic grasp on simple puzzles and logic.

## Assessment Measures

*Clearly identify a set of viable assessment questions AND their grading logic. The questions should be specific examples of the kinds of questions that your game could conceivably improve student performance on. For the grading logic, it could be the correct answer, a rubric for evaluating the answer, or exact logic for deriving answers.*

- Given a file stored in a directory, access that file.
- Given a list stored in a variable and an index, identify the value at that position.
- Given a list stored in a variable and a subscript, identify the values at that position.

# What sets this project apart?

*Give some reasons why this game is not like every other game out there. Whether the learning objective is unique, the gameplay mechanics are new, or what. You should persuade the reader that your game is novel and worthy of development. Consider arguments that would be persuasive to a Venture Capitalist, Teacher, or Researcher. These might be focused on learning needs, too.*

- Most command terminal activities focus strictly on command writing, this can have fun mechanics and fast-paced gameplay.
- The gameplay mechanics are supposted to mimic the feel of navigating a real file system, with a bit of abstraction, allowing the player to have fun doing tasks connected to learning, while also gaining those real world skills connected to the learning objectives.

# Player Interaction Patterns and Modes

## Player Interaction Pattern

This is a game for one person, they use the keyboard to interact with the game world via command inputs.

## Player Modes

*Your game has one or more player modes. Describe each discrete mode, considering things like menus too. Generally describe the transitions between modes too.*

- Single-player: You navigate through a short series of rooms

# Gameplay Objectives

- Advance to the next level:
    - Description: Get the door unlocked and move on to the next level. 
    - Alignment: This aligns with the learning objects because
- *Primary Objective #2*:
    - Description: *Description*
    - Alignment: *Describe how this aligns with one or more learning objectives*

# Procedures/Actions

All actions are done via an in game terminal. This includes:
- moving in and out of places via the cd command
- accessing the list of items via the ls command
- interacting with objects via the sh command

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

# Objects/Entities

*What other things are in the world that you need to design? These may or may not directly translate to actual objects and classes.*

## Core Gameplay Mechanics (Detailed)

- *Core Gameplay Mechanic #1*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #2*: *Describe in 2 paragraphs or less, along with how it generally works*
- *Core Gameplay Mechanic #3*: *Describe in 2 paragraphs or less, along with how it generally works*

    
## Feedback

*Explicitly describe what visual/audio/animation indicators there are that give players feedback on their progress towards their gameplay objectives (and ideally the learning objectives).*

*Describe what longer-term feedback you detect and give that guides the player in their learning and lets them know how they are doing in regards to the learning objectives.*

# Story and Gameplay

## Presentation of Rules

*Briefly describe how the player will learn the gameplay mechanics. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching mechanics iteratively and slowly.*

## Presentation of Content

*Briefly describe how the player will be taught the core material they are meant to learn. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching material iteratively and slowly.*

## Story (Brief)

You are trapped in a room, with no clue why you are there, or how you ended up there. It is your job to escape it in as little time as possible. (NOTE: The player's total game time will not be tracked, and does not affect the gameplay at all.)

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

# Assets Needed

## Aethestics

The aesthetics should be semi cartoony, but down to earth style that converys a tense atmosphere. Limited color pallete to match old DOS games, should only have a maximum of 16. Art should be done in flat colors, possibly vectorized drawings.

## Graphical

- Characters List
  - *Characters 1*
  - *Characters 2*
  - *...*
- Textures:
  - *Texture 1*
  - *Texture 2*
  - *...*
- Environment Art/Textures:
  - *Environment Texture 1*
  - *Environment Texture 2*
  - *...*


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - *Game region/phase/time*: *Example 1*, *Example 2*
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - *Game Interaction*: *Example 1*, *Example 2*
  - *Game Interaction*: *Example 3*, *Example 4*


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
