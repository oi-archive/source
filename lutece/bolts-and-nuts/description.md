
# Content

When visiting the Sun Island during 2010 ACM/ICPC Asia Regional Contest Harbin Site, Cc and Zxh found a lot of bolts(螺栓) and nuts(螺帽). They decided to play a game using them. 

The rule is: they handle these bolts and nuts in turn and always begin with Cc in every game. In every turn one of them can do one of these three operations:
1. pair a nut and a bolt;
2. throw a single nut which was not pair with any bolt into the river; 
3. throw a single bolt which was not pair with any nut into the river;

Of course, every bolt can only be paired with one nut at most.The same with every nut.

The game will be end with one of Cc and Zxh founding they can't do any one of these three operations, and this player is loser.

You are required to write a program to determine who will be the winner in a game.

Suppose that both of Cc and Zxh are clever and they will do their best in the game.

# Standard Input

The first line of the input contains one integer $T$($T\leq 200$), which indicates the number of test cases.

Then, $T$ lines follow. Every line indicates one test case. Every test case only contains two integers $a$,$b$($0\leq a,b\leq 10000$),the number of bolts and nuts.

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$.
Then, output the winner of the game, `Zxh` or `Cc`.

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
0 0
1 1
1 2</td><td>Case #1: Zxh
Case #2: Cc
Case #3: Cc</td></tr></table>


# Constraints



# Note

The first case of the sample, there is no bolt or nut and begin with Cc, so Cc lose.

The second case,Cc can pair the nut and bolt first, then there is no single bolt or nut ,so Zxh lose.

The third case Cc can throw a bolt into the river, then left two nuts,Zxh can only throw a nut into the river, and Cc throw away the last nut.Now, there is no bolt or nut, so Zxh lose.

# Source


