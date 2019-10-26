
# Content

Bees are amazing creatures. They build complex beehives which are of great aesthetical value and they form clear and strict `social` structures, where each bee works hard to play its role, sacrificing itself willingly and unhesitantly if needed.

More amazing is the bee's family tree. A male bee is produced asexually from a female, meaning he has only one parent, his mother. On the other hand, a female bee has two parents, a male and a female. In the family tree below, starting from the male bee at the bottom, he has a mother, one `grandpa` and one `grandma`, one great-grandpa and two great-grandmas, two great-great-grandpas and three great-great-grandmas, etc.

![.*](/source/lutece/bee-tree/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjQvMjAxNDAxMDExMTQwMjg4ODc0LmpwZw==.jpg)

Now this curious male bee wants to know, how many greatn-grandpas and greatn-grandmas he has in his family tree.

# Standard Input

The first line is an integer $T$, number of test cases. Next $T$ lines each contains a single integer $n$.

$0 \leq n \leq 40$

# Standard Output

For each test case, output two integers, number of greatn-grandpas and number of greatn-grandmas this male bee has, respectively.

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
0
1
2</td><td>1 1
1 2
2 3</td></tr></table>


# Constraints



# Note

The grandpa and grandma of this male bee are the parents of his mother, and they are considered the great0-grandpa and great0-grandma, respectively.

If bee $A$ is the greatn-grandpa(or grandma) of this male bee, then $A's$ father(if it has any) is the greatn+1-grandpa, and $A's$ mother the greatn+1-grandma of this male bee, respectively.

# Source


