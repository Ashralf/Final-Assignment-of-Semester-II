# Final-Assignment-of-Semester-II
*Question*:

Develop a Java program for an online multiplayer game to track a player. The program must utilize two
arrays:
- (a) The first array to store the player ID’s (For example: A0010, U0034, E1045)
- (b) The second array to store the active play durations in hours for 8 players.

The program should prompt the user to input the player ID and active play duration for each player.
From each player ID, extract and store the first character, which represents the designated server region
(For example: 'A' represents Asia server, ‘U’ represents United States, E represents Europe and so
on).

After the data entry phase, the program should allow the user to input a specific region letter for linear
searching purposes. If any players are associated with the specified region, the program must display:
-  The index positions of the matching players,
-  Their respective active play durations,
-  The total number of players connected to that region.
If no players are found in the specified region, the program should display an appropriate message
indicating that no players are found in that region.
