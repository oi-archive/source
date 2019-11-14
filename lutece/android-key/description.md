
# Content

Xixi has a smart phone with Symbian OS. She loves it for its convenience and massive software supplies. But recently, she could not help but notice that more and more people are using Android. Not only the staff at Google, but also her boyfriend and many other ACM team members are turning to Android users.

If you are already a user of Android, you must be familiar with its key lock system. The Android lock system uses a series of nine dots in a $3 \times 3$ square that you need to replicate a pre-set pattern to unlock the phone.

Starting from one dot in the $3 \times 3$ square, you can then move to the adjacent dot in four directions, up, down, left, and right. Sometimes you are on the edge or corner, your choices will be limited to $2$ or $3$ directions.

Another rule of setting the lock is that you cannot move to the dot that you have already visited. So $4-5-2-1$ is a valid lock, whereas $4-5-2-1-4$ is not.

Now xixi has found poemqiong’s new cell, and it is an Android phone. Knowing the length of peomqiong’s phone lock is $K$, she wonders how many different lock patterns are there.

To make this problem a little more difficult, we assume that the keyboard is $N\times M$ square, instead of $3\times 3$. An $N\times M$ square has $N$ columns and $M$ rows.

Now, given $N (1\leq N\leq 10$), $M$ ($1\leq M\leq 10$) and the length of the lock pattern $K$ ($0\leq K\leq 10$), can you write a program to help xixi figure out how many patterns are there?

# Standard Input

$N$, $M$, $K$

# Standard Output

The number of different patterns, noting that $4-5$ and $5-4$ are two different patterns.

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
<tr><td>2 2 3
3 3 2</td><td>8
24</td></tr></table>


# Constraints



# Note



# Source


