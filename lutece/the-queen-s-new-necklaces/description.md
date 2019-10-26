
# Content

Long ago and far away, there lives a Queen in the country of ByteLand. This Queen is very vain and could think about nothing but her jewelry, especially her necklaces. She orders her craftsmen to make for her a new necklace every day. And if they can't hand in a necklace which the Queen hasn't seen before, they will be executed.

The necklace these craftsmen make is a circular string of diamond beads, each bead has one of $M$ different colors. In addition, for aesthetical reasons a necklace must have exactly $K_i$ beads with color $i$, for $1 \leq i \leq M$. Two necklaces are the same if the colors of their beads exactly match. Note rotations of a necklace do not change it, however reflections are considered to be different. For example, `(RBRB)` and `(BRBR)` are the same necklaces, but `(BRBBRR)` and `(RRBBRB)` are not, where `R` and `B` represent the color `red` and `blue`, respectively.

The craftsmen know that some day they will run out of new necklaces, so they decided to escape from the country. However the security of ByteLand is very tight so they have to first plan their escape to every detail, and that requires a lot of time. Now the craftsmen want to know, how many different necklaces they can make, which satisfies the constraints above, so they can see whether they will have enough days to make up the escape plan.

# Standard Input

There are several test cases. The first line is an integer giving the number of cases. Each test case begins with a positive integer $M (0 < M \leq 100)$ on a line, which is the number of different colors. The following line contains $M$ positive integers, $K_1$ … $K_M$, the number of beads with color $i$ a necklace must have exactly. You can assume that the sum of all $K$ will not exceed $1000$.

# Standard Output

For each test case, you should output one line containing the number of different necklaces the craftsmen can make.

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
1
10
2
2 3</td><td>1
2</td></tr></table>


# Constraints



# Note

For the second case, the two distinct necklaces are `(11222)` and `(12122)`. Anyone else, such as `(21212)`, can be obtained by rotating one of these two necklaces.

# Source


