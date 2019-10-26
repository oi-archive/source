
# Content

MAX AIR CITY is an illusory city.Matters every day in this bustling city is happening. MAX AIR CITY is made up of $n$ regions (conveniently numbered from $1$ to $n$) but unfortunately is connected by unidirectional roads, however, to overcome the shortages, there can be multiple roads between any two regions.

Today, YAN leaves Tian all of a sudden because Tian has made a serious mistake. Tian is eager to find YAN. 

He has to go to $L$ different regions to collect information in order to make a decision how should he take the next step.

Now, Tian has a list which indicates the regions he will reach. But he is not sure the order of visiting. 

So once he has got to a region, he has to return home to analyse the next place to go to. Be careful that it takes time 
$t[i]$ to prepare his leaving(such as have a meal,the call of nature). In other words, to travel from region $i$ to any other adjacent city $j$, preparation would cost him $t[i]$ of time to , and then time $w(i, j)$ on the road.

Tian wants to find YAN as soon as possible even any piece of message about her, so he wants to use the least time to collect information. Luckily ,you are a good programmer and he is eager to ask for your help to calculate the minimum time that it may take him to find his YAN.

# Standard Input

The first line of the input contains an integer $T$ indicating the number of cases.

Each case contains $M+3$ lines. The first line contains $4$ integers $N$ $M$ $S$ $L$ separated by blank. $N$ ($2\leq N\leq 50000$) 
is the number of regions. $M$ ($1\leq M\leq 500000$) is the number of roads. $S$ indicates which region Tian’s home is in. 

$L$ is number of regions that Tian has to reach. The second line is $L$ integers indicating the number of these regions. 

Then a line with $N$ integers indicating the time that must be cost to prepare $t[i]$ ($0\leq t[i]\leq 10^9$) .
 
The following $M$ lines each contains $3$ integers $u$ $v$ $w$ separated by a blank indicate that there is a road from $u$ to $v$, 
and it would cost time $w$. 

All data will fit in a $64$-bit integer.

# Standard Output

For each test case, output one line with an integer indicating the minimum time. Note that if Tian can’t 
visit all the regions or he can’t return home after any visiting, then output “Tumblerful” (without quotation).

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
3 4 1 2
2 3
5 5 5
1 2 3
2 3 5
3 1 7
1 3 4
2 1 1 1
2
2 3
1 2 3</td><td>51
Tumblerful</td></tr></table>


# Constraints



# Note

1. For the first case, Tian begins from his home at region $1$, spend $5$ minutes to prepare. Then spend $3$ minutes 
on the road from region $1$ to region $2$.Then he finished visiting and return ,spend $5$ minutes in region $2$ to prepare, 
via road $2\rightarrow 3$ get to region $3$ and spend $5$ minutes for preparation. Via road $3\rightarrow 1$ he return home. The next place 
is region $3$. So he started at region $1$ spending $5$ minutes to prepare and then via road $1\rightarrow 3\rightarrow 1$ to finish his work 
of collecting information. The total time is $(5)+3+(5)+5+(5)+7+(5)+4+(5)+7=51$,the number in the brackets indicate the time for preparation.
2. Huge input datas , scanf is recommended.

# Source


