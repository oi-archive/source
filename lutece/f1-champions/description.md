
# Content

Formula One championship consists of series of races called Grand Prix. After every race drivers receive points according to their final position. Only the top $10$ drivers receive points in the following order $25$, $18$, $15$, $12$, $10$, $8$, $6$, $4$, $2$, $1$. At the conclusion of the championship the driver with most points is the champion. If there is a tie, champion is the one with most wins (i.e. first places). If a tie still exists, it is chosen the one with most second places, and so on, until there are no more place to use for compare.

Last year another scoring system was proposed but rejected. In it the champion is the one with most wins. If there is tie, champion is the one with most points. If a tie still exists it is proceeded the same way as in the original scoring system, that is comparing number of second, third, forth, and so on, places.

You are given the result of all races during the season and you are to determine the champion according to both scoring systems. It is guaranteed, that both systems will produce unique champion.

# Standard Input

There are multi-cases. For each case the first line contain integer $t$ ($1\leq  t\leq  20$), where $t$ is the number of races. After that all races are described one by one. Every race description start with an integer $n$ ($1\leq  n \leq  50$) on a line of itself, where $n$ is the number of clasified drivers in the given race. After that n lines follow with the classification for the race, each containing the name of a driver. The names of drivers are given in order from the first to the last place. The name of the driver consists of lowercase and uppercase English letters and has length at most $50$ characters. Comparing of names should be case-sensetive.

# Standard Output

For each case. Your output should contain exactly two line. On the first line is the name of the champion according to the original rule, and on the second line the name of the champion according to the alternative rule.

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
3
Hamilton
Vettel
Webber
2
Webber
Vettel
2
Hamilton
Vettel
2
7
Prost
Surtees
Nakajima
Schumacher
Button
DeLaRosa
Buemi
8
Alonso
Prost
NinoFarina
JimClark
DeLaRosa
Nakajima
Patrese
Surtees</td><td>Vettel
Hamilton
Prost
Prost</td></tr></table>


# Constraints



# Note



# Source


