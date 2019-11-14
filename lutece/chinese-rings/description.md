
# Content

Chinese rings, also known as the Baguenaudier, is a classical mechanical puzzles, which is aimming at removing all n rings from a horizontal loop of stiff wire, and/or put them back on.

![.*](/source/lutece/chinese-rings/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTczLzIwMTQwMjAyMjMzODQyMzk4MzIucG5n.png)

The puzzle is thought to be invented by the famous Chinese general Chu-ko Liang (AD 181-234), in the 2nd century. As a present to his wife so that she would have something to do (solving it!) while he was away at the wars. By the end of the 17th century, it had become popular in many European countries. Later, the French peasants used it to lock chests and called it "time-waster", or Baguenaudier.

Marking the rings from left to right with $0$ or $1$ on specific bit to represent whether the corresponding ring is on the wire or not, respectively. If the Chinese Ring Puzzle with only $4$ rings, the initial state is `0000`. The goal is to remove all of the rings off the horizontal loop on the stiff wire ,i.e. turn the state into `1111`.

![.*](/source/lutece/chinese-rings/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTczLzIwMTQwMjAyMjMzOTM1NzY4MzMucG5n.png)

The rules of Baguenaudier is showed below:
1. The first ring can be moved up and down freely. 
2. Others can only move up or down if the previous ring is still on the wire AND the other rings before have been removed. 
e.g. ring $5$ can be moved onto the wire if and only if ring $4$ is on the wire(state of $0$) and ring $1$,$2$,$3$ are all in the state of $1$.

**The solution of the Chinese rings is intimately related to the theory of Gray codes**. As showed in the table, in the Puzzle of four rings, the relationship between each state and the binary representation of the value of its minimum steps is exquisite and beautiful! Can you find this relationship?

This problem has several queries. Give you a state of Chinese rings, steps , please calculate binary representation of the corresponding minimum step.

# Standard Input

The first line is a integer $T$ ($T\leq 100$), the number of test cases, followed $T$ lines. Each line consists of a binary number, which is not longer than $20$ bits. And there is no leading $0$s. 

**The number of rings equals to the length of the binary number.**

# Standard Output

For each test case, output the required binary representation in one line.

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
<tr><td>3
10
1011
1010110</td><td>11
1101
1100100</td></tr></table>


# Constraints



# Note



# Source


