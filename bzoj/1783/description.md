
# Description

<div class="content">Farmer John has invented a new way of feeding his cows. He lays out
N (1 &lt;= N &lt;= 700,000) hay bales conveniently numbered 1..N in a
long line in the barn. Hay bale i has weight W_i (1 &lt;= W_i &lt;=
2,000,000,000). A sequence of six weights might look something like:
        17 5 9 10 3 8 
A pair of cows named Bessie and Dessie walks down this line after
examining all the haybales to learn their weights. Bessie is the
first chooser. They take turns picking haybales to eat as they walk
(once a haybale is skipped, they cannot return to it). For instance,
if cows Bessie and Dessie go down the line, a possible scenario is:

* Bessie picks the weight 17 haybale
* Dessie skips the weight 5 haybale and picks the weight 9 haybale
* Bessie picks the weight 10 haybale
* Dessie skips the weight 3 haybale and picks the weight 8 haybale
Diagrammatically:

Bessie   |      |
        17 5 9 10 3 8 
Dessie       |      |
This scenario only shows a single skipped bale; either cow can skip
as many as she pleases when it&#39;s her turn.Each cow wishes to maximize the total weight of 
hay she herself consumes (and each knows that the other cow has this goal).Furthermore, a cow 
will choose to eat the first bale of hay thatmaximimizes her total weight consumed.
Given a sequence of hay weights, determine the amount of hay that
a pair of cows will eat as they go down the line of hay.


一排数，两个人轮流取数，保证取的位置递增，每个人要使自己取的数的和尽量大，求两个人都在最优策略下取的和各是多少。

</div>

# Input

<div class="content">* Line 1: A single integer: N

* Lines 2..N+1: Line i+1 contains a single integer: W_i

</div>

# Output

<div class="content">* Line 1: Two space-separated integers, the total weight of hay
        consumed by Bessie and Dessie respectively
</div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
17<br/>
5<br/>
9<br/>
10<br/>
3<br/>
8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">27 17<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

