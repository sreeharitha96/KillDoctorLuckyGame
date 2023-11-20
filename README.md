
The /src and /test folders are kept private for this project to adhere to Academic Integrity. The executeable jar file is under /res folder and in case of any queries please reach out to me.

The main theme of this project is to create, design, implement and test our own world game along with ten main features to be implemented in four milestones.

### List of Features

Features of "Doctor Lucky's Mansion" are:

1. Adds a human player based on the user inputs given on the console.
2. Adds a computer player based on the user input given on the console.
3. Moves the human player to the specified room based on the turn of the player.
4. Player can look around from the current room and get the room details.
5. Player can pick a weapon from the current room location.
6. Target moves around the world after every turn in the world till the maximum turns are reaached.
7. Player can see the details of a room by specifying the room index.
8. Player details will be displayed on the console along with the list of weapons carrying.
9. Game will be ended once the maximum turns will be reached.
10. Pet can be moved by the human/computer player to the desired room.
11. Pet moves automatically following Depth First Traversal algorithm when no player moves it in a turn.
13. Target can be attacked by human/computer player when no players are seeing the current player or the room is invisible.(the room becomes invisible when pet is present in that room)
14. Player who makes the target health to zero wins the game and the game ends.
15. When maximum turns are completed and if target is not killed by then, then no player wins.

### How to Run

run the below jar file in the command prompt:
java -jar cs5010-project-sreeharitha1396.jar mansion.txt 150

to run the application in IDE:
Go to run-> run configurations, in environment variables field put the path where "mansion.txt" file
is stored on your PC along with the integer value for maximum number of turns in the game and then
select "run".

### How to Use the Program

Console displays below options from which we need to enter any one option and respective inputs for
the selected option:
"Please enter the correct number of the selected option.

1. Display Room Details
2. Create Graphical Representation
3. Add Human Player
4. Add Computer Player
5. Move Player
6. Pick Weapon
7. Look Around
8. Display Player Details
9. Move Pet
10. Attack Target
   (Please enter QUIT for ending the game.)
   "

When 1 is selected we need to enter the room id. When 2 is entered no need of any inputs. When 3 is
selected user need to enter the details of the human player as specified. When 4 is selected user
need to enter the details of the computer player as specified. When 5 is selected the player whose
the turn will be moved accordingly. When 6 is selected the player can pick a weapon by entering the
weapon id. When 7 is selected the player gets neighbours for the current location. When 8 is
selected player details will be displayed. When 9 is selected the pet can be moved to desired room. When 10 is selected attack on target character can be performed.

### Example Runs

There are totally 15 examples runs which are under "res" folder in the form of text files.

### Design/Model Changes

One change which is made in the design is, now Pet class is added to the design. So now I implemented
both and updated my UMl design as well.

### Assumptions

1. "Poke in Eye" weapon is having weaponId= 22. So when player has no weapons, he is given option to enter 22 so that "poke in eye" can be used.

### Limitations

No Limitations.

### Citations

Reference: https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph/
Using the above link I created the DFS algorithm for the pet movement.


    


