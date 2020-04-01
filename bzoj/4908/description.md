
# Description

<div class="content"><div>你有n辆车，分别a1, a2, ..., an位置和n个加油站，分别在b1, b2, ... ,bn 。每个加油站只能支持一辆车的加</div>
<div>油，所以你要把这些车开到不同的加油站加油。一个车从x位置开到y位置的代价为 |x-y| ，问如何安排车辆，使</div>
<div>得代价之和最小。同时你有q个操作，每次操作会修改第i辆车的位置到x，你要回答每次修改操作之后最优安排方</div>
<div>案的总代价。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数n，接下来一行n个整数a1, a2, ...,an，接下来一行n个整数b1, b2,... ,bn。</div>
<div>接下来一行一个正整数q，表示操作的个数。</div>
<div>接下来q行，每行有两个整数i(1 ≤ i ≤ n)和x，表示将i这辆车开到x位置的操作。</div>
<div>1 ≤ n, q ≤ 5 * 10^4，所有的车和加油站的范围一直在0到10^9之间。</div></div>

# Output

<div class="content"><div>共q+1行，第一行表示一开始的最优代价。接下来q行，第i行表示操作i之后的最优代价。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 2<br/>
3 4<br/>
1<br/>
1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2<br/>
【样例解释】<br/>
一开始将第一辆车开到位置4，将第二辆车开到位置3，代价为 |4-1|+|3-2|=4。<br/>
修改后第一辆车的位置变成3，代价为 |3-3|+|4-2|=2。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

