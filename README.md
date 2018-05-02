Shahwaiz Nassar
snassar3@gatech.edu
snassar3

Kevin Lee
kk@gatech.edu
klee639

Andrew Hu
ahuman87@gatech.edu
ahu37

Ollie Foo
ofoo3@gatech.edu
ofoo3

Eduardo Mestanza
emestanza3@gatech.edu
emestanza3

------------------------------------------------------------------------------------------

No extra installations required other than Unity

------------------------------------------------------------------------------------------

UP, DOWN, LEFT, RIGHT - ARROW KEYS
X - SWITCH CHARACTER
C/Z - CHANGE CAMERA
SPACE - JUMP
ESC - PAUSE

------------------------------------------------------------------------------------------
All levels include textures and is a complete game from beginning to end, allowing it to be a 3D Game Feel game.

Objectives are clearly stated on Start menu, as well as controls for the player to use. Levels get progressively harder and allow user to have more control. For example, the ability to switch between characters.

All scenes have a pig which is controlled by the player with engaging animations that react to the player's inputs. The controls are intuitive because it uses keyboard arrows for movement, similar to many other computer video games.

Levels 1 & 3 incorporate state-machine based Artificial Intelligence. This AI is included in the robot detecting the pig. The interactions are critical to getting to the final checkpoint.

Level 3 utilizes rigid body physics simulation with interactive objects (crates).

Level 3 has environment that acknowledges the player. This is apparent with the fans that push the player around.

------------------------------------------------------------------------------------------

Known bugs:
Sometimes the piggy may phase through floor in the ramp of Level 3. If you ever fall endlessly, press ESC and 'restart from checkpoint'.
The crate to be placed on the big switch button (for bridge activation) in Level 3 sometimes doesn't trigger the switch. Player needs to move it around a little.
The robot in level 3 protecting the bridge activation can get stuck from the crates. But the player must move the crates to win so the player can still move the crates.

------------------------------------------------------------------------------------------

No external resources used

------------------------------------------------------------------------------------------

Shahwaiz - Create Start Game Screen, Pause Menu Screen, Objectives Screen
Kevin - Create Pig Model, Rigging and Keyframe Animation, Sounds and Textures
Ollie - Movement controller, Camera controller, pig abilities, switching pigs
Edu - Code for AI Behavior, Fan Behavior and Physics in Level 3, Designer of Level 1 & 3
Andrew - Checkpoint Management, Pause Menu Logic, Designer of Level 2 and Environment Logic for Level 2

------------------------------------------------------------------------------------------
Open scene labeled "Menu" for title screen, which allows gameplay by clicking 'start game'
Open scene labeled "Level 1" in Unity for direct gameplay
