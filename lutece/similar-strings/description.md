
# Content

We call two strings $S[1\cdots n]$ and $T[1\cdots n]$ similar if and only if:
1. They have the same length $n$.
2. For any pair of index $i$ and $j$, if $S\_i=S\_j$,then $T\_i=T\_j$.If $S\_i\neq S\_j$, then $T\_i\neq T\_j$ ($\neq$ means not equal to).

For example:
1. $S=$`AABBC` and $T=$`ZZYYK` are similar.
2. $S=$`AABBC` and $T=$`ZZYY` are not similar. (different length)
3. $S=$`AABBC` and $T=$`ZXYYK` are not similar. ($S\_1=S\_2$,$T\_1\neq T\_2$).

Now, give you two strings, please tell me whether they are similar.

# Standard Input

The first line of input is a number $T$,indicating the number of test case.For each test case,there are two lines,string $S$ and string $T$.Each string only contains upper-case.English letters,at least $1$ letter,at most $10^5$ letters.

# Standard Output

For each test case if $S$ and $T$ are similar output `YES`, otherwise output `NO`.

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
<tr><td>3
AABBC
ZZYYK
AABBC
ZZYY
AABBC
ZXYYK</td><td>YES
NO
NO</td></tr></table>


# Constraints



# Note



# Source


