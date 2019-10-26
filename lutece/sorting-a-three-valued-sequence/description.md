
# Content

Sorting is one of the most frequently performed computational tasks. Consider the special sorting problem in which the records to be sorted have at most three different key values. This happens for instance when we sort medalists of a competition according to medal value, that is, gold medalists come first, followed by silver, and bronze medalists come last.

In this task the possible key values are the integers $1$, $2$ and $3$. The required sorting order is non-decreasing. However, sorting has to be accomplished by a sequence of exchange operations. An exchange operation, defined by two position numbers $p$ and $q$, exchanges the elements in positions $p$ and $q$.

You are given a sequence of key values. Write a program that computes the minimal number of exchange operations that are necessary to make the sequence sorted.

# Standard Input

Line $1$: $N$ ($1\leq N\leq 1000$), the number of records to be sorted

Lines $2-N+1$: A single integer from the set $\\{1, 2, 3\\}$

# Standard Output

A single line containing the number of exchanges required

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
<tr><td>9
2
2
1
3
3
3
2
3
1</td><td>4</td></tr></table>


# Constraints



# Note



# Source


