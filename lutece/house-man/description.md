
# Content

In somewhere, there is a crazy super man. He can’t fly, but he could jump from housetop to housetop. Today he plans to use $N$ houses to hone his house hopping skills. He will start at the shortest house and make $N-1$ jumps, with each jump taking him to a taller house than the one he is jumping from. When finished, he will have been on every house exactly once, traversing them in increasing order of height, and ending up on the tallest house. 

The man can travel for at most a certain horizontal distance $D$ in a single jump. To make this as much fun as possible, the crazy man want to maximize the distance between the positions of the shortest house and the tallest house. 

The crazy super man have an ability—move houses. So he is going to move the houses subject to the following constraints:
1. All houses are to be moved along a one-dimensional path. 
2. Houses must be moved at integer locations along the path, with no two houses at the same location. 
3. Houses must be arranged so their moved ordering from left to right is the same as their ordering in the input. They must NOT be sorted by height, or reordered in any way. They must be kept in their stated order. 
4. The super man can only jump so far, so every house must be moved close enough to the next taller house. Specifically, they must be no further than $D$ apart on the ground (the difference in their heights doesn't matter). 

Given $N$ houses, in a specified order, each with a distinct integer height, help the super man figure out the maximum possible distance they can put between the shortest house and the tallest house, and be able to use the houses for training.

# Standard Input

In the first line there is an integer $T$, indicates the number of test cases.($T\leq 50$)

Each test case begins with a line containing two integers $N$ ($1\leq N\leq 10000$) and $D$ ($1\leq D\leq 100000$). The next line contains $N$ integer, giving the heights of the $N$ houses, in the order that they should be moved. Within a test case, all heights will be unique.

# Standard Output

For each test case , output `Case #d: ` first where d is the case number counted from one, then output a single integer representing the maximum distance between the shortest and tallest house, subject to the constraints above, or $-1$ if it is impossible to lay out the houses. Do not print any blank lines between answers.

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
4 4 
20 30 10 40 
5 6 
20 34 54 10 15 
4 2 
10 20 16 13</td><td>Case #1: 3
Case #2: 3
Case #3: -1</td></tr></table>


# Constraints



# Note



# Source


