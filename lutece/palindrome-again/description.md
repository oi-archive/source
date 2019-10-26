
# Content

Palindrome really has many many properties which fascinated us a lot and arouse many interests.

Do you remember that last summer, the problem about longest palindrome in the inteval?

Too easy? Maybe you are tired of solving problem about palindrome on one string.

Here is your another challenge.

There are two strings, $A$ and $B$, and an integer $d$.

And you are to count the number of triples $(i,j,k)$. that satisfies
$A.substr(i,k)=B.substr(j,k)$, $1\leq i\leq strlen(A)$, $1\leq j\leq strlen(B)$, $A.substr(i,k)$ is a palindrome, $k$ is the length of the substring, $k\geq d$

A substring of a string $T$ is defined as:

$T.substr(i, k)=T\_iT\_{i+1}\cdots T\_{i+k-1}$, $1\leq i\leq i+k-1\leq |T|$.

# Standard Input

The input file contains several cases, end by `EOF`. For each cases, the first line contains one integer $d$, followed by two lines containing strings $A$ and $B$, respectively.

$1 \leq strlen(A), strlen(B) \leq 50000$

$1 \leq d \leq min\\{strlen(A), strlen(B)\\}$

Characters of $A$ and $B$ are all lowercase letters.

# Standard Output

For each case, output an integer indicates the number of the triples $(i,j,k)$.

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
aba
aba
1
icpc
cicpc
2
myon
usagi</td><td>6
9
0</td></tr></table>


# Constraints



# Note

In the first sample , the $6$ triples are

$1,1,1$

$1,3,1$

$2,2,1$

$3,1,1$

$3,3,1$

$1,1,3$

respectively.

# Source


