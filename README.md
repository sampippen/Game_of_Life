# Game_of_Life
John Conway's Game of Life in C

Name: Samuel Pippen

Program purpose: This program is a recreation of John Conway's Game of Life. The main premise is that the game starts with a "world" which is a random design, and in this case, it
is stored in a text file. The asterisks start off as a sort of living creature and certain rules allow for the creation of birthing neighbors; for example, depending on the number
of asterisks next to each other, a new neighbor is born. Certain rules are also in place to destroy creatures depending on the number of neighbors surrounding them. This is a zero
player game - just sit back and watch populations of asterisks live and die in the Game of Life.

Program functionality: The program starts off by reading in a text file which contains the starting grid of asterisks and periods. The text file is then copied into a 2D array.
Then, therules of the game are applied, changing the locations of the asterisks based on the number of neighbors surrounding each asterisk. After that, the grid is displayed to the
screen. The number of times the program iterates is based on the user input when initially executing the program.

NOTE: The "world"/grid/text file cannot exceed 48x78 lines if running in Linux.
      Can run in IDEs such as CLion but the grid doesn't look nearly as good. Linux suggested.

How to run this program:
1. unzip program (type: unzip life.zip)
2. compile the program and create the executable (type:  make)
3. execute the program with the image file and number of iterations passed in as an argument (type:  ./life world.txt 315)

Known issues/bugs: N/A
