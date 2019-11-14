
# Content

Alice has a piano which can plays nice music, but it's different from other pianos. It has two rows of keys, and the method of playing it is also quite special. When Alice plays piano, she has to put her two hands on the leftside of the two rows of keys respectively (without touching the leftmost keys of the two rows). And then her hands move on the keys from left to right one by one. Each time she can move one of her hands by one key, either on the above row or the below row. She has to keep the difference between the number of black keys and white keys she has already touched no more than $K$ to make sure the music is beautiful. When the music is end, her two hands should be both on the rightmost of the piano keyboard. Now Alice wants to know whether she can play nice music, given the description of the piano.

Suppose the number of keys of the two rows are both $N$. And two strings are given to describe the keyboard. `1` stands for black keys while `0` for white ones.

# Standard Input

There are multiple cases, end by EOF.

For each case, the first line contains two integers $N$($3 \leq N \leq 1000$) and $K$ ($0 \leq K \leq 1000$), with two `0`-`1` strings which are described above.

# Standard Output

If she can play the music, please output an answer string of length $2N$ which has the minimum lexicographic order. In the answer string, `1` represents move on the above row while `2` represents the below row. If she cannot, just output `Poor Alice`.

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
<tr><td>4 1
0011
0110

4 1
1100
1100</td><td>22121112
Poor Alice</td></tr></table>


# Constraints



# Note

Take the first sample for explaining:

Suppose Alice puts her left hand on the above row of keys, and right on the

below one, the answer string stands for the following process:
1. move right hand to the $1\_{st}$ key of the below row of keys.
2. move right hand to the $2\_{nd}$ key of the below row of keys.
3. move left hand to the $1\_{st}$ key of the above row of keys.
4. move right hand to the $3\_{rd}$ key of the below row of keys.
5. move left hand to the $2\_{nd}$ key of the above row of keys.
6. move left hand to the $3\_{rd}$ key of the above row of keys.
7. move left hand to the $4\_{th}$ key of the above row of keys.
8. move right hand to the $4\_{th}$ key of the below row of keys.

# Source


