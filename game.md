
# Ninja village

In this file we are going to describe game.

## General description of the game

The genre of the game will be *turn based startegy*. You will play the role of a head of a ninja village and you will make chioces in order to manage it.

### Idea of *turns*

Every turn in the game will be half a day. The 24 hours of the day will be split to a day light turn and a night turn.

### Concept of *ninjas*

The village consists of several ninjas. The player (the village head is not considered a ninja). Every ninja has stats that describes his ablilities.

### Concept of *missions*

All the operations in the village are made by completing missions. The player can assign ninjas for missions, and recieve reward. Missions have the following properties:

1. **Time to completion**. A normalized value that togather with the assiged ninjas abilities produce a number of turns needed to complete the missions by the assigned ninjas.
2. **Rank**. A symbol that represent the difficulty of the mission.
3. **Requirements**. Set of needed requirements that are needed in order to start the mission.
4. **Output**. The result of the mission (resources, experience ...).

### Concept of *resources*

There are 5 resources in the game:

1. Food
2. Wood
3. Stone
4. Gold
5. Scrolls

## Game graphics

Actually are is no graphics in the game. The game is completely text/ui based.

## First 10 minutes of the game

### Starting screen

1. The player will see an explanation for his role as the head of the village.
2. The player will be ask to pick *Three legandary ninjas*.
    * They are the first ninjas in the village.
    * They are picked randomly and the player can reject them and ask for other three ninjas.
3. The player will see an explanation about missions.

### Basic screens

The main screen consists of:

1. **Status bar**. Has top level data of the village (resources, villigers, ninjas, date).
2. There are buttons to the sub screens:
    1. **Ninjas**. List of all the ninjas in the village.
    2. **Missions**. In this screen the player will be able to assign ninjas to missions and see the progress of current missions.

### Selecting missions

After completing the staring screen and selecting three legandary ninjas the player will be moved to the main screen. There he can pick a mission and start playing the game. He will pick some missions and click on a *next turn button* and the progress of the missions will be updated.

## Development and technology

We will probably implement this game in Unity although this is not a final decision. Suggestions are welcome.

We need to consider developing in Godot. There are a nice tutorial for GUI in Godot : https://docs.godotengine.org/en/3.0/getting_started/step_by_step/ui_game_user_interface.html

We need to write some conclutions based on this tutorial and we need to try building a simple game for android device in Godot and see if it is a possible solution for us.

The game will be completey open source because it is a project for learning game development.

## Roadmap

1. Complete the game description.
2. Design the game screens (in draw.io or something simillar).
3. Decide a technology that the game will be implemented in.
4. Decide on a platform.
5. Implement the first 10 minutes of the game.