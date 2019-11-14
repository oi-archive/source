
# Content

$4$.$1$, `April Fools' Day` (maybe you know, another lovers' Day), is coming. However, Bob is tired of being single again. As is known for all ACMers, Bob loves Alice very much, so he decides to express his love to Alice. As usual, Alice decides to play a game with Bob to consider whether to accept Bob. 

The game is played on a circle (you are supposed to take it as a ring) which is L meters long. Initially, they are both located at somewhere in the circle, then they start to go around the circle at certain unchanged speeds, clockwise or anticlockwise, the initial direction of Alice is always clockwise. 

The goal of Bob is to catch Alice, that is to say he must be the same position with Alice at last so that Alice will agree to be his girl-friend. Of course, if Bob has caught Alice, the game will end.

However, the way Alice moves has nothing to do with Bob. She will keep going in the current direction, unless she finds Bob is no more than $K$ meters in front of her (the current direction she is going is her front, the other direction is her back). No matter which direction Bob will move, when Alice finds Bob is no more than $K$ meters in front of her, she will stop and turn back immediately then continue to move at her fixed speed. Don't ask me why, you know it's always hard to understand why girls do this do that, maybe Alice is shy, maybe she dislikes Bob, maybe for fun, maybe just no reason, however I don't know either. 

In addition, it takes no time to stop and turn back. Both Alice and Bob can decrease and increase their speeds suddenly.

As a nanxiongnandi of single Bob, can you tell Bob the least time it will cost to catch Alice, or the fact that he will be single forever (Oh, poor Bob).

# Standard Input

The first line is an integer $T (T \leq 10000)$, the number of test cases.

Then $T$ lins follows, each test case one line.

Each line has six integers $L, X\_b, X\_a, V\_b, V\_a, K$, representing the length of the circle, the coordinate of Bob, the coordinate of Alice, the speed of Bob, the speed of Alice, the distance Alice will keep from Bob.

The coordinate of the circle is calculated in this way: choose a point in the circle as the origin point, take clockwise as the direction of the coordinate axis. The coordinate of a position is the distance from the origin point to this point in the clockwise direction.

$1 \leq L \leq 10000, 0 \leq X\_b, X\_a < L, 0 \leq V\_b, V\_a \leq 100, 0 \leq K \leq 10000$

# Standard Output

Each test case, output one number in a line if there is a solution, the answer should be rounded to $5$ digits after the decimal point.

Otherwise output `Impossible` instead.

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
<tr><td>2
5 1 2 1 2 2
10 2 1 2 1 3</td><td>Impossible
1.00000</td></tr></table>


# Constraints



# Note

It may get Wrong Answer if the code has such sentence like : printf("%.5f\n", 0); 

You are supposed to change it to : printf("%.5f\n", 0.0);

# Source


