
# Content

as we all know, ZhangYu(Octopus vulgaris) brother has a very famous speech - "Keep some distance from me".
ZhangYu brother is so rich that everyone want to contact he, and scfkcf is one of them.
One day , ZhangYu brother agreed with scfkcf to contact him if scfkcf could beat him.
There are $n$ digits(lets give them indices from $1$ to $n$ and name them $a_1, a_2 ... a_N$) and some queries.

for each query:
1.  ZhangYu brother choose an index $x$ from $1$ to $n$.
2.  For all indices $y$ ( $y$ < $x$) calculate the difference $b_y = a_x - a_y$.
3.  Then ZhangYu brother calculate $B_1$ ，the  sum of all by which are greater than $0$ , and scfkcf calculate $B_2$ , the sum of all by which are less than $0$.

if $B_1 > |B_2|$ , ZhangYu brother won and did not agree with scfkcf to contact him;
else if $B_1$ is equals to $|B_2|$ , ZhangYu brother would ignore the result;
else if $B_1$ < $|B_2|$ , ZhangYu brother lost and agreed with scfkcf to contact him.

# Standard Input

The first line contains two integers $n$, $m$ $(1 \le n,m \le 100000)$ denoting the number of digits and number of queries. The second line contains $n$ digits (without spaces) $a_1, a_2, ..., a_n$.$(0 \le a_i \le 9)$
Each of next $m$ lines contains single integer $x$ $(1 \le x \le n)$ denoting the index for current query.

# Standard Output

For each of $m$ queries print **"Keep some distance from me"** if ZhangYu won, else print **"Next time"** if ZhangYu brother ignored the result, else print **"I agree"** if ZhangYu brother lost in a line - answer of the query.

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
<tr><td>10 3
0324152397
1
4
7</td><td>Next time
Keep some distance from me
I agree</td></tr></table>


# Constraints



# Note

It's better to use "scanf" instead of "cin" in your code.

# Source


