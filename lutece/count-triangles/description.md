
# Content

In a class, kennethsnow is very sleepy. To avoid falling asllep, he starts to doodle and finally gets this:

![title](/source/lutece/count-triangles/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzIyLzIwMTQwNDEwMTQyMjEwMDE1MTQuanBn.jpg)

Now kennethsnow is very curious about how many triangles in the picture above. If he can't calculate excatly, he will fall asleep. Your task is write a program to help him solve this problem.

# Standard Input

The first line of the input contains one integer $T$($1\leq T\leq 10000$).

Following $T$ lines, every line only contains one integers $N$($1\leq N\leq 100000000$), indicates the length of the greatest triangle in the kennethsnow's picture.(In the picture of the description, the $n$ is equal to $5$)

# Standard Output

For each test case, output one line. First, output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, output the number of triangles in the picture for each test case. Since the answer may be very large, you just have to output the answer mod $20110108$.

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
<tr><td>5
1
2
3
4
5</td><td>Case #1: 1
Case #2: 5
Case #3: 13
Case #4: 27
Case #5: 48</td></tr></table>


# Constraints



# Note

You may use these equations:
1. If $A$ is divided by $B$, $\frac{A}{B}\rm\ mod\ K = \frac{A\rm\ mod\ (B\times K)}{B}$;
2. $(A+B)\rm\ mod\ K = A\rm\ mod\ K + B\rm\ mod\ K$
3. $(A\times B)\rm\ mod\ K = ((A\rm\ mod\ K)\times (B\rm\ mod\ K))\rm\ mod\ K$

# Source


