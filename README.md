# bowling_ball_game
It is a Program, which, given a valid sequence of rolls for one line of American Ten-Pin Bowling, produces the total score for the game.

Problem Statement :

Bowling ball scoring
Create a program, which, given a valid sequence of rolls for one line of American Ten-Pin Bowling, produces
the total score for the game. Here are some things that the program does not need to do:

• Does not need to check for valid rolls.

• Does not need to check for correct number of rolls and frames.

• Does not need to not provide scores for intermediate frames.

You can find more information about how a bowling game is scored below.
How are bowling games scored?
The game consists of 10 frames as shown above. In each frame the player has two opportunities to knock
down 10 pins. The score for the frame is the total number of pins knocked down, plus bonuses for strikes and
spares.
A spare is when the player knocks down all 10 pins in two tries. The bonus for that frame is the number of pins
knocked down by the next roll. So in frame 3 above, the score is 10 (the total number knocked down) plus a
bonus of 5 (the number of pins knocked down on the next roll.)
A strike is when the player knocks down all 10 pins on his first try. The bonus for that frame is the value of the
next two balls rolled.
In the tenth frame a player who rolls a spare or strike is allowed to roll the extra balls to complete the frame.
However no more than three balls can be rolled in tenth frame.

LOGIC :

1 Set 

X - 10

Total = 20

2 Set

9 

1 /(Spare)

20 + 10 + 5 = 35

3 Set

5 

5 /Spare

35 + 10 + 7 = 52

4 Set

7

2 

52 + 9 = 61

5 Set

X

61 + 10 + 10 + 10 = 91


6 Set

X

91 + 10 + 10 + 9 = 120

7 Set

X

120 + 10 +9 = 139

8 Set

9

148

9 Set 

8 

2 /Spare

148 + 10 + 9 = 167

10 set

9 

1 /Spare

10

167 + 10 + 10 = 187

