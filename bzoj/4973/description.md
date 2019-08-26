
# Description

<div class="content"><div>在比特世界，A国正与B国爆发着战争！B国有n个城市，编号依次为1到n。这些城市之间通过m条双向道路连接，其</div>
<div>中第i条道路连接着u_i,v_i这两个城市。任意两个城市之间可能有多条道路，也有可能从1号点出发不能到达所有</div>
<div>城市。对于第i个城市，占领这座城市则需要在这里聚集a_i个特种兵，而在这里空降1个特种兵的代价为b_i。对于</div>
<div>第i条道路，占领这条道路需要在道路两端点的城市累计聚集c_i个特种兵，即：假如一条边连接着1号和2号城市，</div>
<div>而c=9，那么你可以在1号城市聚集3个特种兵，在2号城市聚集6个特种兵。A国的目标是占领B国所有的城市（不需</div>
<div>要占领所有道路），对于占领过的城市和道路，即使从这里撤兵，它也将永远属于A国，A国不需要派兵一直驻守。</div>
<div>请写一个程序，帮助A国以最小的总代价占领B国所有的城市。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n&lt;=100000,0&lt;=m&lt;=200000)，表示城市数和道路数。</div>
<div>接下来n行，每行两个正整数a_i,b_i(1&lt;=a_i,b_i&lt;=10000)，分别表示每个城市的相关参数。</div>
<div>接下来m行，每行三个正整数u_i,v_i,c_i(1&lt;=u_i,v_i&lt;=n,u_i!=v_i,1&lt;=c_i&lt;=10000)</div>
<div>分别表示每条双向道路的相关参数。</div></div>

# Output

<div class="content"><div>输出一行一个整数，即占领B国所有城市的最小总代价。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
10 5<br/>
20 10<br/>
10 3<br/>
1 2 22<br/>
2 3 200</span></div>

# Sample Output

<div class="content"><span class="sampledata">140<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

