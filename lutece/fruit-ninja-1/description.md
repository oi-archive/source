
# Content

<p class="text-right"><i>In Fruit Ninja, the player slices fruit with a blade controlled via a tablet. As the fruit is thrown onto the screen, the player swipes their finger across the screen to create a slicing motion, attempting to slice the fruit in half.<br/>
--- Wikipedia</i></p>

Fruit Ninja is a very popular game and XNJ likes it very much. After the game player can get a bonus based on his/her score.
* Bonus $1$: If the score is a multiple of $5$, the player gets a bonus of $M$.
* Bonus $2$: If every digit of the score is the same, the player gets a bonus of $N$.

Note that if the score satisfies both conditions, the player gets a bonus of $M + N$. :)

One day when playing on it, XNJ came out an idea: if he can keep getting bonus until satisfying neither conditions, how much he can get? For example, given $M = 3$, $N = 8$, and the initial score is $55$. The score $55$ satisfies both conditions and the player gets a bonus of $3+8 = 11$. Then the score increases to $66$, which leads another bonus of $8$. When it reaches $74$, no more bonus is available. So the final score is $74$. 

Assume that XNJ can get any initial score between $1$ and $10000$, he wants to know what's the maximum final score he can get?

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 15$) indicating the number of test cases.

For each test case there are two integers $M$ and $N$ ($1 \leq M, N \leq 50$) in a single line.

# Standard Output

For each test case, print `Case #t: ` first, in which t is the number of the test case starting from $1$. Then output the maximum final score he can get. If it can be added endless, output `INF`. The data ensures that result is in a signed $64$-bit int bound, i.e. the result is smaller than $2^{63}$.

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
24 50
10 1</td><td>Case #1: 10049
Case #2: INF</td></tr></table>


# Constraints



# Note



# Source


