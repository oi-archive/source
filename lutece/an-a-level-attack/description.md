
# Content

Magic world does exist. Magic world has wars. Magic world has heroes in wars. Magic world has a hero named zplinti1.

Today zplinti1 gets a new mission. He needs to reach the enemy’s base, which is located somewhere in the Nekoneko City. He has to be as quickly as possible for a military attack.

Now zplinti1 has arrived outside Nekoneko, but he still has to find a way to the enemy base. On the map of the Nekoneko, there are n places, and some of them are connected by undirected roads. Zplinti1 decides to choose a starting position, and move along those roads to reach the enemy base.

Unfortunately, just after zplinti1 calculates all the roads’ lengths, a bad news comes. The enemy has set a special magic at one of the places in the city, which will send anyone stepping on instantly to another place. But no magic is perfect, this magic can only be effective for $K$ times. Zplinti1 wonders the shortest time to finish his mission, or declares it as impossible.

The enemy might set magic at their own place, just at the door of the base. Zplinti1 considers his mission completed only when he is able to pass through that door.

# Standard Input

The first line of input contains a number $T$($T\leq 30$), indicating the number of test cases. 

For each case, there are two numbers $n$ and $m$ which is the number of places and roads in Nekoneko($2\leq n\leq 100000, 0\leq m \leq 200000$). Then $m$ lines follow, each with three integers $u$, $v$, and $w$. indicating there is a road between place $u$ and place $v$, which takes zplinti1 $w$ minutes to go($0\leq u,v< n,0< w \leq 100000$).

After that, five numbers are given, they are $s$,$e$,$p\_1$,$p\_2$ and $K$($0\leq s,e,p\_1,p\_2 < n$,$s\neq e,p\_1\neq p\_2,0< K\leq 100000$). Zplinti1 will first step into place $s$ in the city, and the enemy’s base is at place $e$. The enemy set magic at place $p\_1$, which will send someone instantly to place $p\_2$. The magic will be effective to send a person $K$ times.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output a number which is the shortest time for zplinti1 to reach his goal. If it is impossible, output `-1`.

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
<tr><td>4
4 4
0 1 10
1 2 10
2 3 10
0 3 20
0 3 2 1 10
4 3
0 1 10
1 2 10
2 3 10
0 3 2 1 10
4 2
0 1 10
2 3 20
0 3 1 2 10
4 0
0 3 1 2 10</td><td>Case #1: 20
Case #2: 130
Case #3: 30
Case #4: -1</td></tr></table>


# Constraints



# Note



# Source


