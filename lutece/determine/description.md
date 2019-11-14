
# Content

There is a strange pipe, which has two entrances, conveniently named the left entrance and the right entrance. You have some weighted balls, which are numbered from $1$ to $N$. Now, you want to push your balls into the strange pipe, ball $1$ first, and then ball $2$, $\cdots$ , and finally ball $N$. When you push a ball in through an entrance, it must heavier than the balls pushed in before through this entrance. You are clever enough to determine which ones you can and should push in, so could you tell me the maximum number of balls you can successfully push into the strange pipe?

![title](/source/lutece/determine/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzYzLzIwMTQwNDExMTM0NTQ0NzczMzIucG5n.png)

# Standard Input

The first line of the input is an integer $T$ ($T\leq 50$), which stands for the number of test cases you need to solve.

Every test case begins with an integer $N$ ($N\leq 1000$), the number of balls. And then $N$ integers follow, specify the weight of ball $1$ to ball $N$. Weight is nonnegative and less than $10^9$.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the answer. See sample for more details.

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
<tr><td>4
3
1 2 3
3
2 3 1
3
3 2 1
3
1 1 1</td><td>Case #1: 3
Case #2: 3
Case #3: 2
Case #4: 2</td></tr></table>


# Constraints



# Note

**You can choose to push a ball in or not even if you can push the ball in successfully.**

# Source


