
# Content

![title](/source/lutece/kawashiro-nitori-s-cucumber-detector/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTQyLzIwMTQwODI1MjM0MDQ5OTY0MTQuanBn.jpg)

As any other Kappa（河童）, Kawashiro Nitori loves cucumbers. So she invented a great cucumber detector to detect the cucumbers underground within the range of R. (You mean the cucumbers don't grow undergrond? In Gensoukyou, never be tied to common sense.) And detector divides the cucumbers into $9$ levels, the level $9$ is the best, and level $1$ is the worst. Specially, level $0$ means there's no cucumber at ths position.

In this problem, let's assume there's $N$ cucumbers grow in a line and their position are labeled from $1$ to $N$. Given all the information about the cucumbers, can you tell Nitori the best cucumber among the detector's range at some particular position? See more information at the sample.

# Standard Input

There is only one integer $T$ in the first line.

Then $T$ parts follow, each begins with a line with $3$ integers $N, M, R$, ($6\leq N\leq 20000$, $0\leq M\leq N$, $0\leq R\leq N$) indicating the number of cucumbers, the number of the position to be detected and the working range of the detector. And the next line would be $N$ integers, the $i\_{th}$ integer $a\_i$ means the level of $i\_{th}$ cucumber is $a\_i$. And the final line of the part would be $M$ integers, showing the position to be detected.

# Standard Output

For each part, output a line with $M$ numbers, which shows the best cucumber that could be detected at this position.

**There is a blank after each number.**

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
6 6 1
2 0 0 0 0 4
1 2 3 4 5 6</td><td>2 2 0 0 4 4</td></tr></table>


# Constraints



# Note

**Since so many test cases here, an algorithm with time complexity $O(N\times R)$ will not get Accepted.**

# Source


