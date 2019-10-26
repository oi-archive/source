
# Content

You are given a necklace consists of $N$ beads linked as a circle. Each bead is either crystal or jade.
Now, your task is:
1. Choose an arbitrary position to cut it into a chain.
2. Choose either direction to collect it.
3. Collect all the beads in the chosen direction under the constraint that the number of crystal beads in your hand is not less than the jade at any time.

Calculate the number of ways to cut meeting the constraint.

# Standard Input

In the first line there is an integer $T$, indicates the number of test cases. ($T\leq 50$)
Then $T$ lines follow, each line describes a necklace. `C` stands for a crystal bead and `J` stands for a jade bead. The length of necklace is between $2$ and $10^6$.

# Standard Output

For each case, print `Case x: d` on a single line in which $x$ is the number of case counted from one and d is the number of ways.

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
CJCJCJ
CCJJCCJJCCJJCCJJ</td><td>Case 1: 6
Case 2: 8</td></tr></table>


# Constraints



# Note



# Source


