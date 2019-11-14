
# Content

A new hotel has been built in a city where the citizens believe that the number $13$ brings bad luck. The hotel has $n$ rooms which are numbered from $1$ to $n$ inclusive. One of the main properties of a room is its unlucky value which depends on the room number. Only number whose decimal forms contain the substring `13` will be considered to be unlucky numbers. For example, $13$, $132$, $1313$, $9130$ are unlucky numbers, but $1$, $3$, $31$, $103$, $123123$ are not. The unlucky value of a room is the square of the room number if the room number is unlucky, and zero otherwise. 

A hotel's unlucky value equals the sum of the unlucky value of all its rooms. Help the manager to calculate the unlucky value of this hotel.

# Standard Input

The first line contains an integer $T$ ($T\leq 100$) indicating the number of test cases. $T$ lines follows, each line contains an integer $k$ ($1\leq k\leq 100$) indicating that this hotel has $10^k$ (the $k\_{th} power of $10$) rooms.

# Standard Output

For each test case, print the case number and the answer mod $100003$ in a single line where the answer is the unlucky value of this hotel. Follow the format of the sample output please.

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
1 
2 
3</td><td>Case 1: 0 
Case 2: 169 
Case 3: 49582</td></tr></table>


# Constraints



# Note



# Source


