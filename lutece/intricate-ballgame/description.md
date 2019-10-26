
# Content

Three students are playing a game in their spare time. Student A and Student C are in one team (Student A can be used to refer to this team), Student B himself is the other team. Behind Student B there's a chair, and Student C is keeping a goal behind him. Student A repeatedly throws a ball in the direction of Student B, and Student B aims to `defend the chair`, that is to kick the ball thrown to the chair away, and if possible, to kick into the goal Student C keeps. The playing field has $3$ lines, including the goal line, the area among which is counted as in play. The detailed rule of the game is:
1. if Student B does not try to kick the ball, just let the ball pass
  1. if the ball hits the chair, Student A get $1$ point.
  2. else, Student B get $1$ point
2. if Student B tries to kick the ball
  1. if he misses the ball, then Student A get $1$ point, regardless of the ball hits the chair or not
  2. if he contacts(not misses) the ball
    1. if the ball is kicked into the goal Student C keeps, then Student B wins the game.
    2. if the ball is caught by Student C in play, then Student A wins the game.
    3. if the ball is out of play(regardless of it is directly kicked out of play, or deflected out of play by Student C)
       1. if Student A has already $2$ points scored, then both sides do not score.
       2. else, Student A get $1$ point.
3. if Student A scores $3$ points, then he wins; if Student B scores $4$ points, then he wins
4. the game will go on indefinitely until one side win the game.

Now you have information below(thats also the input):
1. the `out of play` percentage of Student B, that means the proportion of balls kicked out of play among balls contacted by Student B.
2. the goalkeeping success rate of Student C: that means when ball in play(scenarios `2.2.1` and `2.2.2`), the conditional probability that Student A wins the game
3. the throwing accuracy of Student A: that means if Student B always do not try to kick the ball, the percentage of balls that hit the chair.
4. the `ball selection` accuracy of Student B: when the ball `will hit the chair if not kicked`, the probability the Student B tries to kick this ball.
5. the `ball selection` mistake rate accuracy of Student B: when the ball `will not hit the chair if not kicked`, the probability the Student B tries to kick this ball.
6. the ball kicking contact rate of Student B: when Student B tries to kick the ball, the probability he contacts (not misses) the ball.

Assume these probabilities are same in every kick.

Your mission is to calculate the probability that Student A wins the game. 

![.*](/source/lutece/intricate-ballgame/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTEzLzIwMTQwMTI5MTQyMTAzNTY2NS5qcGc=.jpg)

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases.

One line per test case, a to f according to the order above, blank separated. All input numbers have $4$ digits after decimal point.

# Standard Output

One line per test case, indicating the probability that Student A wins the game. Output $3$ digits (`%.3f`) after the decimal point.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1
0.2530 0.2696 0.5530 0.5610 0.2350 0.8430</td><td>0.379</td></tr></table>


# Constraints



# Note



# Source


