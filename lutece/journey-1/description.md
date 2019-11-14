
# Content

In Tomb-sweeping Festival, Yangsir and her friends planned to have a journey in a park. The park has N attractions which form a circle and only between adjacent attractions there is a road, so there are $N$ roads in total. On the way to the park, Yangsir and her friends lost their way. After several twists and turns, they arrived at the park but they still didn't know which attraction they are on now. 

![title](/source/lutece/journey-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTc2LzIwMTQwODI3MjEzMjA3NjU5MjMuanBn.jpg)

Looking at the park's map, Yangsir wanted to know that: if they set attraction $X$ as starting point, what is the minimum time they needed to pass all N attractions at least once? They don't need to go back to the starting attraction and the time spend on attractions are ignored.

We number the $N$ attractions from $1$ to $N$ clockwise, and the $i\_{th}$ road is the road between $i\_{th}$ and $i+1\_{th}$ attraction, except that the $N\_{th}$ road is the road between $N$ and $1$. The $N$ roads are all undirected.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 10$) indicating the number of test cases.

For each test case, the first line is only one integer $N$ ($3 \leq N \leq 1000$), representing the number of attractions in the park. In the second line there are $N$ positive integers separated by one space representing the time needed to pass through the $i\_{th}$ road. All the integers above are within $1,000,000$.

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output $N$ integers separated by one space which are the minimum time needed if they start from $1\_{st}$ attraction, $2\_{nd}$ attraction,..., $N\_{th}$ attraction.

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
5
4 6 5 3 7</td><td>Case #1: 18 19 19 20 18</td></tr></table>


# Constraints



# Note



# Source


