
# Content

A regular expression, regex or regexp (sometimes called a rational expression) is, in theoretical computer science and formal language theory, a sequence of characters that define a search pattern. Usually this pattern is then used by string searching algorithms for "find" or "find and replace" operations on strings.

"`?`" : The question mark indicates zero or one occurrences of the preceding element. For example, $\textbf{colou?r}$ matches both "color" and "colour".

Given a string $S$ consist of lower-case English letters only and some string $q$, your task is to count the numbers of substring of the $S$ which matches $q$.

# Standard Input

The first line of the input contains a string $S$($1\leq |S| \leq 1000$)

The next line contains number of query $Q$ ($Q\leq 100$).

Each question contains a string $q$ ($1\leq |q| \leq 20$).

It's guaranteed that no two question marks appear continuously and no question mark appears at the beginning.

# Standard Output

For each query print the corresponding answer in a single line.

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
<tr><td>abcaaaa
3
a?a
a?b
c?a?</td><td>8
2
7</td></tr></table>


# Constraints



# Note



# Source


