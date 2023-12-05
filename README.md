# Clash of The Jungle

![ClashofTheJungle](https://github.com/William3152/William3152/assets/116702856/f5a6ebb5-c334-42b2-8429-baa840eb46c6)

Welcome to Animal Kingdom Defense, an exciting tower defense game where the Animal Kingdom unite to defend their land against the encroaching human forces. Get ready for an epic battle between nature and civilization!

## Overview

Clash of The Jungle is a tower defense game that offers a unique twist by pitting the diverse inhabitants of the animal kingdom against human invaders. Players must strategically deploy animal defenders to thwart waves of human attackers and prevent them from taking over the natural habitats.

## Features

- **Diverse Animal Defenders:** Choose from a variety of animal warriors, each with its own unique abilities and strengths. 

- **Challenging Levels:** Face a series of challenging levels, each with increasing difficulty. Adapt your strategy as you encounter new human threats and overcome obstacles to protect the animal kingdom.

- **Resource Management:** Collect resources throughout the game to unlock new animals, upgrade tower and animals, and gain the upper hand against the human invaders.


## How to Play

1. **Deploy Defenders:** Strategically place animal defenders along the path of the human invaders. Consider the unique abilities of each animal to create a formidable defense.

2. **Upgrade Animals:** Earn resources by defeating human attackers and use them to upgrade your animal. Strengthen your defenses to face increasingly powerful waves of enemies.

3. **Adapt to Challenges:** Be prepared to adapt your strategy as the game progresses. Face new challenges, overcome obstacles, and unlock additional animals to enhance your defense.

4. **Survive and Thrive:** Fight off waves of human invaders and strive to protect the animal kingdom. The more waves you repel, the stronger and more resilient your animal defenders become.

## Player Control 

Player can use these button to control the camera movement on the game 
| Key          | Function       | Description                 |
| ------------ | ---------------| ----------------------------|
| A            | Camera Movement| Move the camera to the left |
| D            | Camera Movement| Move the camera to the right|

## Supporting Scripts

These are scripts that used to help run the game.

| Script Name           | Description                                          |
| --------------------- | ---------------------------------------------------- |
| `BallControl.cs`      | Controls the behavior of a ball, including its initial launch and how it interacts with player objects.  |
| `GameManager.cs`      | Manages the scores of two players in a game, updates the UI to display the scores, and checks for a win condition where a player reaches a score of 20 to trigger a scene change to the main menu. |
| `PlayerControls.cs`   | Allows the player object to move up and down within specified bounds using the "moveUp" and "moveDown" keys. The script continuously updates the player's position and velocity based on user input and ensures the player stays within the defined bounds.               |
| `SceneManagement.cs`  | Allows for the switching of game scenes by providing the name of the target scene to the "ChangeScene" method. It also enables the player to exit the game application using the "QuitApp" method.       |
| `SideWall.cs`         | Designed to be attached to side walls and serves for scoring by keeping track of when a ball collides with it, identifies the specific wall that was hit, and updates the player's score accordingly. It also can be used to restart the game by sending a message to the ball object to restart the game, possibly after a brief delay, by invoking the "RestartGame" method defined in the "BallControl" script.                 |


## Credits

- Game Programmer: William Wijaya (Develop the core gameplay and gameplay experience in the game)
- Game Artist: Vincent Hungadi (Making different animal and human character along with its animation)
- Free Asset Used:
  
## Contact

If you have any questions or suggestions, you can contact us via email at [williamwijaya010803@gmail.com].

Thank you for using Clash of The Jungle!
