
# Content

Bob and Alice are playing a new game. There are $n$ boxes which have been numbered from $1$ to $n$. Each box is either empty or contains several cards. Bob and Alice move the cards in turn. In each turn the corresponding player should choose a non-empty box $A$ and choose another box $B$ that $B<A$ and $A+B\pmod{2}=1$ and $A+B\pmod{3}=0$. Then, take an arbitrary number (but not zero) of cards from box $A$ to box $B$. The last one who can do a legal move wins. Alice is the first player. Please predict who will win the game.

# Standard Input

The first line contains an integer $T$ ($T\leq 100$) indicating the number of test cases. The first line of each test case contains an integer $n$ ($1\leq n\leq 10000$). The second line has $n$ integers which will not be bigger than $100$. The $i\_{th}$ integer indicates the number of cards in the $i\_{th}$ box.

# Standard Output

For each test case, print the case number and the winner's name in a single line. Follow the format of the sample output.

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
2 
1 2 
7 
1 3 3 2 2 1 2</td><td>Case 1: Alice 
Case 2: Bob</td></tr></table>


# Constraints



# Note



# Source


