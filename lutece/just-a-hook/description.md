
# Content

In the game of DotA, Pudge’s meat hook is actually the most horrible thing for most of the heroes. The hook is made up of several consecutive metallic sticks which are of the same length.

Now Pudge wants to do some operations on the hook.

Let us number the consecutive metallic sticks of the hook from $1$ to $N$. For each operation, Pudge can change the consecutive metallic sticks, numbered from $X$ to $Y$, into cupreous sticks, silver sticks or golden sticks.

The total value of the hook is calculated as the sum of values of $N$ metallic sticks. More precisely, the value for each kind of stick is calculated as follows:

* For each `cupreous` stick, the value is $1$.
* For each `silver` stick, the value is $2$.
* For each `golden` stick, the value is $3$.

Pudge wants to know the total value of the hook after performing the operations.

You may consider the original hook is made up of cupreous sticks.

# Standard Input

The input consists of several test cases. The first line of the input is the number of the cases. There are no more than $10$ cases.

For each case, the first line contains an integer $N$, $1\leq N\leq 100,000$, which is the number of the sticks of Pudge’s meat hook and the second line contains an integer $Q$, $0\leq Q\leq 100,000$, which is the number of the operations.

Next $Q$ lines, each line contains three integers $X$, $Y$, $1\leq X\leq Y\leq N$, $Z$, $1\leq Z\leq 3$, which defines an operation: change the sticks numbered from $X$ to $Y$ into the metal kind $Z$, where $Z=1$ represents the `cupreous` kind, $Z=2$ represents the `silver` kind and $Z=3$ represents the `golden` kind.

# Standard Output

For each case, print a number in a line representing the total value of the hook after the operations. Use the format in the example.

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
10 2 
1 5 2
5 9 3</td><td>Case 1: The total value of the hook is 24.</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by standy. So any mistake here does not imply mistake in the offcial judge data.

# Source


