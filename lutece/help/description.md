
# Content

Standy is a clever boy, and loves solving puzzles very much. Recently, he was troubled by a difficult problem.

![title](/source/lutece/help/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzY3LzIwMTQwNDExMTcxOTM5MjQ4MzUucG5n.png)

What’s the numbers in the $5\_{th}$ line? You may find that it is just Yanghui Triangle, so the $5\_{th}$ line should be `1 4 6 4 1`. But Standy didn’t know Yanghui Triangle, and he found that two adjacent cells in a row and the cell above them and the cell below them form a **diamond**. What’s more, the upper and lower cells’ product is **one** larger than the left and right cells’ product. The picture below shows that $2 \times 5 = 3 \times 3 + 1$. So the first and last number in each row is $1$, and others can be determined by the `Diamond Rule`.

![title](/source/lutece/help/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzY3LzIwMTQwNDExMTcyMDQwMjc0MzYucG5n.png)

Standy wants to know the $j\_{th}$ number in the $i\_{th}$ row, and asks you for help.

# Standard Input

The first line of input contains an integer $T$ ($T\leq 100$), which is the number of test cases that follow.

Then $T$ lines follow, each of them containing two integers $i$ and $j$ ($1\leq j\leq i\leq 10^9$)

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then output the $j\_{th}$ number in the $i\_{th}$ row.

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
4 2
5 3
6 4</td><td>Case #1: 3
Case #2: 5
Case #3: 7</td></tr></table>


# Constraints



# Note

As the answer may be very large, you should use `long long` instead of `int`. If you want to know more details, please refer to FAQ of CDOJ.

# Source


