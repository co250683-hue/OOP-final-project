[OOP-SUBMISSION-DOCU.md](https://github.com/user-attachments/files/34524209/OOP-SUBMISSION-DOCU.md)
# PROJECT TOPIC: DOORS ESCAPE

## GROUP MEMBERS & CONTRIBUTIONS

| Group Members (Last Name, First Name) | Contribution |
| :--- | :--- |
| **1. Banguih, Robb Chryzler** | Coding the JFrames, fixing any bugs, in addition to editing and compiling the video demonstration video |
| **2. Jaldon, Ma Candice** | Implementing the images in the program, in addition to detailing and designing them |
| **3. Jaldon, Ma Eunice** | Providing Dialogue in the story as well as designing and creating the images needed for this project |
| **4. Olla, Jhulian Marquez** | Providing the Idea and Key Concepts of the Game itself |
| **5. Villarante, Jassim H.** | Coding the Core Structure of the game as a form of a foundation in order for the groupmates to add-on and improve. |

# USER DOCUMENTATION (EXTERNAL)

**Project Name:** DOORS ESCAPE  
**Project Type:** Game  

## INTRODUCTION

This is a simple door maze game made for those who are interested in solving simple puzzles or riddles. It mainly features abstraction, encapsulation, inheritance, polymorphism, and custom exception handling with a polished user interface featuring a typewriter-style narrative intro, a custom dark theme engine, and an interactive companion character named Pixie. The players need to accomplish all the door questions till they reach the end for the game to finish.

## MAIN SCREEN

### 1. Main Menu Screen
* Displays the game name ("DOORS ESCAPE") at the top.
* Shows basic instructions in the center on how to play.
* A button at the bottom labeled "START GAME". Click it to launch the introductory story and begin playing.

### 2. Introductory Dialogue Screen
* Shows a screen and label on who is currently talking (e.g., Narrator or Pixie).
* Displays the story text using a typewriter effect in a box.
* Click to advance through the story lines until you enter the game.

### 3. Main Gameplay Screen
* Shows your current room number or stage at the top.
* Displays the core riddle or hint in the center of the screen.
* Two buttons at the bottom representing your choices. Click one to submit your answer.

### 4. Lives
* The Player only gets one life, so when they fail they die and end the game.

## 3.1 OBJECTIVE AND RULES

* The players must carefully read riddles in each room and select either the left or right door to advance.
* To win, you must successfully survive all standard rooms and navigate a tricky, multi-stage final room twist.
* There are no extra lives or checkpoints, meaning a single incorrect choice results in an immediate game over.

## 3.2 CONTROLS

* **FOR answering riddles:**
  * **Left Button:** Choice A
  * **Right Button:** Choice B
  * **Pixie Escapes / Yes, leave her alone:** Ending A
  * **Save Yourself:** Ending B

* **FOR main controls (dialogues and menu):**
  * **START GAME Button:** Start game
  * **SKIP Button:** To skip dialogues
  * **NEXT Button:** To go to the next dialogue
  * **OK Button:** To go to the next room

## 3.3 HOW TO PLAY

* Click **START GAME** button to start the game.
* Read dialogues (a small guide) provided by the Pixie.
* Answer the following riddle/puzzle with either the **Left** or **Right** button.
* **The game ends when:**
  * **(Win)** You survived and escaped till the end
  * **(Lost)** You died / The other choice at the final stage
* You only have one life. So when you pick the wrong door it’s already game over.

## 3.4 OTHER ACTIONS

* Players can exit the game by pressing the **EXIT** button in situations where they will see them, or by closing the window.

## IMPORTANT REMINDERS

* There are only six rooms; if it goes beyond that, it will trigger an error and exit the program (since the array is capped at 6).
* The game only accepts `'L'` (Left) or `'R'` (Right) choices. Entering any other key triggers a custom `InvalidChoiceException`.
* There are no health bars, lives, or retries. Making a single incorrect choice immediately ends the game session.
* Because there are no checkpoints or save slots, you cannot delete a save file or restart a run from within the game interface; players must close and re-launch the application to play again.
