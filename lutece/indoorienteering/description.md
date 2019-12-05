
# Content

![title](/source/lutece/indoorienteering/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTEyMC8yMDE1MDUxNjE3MTQzOTI5NTc0LmpwZw==.jpg)

Lukáš really likes orienteering, a sport that requires locating control points in rough terrain. To entertain the NWERC participants Lukáš wants to organize an orienteering race. However, it would be too harsh for the participants to be outdoors in this cold Swedish November weather, so he decided to jump on the new trend of indoor races, and set the race inside the B building of Linköping University.

Lukáš has already decided on the locations of the control points. He has also decided on the exact length of the race, so the only thing remaining is to decide in which order the control points should be visited such that the length of the total race is as he wishes. Because this is not always possible, he asks you to write a program to help him.

Note from the organizer: the NWERC indoorienteering race for this year has been cancelled since we neglected to apply for an orienteering permit in time from the university administration. (We still need you to solve the problem so that we can organize it for next year.)

# Standard Input

The input consists of:

>#####one line with two integers n $(2≤n≤14)$ and L $(1≤L≤10^{15})$, the number of control points and the desired length of the race, respectively;
>#####n lines with n integers each. The jth integer on the ith line, dij, denotes the distance between control point i and j ($1≤ dij ≤L$ for $i≠j$, and $dii=0$). For all $1≤i,j,k≤N$ it is the case that $dij=dji$ and $dij≤dik+dkj$.

# Standard Output

Output one line with “possible” if it is possible to visit all control points once in some order and directly return to the first one such that the total distance is exactly L, and “impossible” otherwise.

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
<tr><td>4 10
0 3 2 1
3 0 1 3
2 1 0 2
1 3 2 0</td><td>possible</td></tr><tr><td>3 5
0 1 2
1 0 3
2 3 0</td><td>impossible</td></tr></table>


# Constraints



# Note



# Source


