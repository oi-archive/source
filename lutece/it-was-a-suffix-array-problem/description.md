
# Content

Peter has ever thought about a difficult string problem and he actually did consider nobody can solve it. Could you?

Given a string $S$ and two type of questions. 
1. Given another string $subS$, decide whether or not $subS$ is a sub-string of $S$, if so, tell me the lexicographic rank of $subS$ among all the distinct sub-strings of $S$.
2. There are $M$ sub-questions following. In each sub-question, given an integer $k$, tell me a sub-string of $S$ whose lexicographic rank is exactly $k$.  You are allowed to just tell me the starting position of that sub-string and the length of it. If more than two sub-strings rank $k$, output the one who has the smallest starting position.

# Standard Input

There are $T$ cases $(1=<T<=5)$ on each test. The first line contains an integer $T$.

In each case, obey the following rules.

The first line contains a string $S$ and the second line contains a string $subS$. Both of their length are in the range $[1,2 \times 10^5]$. 

Next line contains an integer $M$ $(M\in [0,2 \times 10^5])$, representing the number sub-questions of in question 2.

Each of the following M lines contains one integer $k$, meaning the lexicographic rank of the destination substring of $S$.

# Standard Output

In each case, obey the following rules.

The first line should contain an integer $k$, representing the lexicographic rank of $subS$ among all the distinct sub-strings of $S$ if $subS$ is a sub-string of $S$, otherwise, output -1.

Output M lines. Each of line should contain two integer $P$ and $L$, meaning the starting position of the destination sub-string and the length of it. It is guaranteed that you can always find out the sub-string.  If more than two sub-strings are found, output the one who has the smallest starting position.

Do not output anything between two cases or after the last case.

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
abcabc
bc
5
1
2
3
4
5</td><td>8
0 1
0 2
0 3
0 4
0 5</td></tr><tr><td>1
ababababab
aba
5
1
2
3
4
5</td><td>3
0 1
0 2
0 3
0 4
0 5</td></tr><tr><td>3
lfancltrcm
lfa
5
14
4
21
20
14
wftvgaipre
wftvgaipre
5
41
1
50
25
36
abjsdeaaxe
god
5
21
37
24
18
6</td><td>27
4 6
2 4
1 6
1 5
4 6
55
3 3
5 1
0 5
6 4
2 6
-1
1 6
2 2
1 9
1 3
0 3</td></tr></table>


# Constraints



# Note

Let us consider the first sample.

We can make a lexicographic order graph of all the distinct sub-strings of "abcabc".

1. a
2. ab
3. abc
4. abca
5. abcab
6. abcabc
7. b
8. bc
9. bca
10. bcab
11. bcabc
12. c
13. ca
14. cab
15. cabc

Therefore, the lexicographic rank of string "bc" is 8.

String "a" ranks 1, but there are two "a" in "abcabc". The smallest starting position is 0.

# Source


