
# Content

Given a string $A$ and a substring $B$ of $A$. Please tell me the lexicographical order of $B$ among all the substrings of $A$. 

If B has multiple lexicographical orders, tell me the smallest one.

For example. A="abab". A has 10 substrings. They are:

>#####1. a
>#####2. a
>#####3. ab
>#####4. ab
>#####5. aba
>#####6. abab
>#####7. b
>#####8. b
>#####9. ba
>#####10. bab

If B="a", B ranks 1 and 2, so the smallest answer is 1. 

If B="ab", B ranks 3 and 4, so the smallest answer is 3.           

If B="bab", B ranks 10, so the answer is 10.

# Standard Input

The first line contains a string $A$. The length of $A$ is at least $1$ and at most $10^5$. It only contains lower-case letters ('a'-'z').

The second line contains a non-empty string $B$. It is guaranteed that $B$ is a substring of $A$.

# Standard Output

Output an integer representing the lexicographical order of B among all the substrings of $A$. 

If B has multiple lexicographical orders, tell me the smallest one.

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
<tr><td>abab
ab</td><td>3</td></tr></table>


# Constraints



# Note



# Source


