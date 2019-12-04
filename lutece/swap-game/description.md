
# Content

Last week, children of the kindergarten which Lily attends organized a dinner party to welcome children from their neighborhood kindergarten. Lots of candy and fruit were offered and children all had a good time. What’s more, they played a special game designed by Miss Xue. In this game, children of each kindergarten wore clothes with specific color. The color assigned to clothes for Lily’s kindergarten is red, and for the neighborhood kindergarten is blue. 

Children stood in a circle. Adjacent children could swap their place with each other. Miss Xue asked the children to swap so that in the end children of the same kindergarten formed a consecutive sequence.

![title](/source/lutece/swap-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDkwLzIwMTQwODI0MjExMTQ1OTMxMzIucG5n.png)

This game is so funny that everyone was happy. However, Lily wants to know what the minimum number of swaps is needed for children to accomplish the game, given the initial state of the circle. Can you tell her?

# Standard Input

First an integer $T$ ($T \leq 20$), indicates the number of test cases.

Every test case contains a string which represents the color of clothes children wore at each place. Specifically, $i\_{th}$ element of the string is `R` if the child stood at $i\_{th}$ place is from Lily’s kindergarten, `B` otherwise. Note that the first child is adjacent with the last one. The length of the string is not greater than $100000$.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and counts from $1$. Then output the minimum number of swaps needed.

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
RBRBR
BBRBBRBBBRRR</td><td>Case #1: 1
Case #2: 5</td></tr></table>


# Constraints



# Note



# Source


