
# Content

Being the head judge of a programming contest is no small thing. As with everything good in life, there is that inevitably long list of things that need to be done before it can happen. Fortunately for Ruben, he has recently acquired a machine that at the push of a button, can spawn a small minion for him to do part of his work. He has also hired an assistant to remind him to activate the machine.

![title](/source/lutece/ruben-spawns/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzE1LzIwMTQwOTAxMTgyNTE2NTM5MzEucG5n.png)

There is one caveat with minions. If you have too many of them, they might get lost. So, simply put, fewer is better. After all, someone has to keep track of those minions. Each minion spawned from the machine can work a set amount of units, and then they are "spent" (there exists a recycling machine, but it is hidden in a deep, dark forest somewhere).

The machine itself creates a given number of minions whose work capacities are normally distributed with both parameters unknown. The number of minions the machine can spawn in a given time interval is Poisson distributed with intensity also unknown.What we are interested in is knowing the minimum amount of times Ruben would have to spawn a minion to be sure that all the work gets done. You are given a list of how many work units each of the N minions can work for. The machine will break down completely after having spawned $N$ minions. The machine lets you choose which minion you want spawn next from the list of possible minions, but you can only spawn each once. All minions are unique in their own ways,but they might still have the same work capacity.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each of the following $T$ cases then consist of two lines. The first line has two integers: $W$,the number of work units Ruben needs completed, and $M$, the number of minions the machine can spawn. Then follows a line with $M$ integers $C\_i$,representing how many work units each minion can complete.

$0 < T \le 50$

$0 < W \le 10000$

$0 < M \le 100$

$0 < Ci \le 100$

# Standard Output

Output the minimum number of minions needed to complete the workload $W$, or output `no rest for Ruben` (without the quotes). Please note that you need a capital $r$ in Ruben's name.

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
4 5
1 2 4 100 3
10 10
1 1 1 1 1 1 1 1 1 1
20 10
9 1 1 1 1 1 1 1 1 9
100 5
81 1 2 1 4</td><td>1
10
4
no rest for Ruben</td></tr></table>


# Constraints



# Note



# Source


