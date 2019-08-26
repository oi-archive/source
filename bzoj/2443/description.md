
# Description

<div class="content"><div>奶牛们遭到了进攻！在他们的共和国里，有N(1 &lt;= N &lt;=50,000)个城市，由M(1 &lt;= M &lt;= 100,000)条无向的道路连</div>
<div>接城市A_i和B_i(1 &lt;= A_i &lt;= N;1 &lt;= B_i &lt;= N;A_i != B_i; 不会有重复的道路出现)。然而，整个共和国不一定</div>
<div>是连通的——有一些城市无法到达另外一些城市。入侵者想得到共和国的地图。(入侵者很傻，因此，他们的绘制</div>
<div>地图的方法是去访问每一条边，T_T)。奶牛想要折磨一下入侵者，使得他们尽可能难地完成地图绘制。因此，奶牛</div>
<div>会破坏若干条道路。请你帮助奶牛找到一个道路的子集，使得每条边每个点的度数为奇数。或者输出不存在这样的</div>
<div>一个子集。(奶牛的图论学得真好.= =||)举个例子，考虑下面的共和国：</div>
<div>1---2</div>
<div>\ /</div>
<div>  3---4</div>
<div></div>
<div>如果我们保留道路1-3,2-3和3-4,破坏道路1-2,那么城市1,2,4都只有一条边相连，城市3有3条边相连：</div>
<div></div>
<div>1   2</div>
<div>\ /</div>
<div>  3---4</div></div>

# Input

<div class="content"><div>* 第一行：两个用空格隔开的整数：N和M</div>
<p></p>
<div>* 第二行到M+1行：第i+1行有两个空格隔开的整数A_i和</div></div>

# Output

<div class="content"><div>* 第一行： 一个整数表示需要保留的道路数量</div>
<div>* 第二到K+1行：每行一个数表示保留的道路的编号，范围是1...M。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2<br/>
2 3<br/>
3 1<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2<br/>
3<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold 鸣谢cghandy提供SPJ">Gold 鸣谢cghandy提供SPJ</a></p></div>

