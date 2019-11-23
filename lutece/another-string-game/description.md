
# Content

Bob and Alice like playing games together. Today, they come up with a new string game.

The rule of this game is like the following statement:

Initially, Alice has a string $A$. Then Bob can choose a prefix of string $A$ as his initial string $B$ and pay a cost equals the length of his initial string $B$ multiplied by $X$. (for example: if Alice's string is `abc`, then Bob can choose `a` and pay $X$ cost, or choose `ab` and pay $2 \times X$ cost, or choose `abc` and pay $3 \times X$ cost)

After that,Bob can perform the following two operations:

Operation I: Connect a copy of his string after his string, and pay a cost equals $Y$. (for example: after performing operation $1$ Bob can change `ab` to `abab` or change `aac` to `aacaac`).

Operation II: Delete a suffix of his string, and pay a cost equals $Z$.(for example: after performing operation $2$ Bob can change `abcd` to   `a`, `ab`, or `abc`).

When Bob's string is the same as Alice's string, the game is end.
Now, Bob wonders what's the minimum total cost he must pay after the end of the game?

# Standard Input

There is an integer $T$ in the first line, indicates the number of test cases.

 For each case, the first line contains a string $A$, which is Alice's string, <span style="color : red">it only contains lowercase letters.</span>

The second line contains three integer $X$, $Y$, $Z$, as mentioned in the description.

$1\leq T\leq 60$

$1\leq |A|\leq 10^{5}$

$1\leq X, Y, Z \leq 10$

# Standard Output

For each test, output "Case #i: " first, $i$ is the case number, from $1$ to $T$. Then output an integer in one line, which is the minimum cost Bob must pay.

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
abcab
1 2 4
abcab
2 2 1
aaaaaaaa
1 1 1</td><td>Case #1: 5
Case #2: 9
Case #3: 4</td></tr></table>


# Constraints



# Note



# Source


