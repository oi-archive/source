
# Content

Deep in the Carribean, there is an island even stranger than the Monkey Island, dwelled by Horatio Torquemada Marley. Not only it has a rectangular shape, but is also divided into an $n\times m$ grid. Each grid field has a certain height. Unfortunately, the sea level started to raise and in year $i$, the level is $i$ meters. Another strange feature of the island is that it is made of sponge, and the water can freely flow through it. Thus, a grid field whose height is at most the current sea level is considered flooded.Adjacent unflooded fields (i.e., sharing common edge) create unflooded areas. Sailors are interested in the number of unflooded areas in a given year.

An example of a $4\times 5$ island is given below. Numbers denote the heights of respective fields in meters.Unflooded fields are darker; there are two unflooded areas in the first year and three areas in the second year.

![.*](/source/lutece/islands/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjAzLzIwMTQwMjA0MjM0NDI5NTgwMS5wbmc=.png)

# Standard Input

Multiple Test Cases

The input contains several test cases. The first line of the input contains a positive integer $Z\leq 20$,denoting the number of test cases. Then $Z$ test cases follow, each conforming to the format described in section Single Instance Input. For each test case, your program has to write an output conforming to the format described in section Single Instance Output.

Single Instance Input

The first line contains two numbers $n$ and $m$ separated by a single space, the dimensions of the island, where $1\leq n,m\leq 1000$. Next $n$ lines contain $m$ integers from the range $[1, 10^9]$ separated by single spaces, denoting the heights of the respective fields. Next line contains an integer $T$ ($1\leq T\leq 10^5$). The last line contains $T$ integers $t\_j$ , separated by single spaces, such that $0\leq t\_1\leq t\_2\leq\cdots\leq t\_T\leq 10^9$

# Standard Output

Single Instance Output

Your program should output a single line consisting of $T$ numbers $r\_j$ , where $r\_j$ is the number of unflooded areas in year $t\_j$ . **After every number ,you must output a single space!**

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
4 5
1 2 3 3 1
1 3 2 2 1
2 1 3 4 3
1 2 2 2 2
5
1 2 3 4 5</td><td>2 3 1 0 0</td></tr></table>


# Constraints



# Note



# Source


