
# Content

Pfctgeorge is totally a tall rich and handsome guy. He plans to build a huge water transmission network that covers the whole southwest China. To save the fund, there will be exactly one path between two cities.

Since the water every city provides and costs every day is different, he needs to transfer water from one particular city to another as much as possible in the next few days. However the pipes which connect the cities have a limited capacity for transmission. (Which means the water that transfer though the pipe should not exceed a particular amount) So he has to know the maximum water that the network can transfer in the next few days.

He thought it's a maximum flow problem, so he invites an expert in this field, Elfness (Also known as Xinhang senior sister) to help him figure it out.

Unlike Pfctgeorge, Elfness quickly finds that this problem is much easier than a normal maximum flow problem, and is willing to help Pfctgeorge.

"Oh well, this problem is not a tough one. We can ...''

Abruptly, Pfctgeorge's iPhone rings, and ... the ringtone is `Mo Di Da Biao Ke`.

"You can make that? Excellent! ''Pfctgeorge hangs up his iPhone, and turns to Elfness.

"Here's good news for you. A construction team told me that every pipe's capacity can be extended for one day. And the price for extending one unit capacity varies from day to day. ''

"Eh well, that's a good news for you, not me. Now it's rather like a minimum cost flow problem, right? But it's still not a tough one, let me have a think. ''

After a few seconds' thought, Elfness comes up with a simple solution.

"Ok, we can solve it like... ''

Abruptly, here comes `Mo Di Da Biao Ke` again.

"Seriously? You can build new pipes? Thank you very much. ''

"OK, my dear Elfness, we got more good news. Another construction team said they can build one or more pipes between any two cities and their pipes are exactly like the original ones except that they only work for one day. And the capacity of the new pipes is only one, but they can be extended, too. Of course, their price to build a single pipe also varies in days. ''

"You mean the new pipes can be extended too? Wow, things are getting more interesting. Give me a few minutes. ''

Elfness takes out his new ultrabook which is awarded in VK cup and does some basic calculation.

"I get it. The problem can be solved ...''

`Mo Di Da Biao Ke` again, but this time it's from Elfness's phone.

"As you see, I have to go out. But I know someone else who can also solve this; I'll recommend this guy for you. ''

And of course, that poor guy is YOU. Help Pfctgeorge solve his problem, and then the favorability about you from Elfness will raise a lot.

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

The first line of each test case is two integers $N$ ($1\leq N\leq 100000$) 
and $M$ ($1\leq M\leq 100000$), indicating the number of the city that the original network 
connects and the number of days when Pfctgeorge needs to know about the maximum water transmissions. 
Then next $N-1$ lines each describe a pipe that connects two cities. The format will be 
like $U$, $V$, $cap$ ($1\leq U$, $V\leq N$ and $0\leq cap<10000$), which means the $ids$ of the
two cities the pipe connects and the transmission limit of the pipe. As is said in description, 
the network that the cities and pipes form is a tree (an undirected acyclic graph).

Then next $M$ lines of the test case describe the information about the next few days. 
The format is like $S$, $T$, $K$, $A$, $B$. $S$ means the source of the water while $T$ means the sink. $K$ means the total budget in the day. $A$ means the cost for a construction team to build a new pipe and $B$ means the cost for a construction team to extend the capacity of a pipe.

I am glad to list the information of building a new pipe and extending the capacity.

1. Pfctgeorge can build a new pipe between any two cities, no matter they have been directly connected or not. Pfctgeorge can build more than one new pipe between any two cities.
2. The capacity of the pipe that was newly built is **`one`**.
3. Pfctgeorge can extend the capacity of any existed pipe including the newly built one and the original one.
4. Each time you extend the capacity of one pipe, the capacity of that pipe increases one.
5. The cost of building a new pipe is $A$ and the cost of extending a pipe is $B$.
6. You can take any constructions in any times and the only limit is to make sure the total costs not exceed the budget.
7. **`All the work that construction team does only lasts one single day`**.

# Standard Output

For every case, you should output `Case #t:` at first, without quotes. The $t$ is the case 
number starting from $1$.

Then for each day, output the maximum water Pfctgeorge can transfer from $S$ and $T$ with a
budget of $K$.

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
5 1
1 2 2
1 3 5
2 4 1
4 5 2
1 5 3 3 2
5 5
1 2 10
2 3 2
3 4 7
2 5 7
1 5 0 1 3
1 3 0 2 3
1 5 3 2 3
1 2 7 3 1
1 3 2 3 1</td><td>Case #1:
2
Case #2:
7
2
8
17
4</td></tr></table>


# Constraints



# Note



# Source


