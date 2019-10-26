
# Content

![title](/source/lutece/gathering/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTExOC8yMDE1MDUxNjE2MzI0NTI2MzczLmpwZw==.jpg)

The citizens of Fictitia have had enough! The city keeps getting bigger and bigger, and all the more boring. Fictitia consists of horizontal and vertical streets only. The distance between each pair of neighboring parallel streets is always the same; we take this as the unit distance. Surely some variation could not hurt?

In order to draw more support and make their unhappiness known to the municipality, a group of citizens has agreed to gather at an intersection of the city to protest. The question is: which intersection? Since there is not much difference between them, the idea was raised to select an intersection $(x^∗,y^∗)$ that minimizes the total distance everyone has to travel. Since everyone lives close to an intersection, the individual distance travelled by someone who lives at $(x,y)$ is given by $|x−x^∗|+|y−y^∗|$.

However, this could present a problem for the people who live far away, since they might have trouble getting there in time. Therefore it was decided that the intersection should be at most a certain distance $d$ away from everyone. Given that restriction, can you help them identify an intersection that minimizes the total distance everyone has to travel?

# Standard Input

The input consists of:

>#####one line with one integer n $(2≤n≤100000)$, the number of citizens;
>#####n lines each with two integers x and y $(0≤x,y≤10^9)$, the coordinates of each citizen’s house;
>#####one line with one integer d $(0≤d≤2⋅10^9)$, the maximum distance that each citizen should have to travel.

It is possible for multiple citizens to live at the same intersection.

# Standard Output

Output one line with a single integer: the smallest possible total distance that all citizens need to travel. If there is no intersection that everyone lives within a distance d of, output “impossible” instead.

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
3 1
4 1
5 9
2 6
5 3
10</td><td>18</td></tr><tr><td>5
3 1
4 1
5 9
2 6
5 3
5</td><td>20</td></tr><tr><td>5
3 1
4 1
5 9
2 6
5 3
4</td><td>impossible</td></tr></table>


# Constraints



# Note



# Source


