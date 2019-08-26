
# Description

<div class="content"><p>The government of Byteland has decided that it is time to connect their little country to the Internet, so that all citizens can participate in programming competitions and watch videos of cute cats. When it was time to build the network backbone of the country, they assigned the company Internet Optimists Inc. with connecting all the n computers of Byteland. The connections were made as direct links between pairs of computers in such a way that any pair of computers are connected by a sequence of links.</p>
<div>Byteland is not a rich country by any means, so to minimize costs the network topology was built in the form of a tree (i.e. there are exactly n-1 direct links between computers). Far too late, it was realised that this solution suffers from a serious drawback. If just a single link is broken, the computers of Byteland will be partitioned so that some computers cannot communicate with each other!</div>
<div>To improve the reliability of Byteland&#39;s network, it was decided that it should at least tolerate if a single link is broken. Your task is to help Internet Optimists Inc. to improve the network in a cheapest way. Given the network topology of Byteland (i.e. which n-1  pairs of computers are connected by direct links), find the minimum number of links that need to be added so that the network will still be connected if any single link is broken.</div>
<div>
<div>给定一颗树，求最少加多少条边使形成的图形任意删除一条变后都联通，边是无向的</div>
<div>输出最少加边数和任意一种加边方案。注意<span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">不能加已出现的边</span></div>
</div></div>

# Input

<div class="content"><p>The first line of input contains a positive integer n(N&gt;=3), the number of computers in Byteland. For simplicity, all computers are numbered from 1 to n. Each of the following n-1 lines contains a pair of integers a and b (1&lt;=a,b&lt;=n,a&lt;&gt;b) that describes a direct link between computers a and b.</p>
<div></div></div>

# Output

<div class="content"><p>In the first line of output your program should write an integer k, the minimal number of links that should be added to the network. In each of the following k lines your program should write a pair of integers a and b (1&lt;=a,b&lt;=N,a&lt;&gt;b)  that denote the numbers of computers that should be connected by a link. The links can be written in any order. If there is more than one solution, your program should output any one of them.</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 2<br/>
2 3<br/>
2 4<br/>
5 4<br/>
6 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 5<br/>
3 6<br/>
</span></div>

# Hint

<div class="content"><p></p><p> N&lt;=500 000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢fengchanghn提供译文及SPJ">鸣谢fengchanghn提供译文及SPJ</a></p></div>

