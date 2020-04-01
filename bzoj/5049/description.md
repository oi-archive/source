
# Description

<div class="content"><div>小Q来到了一个随机的国度。这个国度由n座城市和m条双向道路构成。因为这个国度崇尚随机，因此m条边是用随机</div>
<div>选择两端点的方式生成的。充满好奇的小Q想在这里进行k次随机的旅行，每次的起点和终点也是随机选择的。在每</div>
<div>次出发之前，他会使用导航系统计算两点间最少需要经过几条道路。请写一个程序，帮助小Q计算两点间的最短路</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含3个正整数n,m,k(2&lt;=n&lt;=100000,1&lt;=m&lt;=300000,1&lt;=k&lt;=10000)，分别表示点数、边数和询问数。</div>
<div>接下来m行，每行两个正整数u_i,v_i(1&lt;=u_i,v_i&lt;=n)，表示一条双向道路。输入数据保证不会有重边和自环。</div>
<div>接下来k行，每行两个正整数u_i,v_i(1&lt;=u_i,v_i&lt;=n,u_i!-v_i)，表示一次询问。</div>
<div>输入数据保证随机生成，且除了样例之外均满足n=100000,m=300000。</div>
<div>本题共3组数据。</div>
<div></div></div>

# Output

<div class="content"><div>输出k行，每行一个整数，即最少经过的边数，若无解输出-1。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 5 5<br/>
1 2<br/>
2 3<br/>
1 3<br/>
1 4<br/>
4 5<br/>
1 3<br/>
4 2<br/>
3 5<br/>
5 1<br/>
4 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
3<br/>
2<br/>
-1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

