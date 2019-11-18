
# Content

The disease is spreading quickly, and the government has requested a map of infected regions. They would like to see what certain regions would look like, worst-case scenario, given some series of events. There are four stages of infection that the feds are interested in.

#####Stage A
The infection has not yet reached this zone. It is still possible for such zones to advance in infection stage due to an infection event.
#####Stage B
This zone is in the early stages of infection. There are reports of erratic behavior in individual citizens, quarantines are starting, and the municipal authorities still have things under control.
#####Stage C
This zone is dealing with mobs of zombies in a few areas. Quarantines are occurring on the scale of towns and small cities. The infection is contained to the zone but growing out of control.
#####Stage D
This zone has lost control of its borders. It is only a matter of time before the infection spreads to neighboring zones.
An infection event is anything that causes a zone to advance towards a higher stage of infection. This is usually the result of a quarantine breach, virus mutation, or biological terrorism. When an infection event occurs in a zone, it will, worst-cast scenario, cause the zone to advance in stage. A zone in stage D cannot advance in stage any further and will, worst-case scenario, result in an outbreak for each additional infection event it experiences. When an outbreak occurs, all neighboring zones experience an additional infection event. An outbreak can cause a chain reaction of outbreaks, but an outbreak can only cause a maximum of one outbreak in each zone.

Zones marked with an `X` character are impassible and unpopulated areas that cannot become infected. An adjacent zone is one zone above, below, to the left, or to the right on the grid of zones. During an outbreak, the infection cannot spread diagonally.

You will receive a grid of zones with their starting stages and a sequence of infection events with the coordinates of the zones in which they occur. Each infection event should be processed before calculating the result of the next infection event.

# Standard Input

The first line of input will contain the number of test cases, $N (1 \leq N \leq 50)$. Each test case will begin with a line giving the width, $W (1 \leq W \leq 100)$ and height, $H (1 \leq H \leq 100)$ of the grid, followed by the grid itself. Each zone in the grid will be marked by the stage that the zone is currently in, or the character $X$ if the zone is impassable.

Following the grid will be a line with the number of infection events $I (0 \leq I \leq 1000)$. I lines will follow each giving an $X$ and $Y$ coordinate of a zone. Each line represents an infection event that occurs on the $X$_th column (the left most column being $X = 0$) and the Yth row (the top row being $Y = 0$).

# Standard Output

Your output should show each grid with its states if the worst-case scenario occurs.

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
<tr><td>2
3 4
AAA
AXA
XAA
AAA
5
1 2
2 2
1 2
1 2
1 2
7 6
AAAAAAA
AAAAADA
AAXAAAA
AAAXDAA
AAXXAAB
AAXXACD
10
6 4
4 4
4 4
6 3
4 3
6 4
6 2
6 4
6 4
6 4</td><td>AAA
AXA
XDC
ABA
AAAAAAA
AAAAADA
AAXACBC
AAAXDDD
AAXXDDD
AAXXDDD</td></tr></table>


# Constraints



# Note



# Source


