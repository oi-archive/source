
# Content

Every cow's dream is to become the most popular cow in the herd. In a herd of $N (1 \leq N \leq 10,000)$ cows, you are given up to $M (1 \leq M \leq 50,000)$ ordered pairs of the form $(A, B)$ that tell you that cow $A$ thinks that cow $B$ is popular. Since popularity is transitive, if $A$ thinks $B$ is popular and $B$ thinks $C$ is popular, then $A$ will also think that $C$ is popular, even if this is not explicitly specified by an ordered pair in the input. Your task is to compute the number of cows that are considered popular by every other cow.

# Standard Input

1. Line $1$: Two space-separated integers, $N$ and $M$ 

2. Lines $2 \cdots 1+M$: Two space-separated numbers $A$ and $B$, meaning that $A$ thinks $B$ is popular.

Process to end of file.

# Standard Output

For each case:

Output A single integer on a single line that is the number of cows who are considered popular by every other cow.

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
<tr><td>3 3
1 2
2 1
2 3</td><td>1</td></tr></table>


# Constraints



# Note

Cow $3$ is the only cow of high popularity.

# Source


