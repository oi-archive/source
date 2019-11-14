
# Content

A friend of yours is working on an AI program to play backgammon, and she has a small problem. At the end of the game, each player's $15$ pieces are moved onto a set of $6$ board positions called points,
numbered $1$ through $6$. The pieces can be distributed in any manner across these points: all $15$ could be on point $3$; $5$ could be on point $6$, $2$ on point $5$, $3$ on point $4$ and $5$ on point $2$; etc. Your friend wants to store all these possible configurations (of which there are $15504$) into a linear array, but she needs a mapping from configuration to array location. It seems logical that the configuration with all $15$ pieces on point $1$ should correspond to array location $0$, and the configuration of all $15$ pieces on point $6$ should correspond to the last array location. It's the ones in between that are giving her problems.

That's why she has come to you.

You decide to specify a configuration by listing the number of pieces on each point, starting with point 6. For example, the two configurations described above could be represented by $(0,0,0,15,0,0)$ and $(5,2,3,0,5,0)$. Then you can order the configurations in lexicographic ordering, starting with $(0,0,0,0,0,15)$, then $(0,0,0,0,1,14)$; $(0,0,0,0,2,13)$; $\cdots$ ;$(0,0,0,0,14,1)$; $(0,0,0,0,15,0)$; $(0,0,0,1,0,14)$; $(0,0,0,1,1,13)$, etc., ending with $(15,0,0,0,0,0)$. Now all you need is a way to map these orderings to array indices. Literally, that's all you need, because that's what this problem is all about.

# Standard Input

Each test case will consist of one line, starting with a single character, either `m` or `u`. If it is an `m` it will be followed by a configuration and you must determine what array index it gets mapped to. If it is a `u` then it will be followed by an integer array index $i$, $0 \leq i < 15504$, and you must determine what configuration gets mapped to it. A line containing the single character `e` will end input.

# Standard Output

For each test case, output the requested answer either an array index or a configuration. Follow the format in the examples below.

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
<tr><td>m 0 0 0 0 0 15
u 15503
e</td><td>Case 1: 0
Case 2: 15 0 0 0 0 0</td></tr></table>


# Constraints



# Note



# Source


