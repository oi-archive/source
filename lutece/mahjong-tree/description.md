
# Content

An elder has a big family with N-1 descendants. If we treat their blood relationships as edges, their family is a tree and this elder is the root. One day, he gets N apples. And the weights of these apples are 1 2 3 … and n. The elder want to share these with every one in his family.

He share these apples with two rules:

1.	The apples’ weights that everyone’s small family(he and his descendants) shared are continuous.
2.	The apples’ weights that everyone’s son shares are continuous.

He want to know the number of methods he can share these apples.

# Standard Input

The first line of the input contains the number of test cases T.

For each case, The first line contains a integer  N (1≤N≤100000) 

Each of the following N−1 lines contains two integers a and b (1≤a,b≤N,a≠b), indicating that a is b’s parent or b is a’s.

The elder’s number is 1.

# Standard Output

For each test case, output “Case #x: ans”, in which x is the number of methods(Mod 1000000007).

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
2 1
3 1
4 3
5 3
6 2
7 4
8 7
9 3
8
2 1
3 1
4 3
5 1
6 4
7 5
8 4
</td><td>Case #1: 32
Case #2: 16
</td></tr></table>


# Constraints



# Note



# Source


