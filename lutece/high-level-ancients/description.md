
# Content

Love8909 is keen on the history of Kingdom ACM. He admires the heroic undertakings of Lxhgww and Haibo. Inspired by those sagas, Love8909 picked up his courage and tried to build up his own kingdom. He named it as A230.

After hard working for several years, Love8909 is about to fulfill his dream. However, there is still one thing to do: setting up the defense network. As Kingdom EDC looks at territory and people of A230 fiercely as a tiger does, Love8909 has to make it as soon as possible.

The defense network Love8909 wants to use is the same as the one used by Lxhgww and Haibo. He also connects all cities with roads which form a tree structure, and the capital city is City $1$, which is the root of this tree. Love8909 sends commands to inform cities to add soldiers. The command, being same to those of the ancients, with two values, $X$ and $K$, means sending $K$ soldiers to City $X$, sending $K + 1$ soldiers to sons of City $X$, sending $K + 2$ soldiers to sons of sons of City $X$ and so on. Initially there are no soldiers in any city.

![title](/source/lutece/high-level-ancients/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTc0LzIwMTQwODI3MjEyMjE3ODExMjEuanBn.jpg)

Love8909 may adjust the arrangement of soldiers ever and again. He asks questions about how many soldiers in the subtree rooted at City $X$. A subtree rooted at City $X$ includes City $X$ itself and all of its descendants. As Love8909's military counselor, you are responsible to complete all his commands and answer his questions.

# Standard Input

The first line of the input will be an integer $T$ ($T \leq 20$) indicating the number of cases.

For each case, the first line contains two integers: $N$ $P$, representing the number of cities in A230 and number of operations given by love8909. 

The next line lists $N-1$ integers, in which the $i\_{th}$ number, denoted as $X\_i$, represents there is a road from City $X\_i$ to City $i$. Note that the City $1$ has been omitted. $1 \leq X\_i \leq N$ for $2 \leq i \leq N$.

Then $P$ lines follow, each gives an operation. Each operation belongs to either kind:
* `A X K`. An adding-soldier command.
* `Q X`. A question about how many soldiers in the subtree rooted at City $X$.

We guarantee that the cities form a rooted tree and the root is at City $1$, which is the capital.

$1 \leq N \leq 50000$, $1 \leq P \leq 100000$, $1 \leq X \leq N$, $0 \leq K \leq 1000$.

# Standard Output

For each case, print `Case #k:` first in a single line, in which $k$ represents the case number which starts from $1$. Then for each `Query X` operation, print the answer in a single line.

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
7 10
1 1 2 2 5 5
Q 1
A 2 1
Q 1
Q 2
Q 5
A 5 0
Q 5
A 3 1
Q 1
Q 2</td><td>Case #1:
0
11
11
8
10
14
13</td></tr></table>


# Constraints



# Note

**Huge input/output. Please use `scanf/printf` for `C/C++`.**

In the first case, adding $1$ soldier to City $2$ leads to $11$ soldiers needed in total.

# Source


