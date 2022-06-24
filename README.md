# DailyLifeSimulator
This program simulates the everyday life of characters represented by simple assets called AI guys.

They walk around the level doing random activities for about 4 minutes per Day and sleeps for about 2 minutes. Moving around the room, they choose a route to avoid obstacles such as walls or furniture.

The map level has walls and consists of several rooms. They move around avoiding obstacles, but they can walk through each other.

The aim of this project is to practice with Unreal Engine's Blueprints, Behaviour Trees and Environment Query System.

</br>
<p align="center">
<img src="https://raw.githubusercontent.com/pikumb94/DailyLifeSimulator/master/Resources/Gameplay.gif" width="640" height="360" />
</p>

## Activities
AI guys can perform various activities for a certain period:
* Idle
* Sitting
* Reading: AI guy looks for a place to sit, then sits down and starts the book reading animation.
* Smoking: AI guy looks for a place where he can stand and activates the animation of smoking a cigarette.
* Drinking coffee: AI guy looks for a table at which he can sit, then sits down and starts the coffee drinking animation.
* Playing on console: 1, 2 or 3 AI guys find a console and start playing it.

* Conversation: between two or more AI guys (Bubble icons appear above their heads)
    * Standing: AI guys find a random place to stand next to each other and start talking.
    * Sitting: AI guys find a random empty seat at the table or sofa and sit there to chat.
* Smoking and talking: 2 or more AI guys find a common place where they smoke and talk.
* Ping pong: 2 AI guys finds a shared ping pong table, they go to it and then start the ping pong animation.

* Sleeping: sleep for about 2 minutes per AI Day at night. If they have free beds, they go to bed, if not, they go to sleep on the floor.
## AI guys
There are three kinds of people.
* Yellow guys: has no preference of activities.
* Red guys: are much more likely to doing lone activities (and they do for a longer period of time).
* Blue guys: are much more likely to doing lone activities (and they do for a longer period of time).

### Disclaimer
Everything has been done using Unreal Engine 4.27.2 version.
The project is an __early__ prototype and needs code refactoring and cleaning.
