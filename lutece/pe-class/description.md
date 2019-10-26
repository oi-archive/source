
# Content

The dwarven kingdom and the giant countries classmates have PE class together. 

The students' height from $1$ cm to $N$ cm,everyone's height is different from other's.

There are $N$ students in total, and there are $M$ pairs of relationship, such as $(i, j)$ said the student's height stand at position $i$ is less than the one stand at position $j$.
Can you find each position of the height of students?

# Standard Input

The first line of input is the number of test case. 

The first line of each test case contains two integers, $N$ ($1 \leq N \leq 200$) and $M$ ($0 \leq M \leq 40,000$).
 
The next $M$ line each contain two integers $a$ and $b$, indicating the student's height stand at 
position $a$ must be less than the one stand at position $b$. ($1 \leq a, b \leq N$) 

There is a blank line before each test case.

# Standard Output

For each test case output one line the students' heights from position $1$ to position $N$.
 
If there are several solutions exist, you should output the one with the smallest height for label $1$, 
then with the smallest height for label $2$, then with the smallest height for label $3$ and so on... 

If no solution exists, output one line,just a number $-1$.

Output a blank line after each test case.

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
<tr><td>4

4 2
1 2
2 1

4 1
2 1

4 1
3 2

3 1
1 1</td><td>-1

2 1 3 4

1 3 2 4

-1</td></tr></table>


# Constraints



# Note



# Source


