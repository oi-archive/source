
# Content

The toilet in Freddy's garden is broken, so his only chance are public toilets nearby. One day,there is a long queue of people in front of the toilets. Freddy is in a big need and so he desperately wants the queue to be served as quick as possible.

To use the toilets, you need to pay 5 crowns. Half of the people in the queue have a $5$-crown coin and the other half only have a $10$-crown coin. Initially, the toilet operator has no coins,thus, the people in the queue have to reorganize so that whenever someone wants to pay with a $10$-crown coin, the operator has at least one $5$-crown coin available from previous customers.

The issue is that some of the people in the queue are unwilling to give up their spot. Determine in how many ways can the people willing to change their position rearrange themselves in the queue so that the operator always has change available. The positions of those unwilling cannot change (they cannot be moved to a later but also to an earlier spot in the rearranged queue).Furthermore, among those willing to change the position, the relative order of those with the same coin must be preserved.

# Standard Input

The input contains several test cases. Each test case consists of one line containing a non-empty string of parentheses and dots of length $n\leq 1,000$. A dot indicates a person willing to change their position in the queue, an opening parenthesis indicates a person unwilling to change the position who has a $5$-crown coin, and a closing parenthesis indicates a person unwilling to change the position who has a $10$-crown coin.You may assume that n is even and that the string contains at most $\frac{n}{2}$ opening parentheses and at most $\frac{n}{2}$ closing ones.

# Standard Output

For each test case, compute the number of ways the queue can be rearranged so that the conditions described in the statement of the problem are satisfied. Since this number may be too large, you are only required to print a single line containing one integer equal to the last $6$ digits (in the decimal representation) of the number.

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
<tr><td>....
.(..
)...
.....)......................</td><td>2
1
0
68484</td></tr></table>


# Constraints



# Note



# Source


