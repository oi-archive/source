
# Content

After the last war devastated your country, you - as the king of the land of Ardenia - decided it was high time to improve the defense of your capital city. A part of your fortification is a line of mage towers, starting near the city and continuing to the northern woods. Your advisors determined that the quality of the defense depended only on one factor: the length of a longest contiguous tower sequence of increasing heights. (They gave you a lengthy explanation, but the only thing you understood was that it had something to do with firing energy bolts at enemy forces).

After some hard negotiations, it appeared that building new towers is out of question. Mages of Ardenia have agreed to demolish some of their towers, though. You may demolish arbitrary number of towers, but the mages enforced one condition: these towers have to be consecutive.

For example, if the heights of towers were, respectively, $5, 3, 4, 9, 2, 8, 6, 7, 1$, then by demolishing towers of heights $9, 2$ and $8$, the longest increasing sequence of consecutive towers is $3, 4, 6, 7$.

# Standard Input

The input contains several test cases. The first line of the input contains a positive integer $Z\leq 25$, denoting the number of test cases. Then $Z$ test cases follow, each conforming to the format described below.

The input instance consists of two lines. The first one contains one positive integer $n\leq 200000$ denoting the number of towers. The second line contains $n$ positive integers not larger than $1000000000$ separated by single spaces being the heights of the towers.

# Standard Output

For each test case, your program has to write an output conforming to the format described below.

You should output one line containing the length of a longest increasing sequence of consecutive towers, achievable by demolishing some consecutive towers or no tower at all.

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
9 
5 3 4 9 2 8 6 7 1 
7 
1 2 3 10 4 5 6</td><td>4 
6</td></tr></table>


# Constraints



# Note



# Source


