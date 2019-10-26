
# Content

Astronomers often examine star maps where stars are represented by points on a plane and each star has Cartesian coordinates. Let the level of a star be an amount of the stars that are not higher and not to the right of the given star. Astronomers want to know the distribution of the levels of the stars. 

![.*](/source/lutece/stars/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjExLzIwMTQwMjA2MDAxMjQ1ODg4NC5qcGc=.jpg)

For example, look at the map shown on the figure above. Level of the star number 5 is equal to 3 (it's formed by three stars with a numbers $1$, $2$ and $4$). And the levels of the stars numbered by $2$ and $4$ are $1$. At this map there are only one star of the level $0$, two stars of the level $1$, one star of the level $2$, and one star of the level $3$. 

You are to write a program that will count the amounts of the stars of each level on a given map.

# Standard Input

The first line of the input file contains a number of stars $N$ ($1\leq N\leq 15000$). The following $N$ lines describe coordinates of stars (two integers $X$ and $Y$ per line separated by a space, $0\leq X,Y\leq 32000$). There can be only one star at one point of the plane. Stars are listed in ascending order of $Y$ coordinate. Stars with equal $Y$ coordinates are listed in ascending order of $X$ coordinate.

# Standard Output

The output should contain $N$ lines, one number per line. The first line contains amount of stars of the level $0$, the second does amount of stars of the level $1$ and so on, the last line contains amount of stars of the level $N-1$.

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
1 1
5 1
7 1
3 3
5 5</td><td>1
2
1
1
0</td></tr></table>


# Constraints



# Note

This problem has huge input data,use `scanf` instead of `cin` to read data to avoid time limit exceed.

The data used in this problem is unofficial data prepared by standy. So any mistake here does not imply mistake in the offcial judge data.

# Source


