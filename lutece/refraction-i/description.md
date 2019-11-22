
# Content

Refraction is a common phenomena in our life. Now ,comes a problem. Give you a kind of liquid and its refractive index, you should calculate the focus of the light on the ground(Point $T$ in the picture below). 

To let the problem easier,we assume that the air's refractive index is always $1$. As the picture below,the light source is always in the air(the point $S$ in the picture). We assume the $Y$ coordinate of ground level is $0$.

![title](/source/lutece/refraction-i/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzk5LzIwMTQwODExMjM0OTM2MzAzNC5wbmc=.png)

# Standard Input

The first line of the data contains a number $T$($1\leq T\leq 500$), indicating the total number of test cases. Each test case consists of $2$ lines .The first line contains $4$ numer $x\_1,y\_1,x\_2,y\_2$, indicating the coordinate of the light and the coordinate of 
the direction respectively. The second line contains $2$ numbers $n$, $H$, indicating the refractive index of the liquid and the depth of the liquid.

# Standard Output

For each test case, write a single float numbers $x$ on a single line, indicating the $X$ coordinate of the focus,retain $3$ digits after the decimal point.

If there is not focus on the ground ,just output `Impossible` on a single line.

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
3 6 0 6
1.35 3
3 6 0 3
1.35 3
3 6 3 3
1.35 3</td><td>Impossible
-1.845
3.000</td></tr></table>


# Constraints



# Note



# Source


