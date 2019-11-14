
# Description

<div class="content">给定一颗树，树中每个结点有一个邮递员，每个邮递员要沿着唯一的路径走向capital(1号结点)，每到一个城市他可以有两种选择：
1.继续走到下个城市
2.让这个城市的邮递员替他出发。
每个邮递员出发需要一个准备时间W[I]，他们的速度是V[I]，表示走一公里需要多少分钟。
现在要你求出每个城市的邮递员到capital的最少时间(不一定是他自己到capital，可以是别人帮他）

N&lt;=100000

3 ≤  N ≤  100 000 
0 ≤  Si≤ 10^9
 
1 ≤  Vi≤ 10^9
 
The length of each road will not exceed 10 000 
For 20% of the tests, N ≤  2 500 
For 50% of the tests, each town will have at most 2 adjacent roads (i.e., the graph of 
roads will be a line) </div>

# Input

<div class="content">N
以下N-1行A,B,C三个数表示A,B之间有一条长为C的边。
再N行每行两数Wi,Vi
输出有一行N-1个数表示如题所述。
</div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
1 2 20 <br/>
2 3 12 <br/>
2 4 1 <br/>
4 5 3 <br/>
26 9 <br/>
1 10 <br/>
500 2 <br/>
2 30 </span></div>

# Sample Output

<div class="content"><span class="sampledata">206 321 542 328 </span></div>

# Hint

<div class="content"><p><img border="0" src="/source/bzoj/1767/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE3NjcuanBn.jpg"/> <br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

