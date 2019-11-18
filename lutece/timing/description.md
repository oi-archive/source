
# Content

***NOTICE: The SPJ program is missing now, if you want submit this problem, please write a SPJ and contact the staff (muziriyun@gmail.com)***

A clash of galaxies is coming!

A galaxy ruled by the mysterious MdI is trying to annex our milky way, but the galactical government
has plans to turn things round.

Our intelligence agency has infiltrated the enemy’s headquarter and gained surprising intelligence.
The enemy is moving its units around according to a fixed scheme: for each fort a fraction of the
units is moved to other forts in each time unit (the time of the flight is negligible).

Now the government has fixed a time when to attack. Your order is to compute the weak points. But
as the enemy’s galaxy is far, far away it takes one time unit to fly there. Furthermore, we are also
certain that the MdI will recognize our target and immediately start all ships which can reach our
attacking point (via one link, regardless of its direction). The spy informed you that these strengths
are only statistical values, i.e. some sort of indicator as float.

# Standard Input

The first line of the input contains the number of test cases ($1\leq T\leq 10$). Each test case starts with
one line containing three integers stating the number of enemy forts $N$ ($1\leq N\leq 100$), the number
of links $l$ ($0\leq l\leq (N − 1)^2$) and the time from now when to attack $t$ ($0\leq t\leq 5000$). The second
line contains $N$ doubles $u_i$ ($0\leq u_i\leq 1000$) specifying the strength of the stationed troops at each
fort followed by $l$ lines containing the links. Each link is described by two integers $s_j$ ($0\leq s_j < N$),
$t_j$ ($0\leq t_j < N$) describing the source and the target of the link and one double $p_j$ ($0 < p_j\leq 1$), the
fraction of units transferred from $s_j$ to $t_j$ in each time unit.

# Standard Output

Print the lowest indicator of the enemy galaxy with an absolute or relative error less than $10^{−6}$

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
4 3 1
100 200 10 305
0 1 0.25
1 2 0.1
2 0 0.75
4 3 1
100 200 10 312
0 1 0.25
1 2 0.1
2 0 0.75
4 4 5
100 200 300 400
0 1 0.2
1 2 0.2
2 3 0.3
3 0 0.2</td><td>305.000000000
310.000000000
659.879000000</td></tr></table>


# Constraints



# Note

![Title](/source/lutece/timing/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjEvMjAxMzEyMjkwMDUzNTEzMjI0LnBuZw==.png)

*The statistical strengths of the first sample before and after the first time step.*

![Title](/source/lutece/timing/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjEvMjAxMzEyMjkwMDU0MDAwMDA1LnBuZw==.png)

*Strength of the forces to face at each fort. Note that links are used in both directions.*

# Source


