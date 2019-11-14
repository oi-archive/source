
# Content

![title](/source/lutece/biking-duck/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTExMy8yMDE1MDUxNTIzNDk0MDcwNjY3LmpwZw==.jpg)

Gladstone Gander is walking through Duckburg and needs to get to his date with Daisy Duck as soon as possible. If he doesn’t get there in time, Donald might show up and take his place instead.

Duckburg has recently started providing a very eco-friendly way of public transport: bikes. At many bike stations throughout the city, one can pick up a free bike, ride it to another bike station, and drop it there. This gives Gladstone two ways of transportion: on foot or by bike. Biking is faster, of course, but he must pick up and leave the bikes at the designated stations. Gladstone can walk or bike between any two points in a straight line.

Gladstone possesses a map of the (rectangular) center of Duckburg. His current position is on this map and so is the meeting point with Daisy. The map also contains the locations of all bike stations within the boundaries of the map.

There can be way more bike stations though, that are not within the boundaries of the map. Considering his luck, you can assume that the moment Gladstone walks (or bikes) off the map, he encounters a bike station if that suits him well. The bike stations not on the map can be located anywhere outside the map, they do not have to lie on integer coordinates.

That leaves Gladstone with the task of figuring out which route to take. Can you help him out? Given the map and his infinite amount of luck, what is the fastest time to his date with Daisy?

# Standard Input

The input consists of:

>#####one line with two integers vwalk and vbike $(1≤vwalk<vbike≤1000)$, the speeds of walking and of biking;
>#####one line with four integers x1,y1,x2 and y2 $(−10^6≤x1<x2≤10^6; −10^6≤y1<y2≤10^6)$, the bounding coordinates of the map of the center of Duckburg;
>#####one line with two integers xG and yG, Gladstone’s position;
>#####one line with two integers xD and yD, Daisy’s position;
>#####one line with one integer n $(0≤n≤1000)$, the number of known bike stations;
>#####n lines with two integers xstation and ystation each, the coordinates of the known bike stations.

All coordinates are on the map of the center, i.e. $x1≤x≤x2$ and $y1≤y≤y2$.

# Standard Output

Output one line with the shortest possible time for Gladstone to get to Daisy. Your answer should have an absolute or relative error of at most $10^{−6}$.

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
<tr><td>1 8
0 0 10 10
5 1
5 9
3
5 8
2 2
9 6</td><td>3.000000000</td></tr><tr><td>5 100
0 -100000 100000 0
5 -30000
40000 -5
0</td><td>501.9987496</td></tr></table>


# Constraints



# Note



# Source


