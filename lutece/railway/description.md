
# Content

There are some locations in a park, and some of them are connected by roads. The park manger needs to build some railways along the roads, and he would like to arrange tourist routes to each circuit. If a railway belongs to more than one tourist routes, there might be clash on it, and if a railway belongs to none tourist route, it doesn't need to build. 

Now we know the plan, and can you tell us how many railways are no need to build and how many railways where clash might happen.

# Standard Input

The Input consists of multiple test cases. The first line of each test case contains two integers, $n$ ($0 < n\leq 10000$), $m$ ($0\leq m\leq 100000$), which are the number of locations and the number of the railways. The next m lines, each line contains two integers, $u$, $v$ ($0\leq u, v < n$), which means the manger plans to build a railway on the road between $u$ and $v$. 

You can assume that there is no loop and no multiple edges. 

The last test case is followed by two zeros on a single line, which means the end of the input.

# Standard Output

Output the number of railways that are no need to build, and the number of railways where clash might happen. Please follow the format as the sample.

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
<tr><td>8 10 
0 1 
1 2 
2 3 
3 0 
3 4 
4 5 
5 6 
6 7 
7 4 
5 7 
0 0</td><td>1 5</td></tr></table>


# Constraints



# Note



# Source


