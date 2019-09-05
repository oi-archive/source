# 题目描述


<!--<article class="span9">-->
 <header class="page-header">
<h2 class="text-center">
LDN <small>NOI2015 HA省队胡扯-第三场</small> 
</h2>
</header>
<h4>
背景
</h4>
<p>
小A和小B都是足球迷，他们酷爱西甲联赛。
</p>
<p>
但是小A是皇马的忠实球迷，小B是巴萨的铁杆粉丝，于是经常发生争执……
</p>
<p>
这个赛季，皇马在某场重要比赛中，萎了……
</p>
<p>
小A很伤心，但他不服输，找到了LDN大爷，想知道皇马是否还存在翻盘的机会。
</p>
<p>
Orz LDN，他掐指一算，就得出了答案。
</p>
<p>
zkk正好路过，想调戏一下LDN，于是将问题加强，问每个球队是否存在翻盘的机会。
</p>
<p>
LDN掐指一算，晕了……于是他向你求助。
</p>
<h4>
描述
</h4>
<p>
有<img alt="n" src="http://latex.codecogs.com/gif.latex?n"/>支球队进行比赛。每场比赛恰好有一支队伍获胜（不存在平局）。获得冠军的条件是：获胜场数在所有球队中最多（允许并列）。
</p>
<p>
现在给出每支队伍目前胜利的场数和失败的场数，以及每两个球队之间还要比赛的次数。
</p>
<p>
请你确定所有可能获得冠军的球队。（多组数据）
</p>
<h4>
输入格式
</h4>
<p>
第一行一个整数<img alt="T" src="http://latex.codecogs.com/gif.latex?T"/>，表示数据组数。
</p>
<p>
每组数据第一行一个整数<img alt="n(1\leq n\leq 25)" src="http://latex.codecogs.com/gif.latex?n%281%5Cleq%20n%5Cleq%2025%29"/>，表示队伍数量。
</p>
<p>
第二行为<img alt="2n" src="http://latex.codecogs.com/gif.latex?2n"/>个整数<img alt="w_1,d_1,w_2,d_2,...,w_n,d_n(1\leq w_i,d_i \leq100)" src="http://latex.codecogs.com/gif.latex?w_1%2Cd_1%2Cw_2%2Cd_2%2C...%2Cw_n%2Cd_n%281%5Cleq%20w_i%2Cd_i%20%5Cleq100%29"/>，其中<img alt="w_i" src="http://latex.codecogs.com/gif.latex?w_i"/>和<img alt="d_i" src="http://latex.codecogs.com/gif.latex?d_i"/>分别表示队伍<img alt="i" src="http://latex.codecogs.com/gif.latex?i"/>已经获胜的场数和失败的场数。
</p>
<p>
第三行为<img alt="n^2" src="http://latex.codecogs.com/gif.latex?n%5E2"/>个整数<img alt="a_{1,1},a_{1,2},a_{1,3},...,a_{2,1},...,a_{n,n}" src="http://latex.codecogs.com/gif.latex?a_%7B1%2C1%7D%2Ca_%7B1%2C2%7D%2Ca_%7B1%2C3%7D%2C...%2Ca_%7B2%2C1%7D%2C...%2Ca_%7Bn%2Cn%7D"/>，其中<img alt="a_{i,j}" src="http://latex.codecogs.com/gif.latex?a_%7Bi%2Cj%7D"/>表示队伍<img alt="i" src="http://latex.codecogs.com/gif.latex?i"/>和队伍<img alt="j" src="http://latex.codecogs.com/gif.latex?j"/>之间还要打的比赛场数。输入保证<img alt="a_{i,j}=a_{j,i}" src="http://latex.codecogs.com/gif.latex?a_%7Bi%2Cj%7D%3Da_%7Bj%2Ci%7D"/>，并且<img alt="a_{i,i}=0" src="http://latex.codecogs.com/gif.latex?a_%7Bi%2Ci%7D%3D0"/>。
</p>
<h4>
输出格式
</h4>
<p>
对于每组数据，输出一行，按照从小到大顺序给出所有可能获得冠军的队伍编号。
</p>
<h4>
样例输入
</h4>
<pre>1 </pre>
<pre><span style="font-family:sans-serif,&#34;">3 </span></pre>
<pre><span style="font-family:sans-serif,&#34;">1 0 2 0 3 0 </span></pre>
<pre><span style="font-family:sans-serif,&#34;">0 3 2 3 0 1 2 1 0</span></pre>
<h4>
样例输出
</h4>
<pre>1 2 3
</pre>
<h4>
数据范围与约定
</h4>
<ul>
<li>
对于<img alt="30\%" src="http://latex.codecogs.com/gif.latex?30%5C%25"/>的数据:<img alt="1 \leq n \leq 5" src="http://latex.codecogs.com/gif.latex?1%20%5Cleq%20n%20%5Cleq%205"/> 
</li>
<li>
对于<img alt="60\%" src="http://latex.codecogs.com/gif.latex?60%5C%25"/>的数据:<img alt="1\leq n\leq 10" src="http://latex.codecogs.com/gif.latex?1%5Cleq%20n%5Cleq%2010"/> 
</li>
<li>
对于<img alt="100\%" src="http://latex.codecogs.com/gif.latex?100%5C%25"/>的数据:<img alt="1\leq n \leq 25" src="http://latex.codecogs.com/gif.latex?1%5Cleq%20n%20%5Cleq%2025"/> 
</li>
</ul>
<!--</article>-->
