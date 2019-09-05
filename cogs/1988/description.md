# 题目描述


<article class="span9">
                <header class="page-header">
<h2 class="text-right">
PG <small>NOI2015 HA省队胡扯-第三场</small> 
</h2>
</header>
<h4>
背景
</h4>
<p>
LDN不知道为什么特别喜欢PG，也许是某种原因吧……
</p>
<p>
有一天，他发明了一个游戏“PG图”。
</p>
<h4>
描述
</h4>
<p>
给定一个有向图，每条边都有一个权值。
</p>
<p>
每次你可以选择一个节点<img alt="u" src="http://latex.codecogs.com/gif.latex?u"/>和一个整数<img alt="d" src="http://latex.codecogs.com/gif.latex?d"/>，把所有以<img alt="u" src="http://latex.codecogs.com/gif.latex?u"/>为终点的边的权值减小<img alt="d" src="http://latex.codecogs.com/gif.latex?d"/>，把所有以<img alt="u" src="http://latex.codecogs.com/gif.latex?u"/>为起点的边的权值加上<img alt="d" src="http://latex.codecogs.com/gif.latex?d"/>。最后要让所有边的权值的最小值为正且尽量大。
</p>
<h4>
输入格式
</h4>
<p>
输入包含若干组数据。
</p>
<p>
每组数据第一行为两个整数<img alt="n" src="http://latex.codecogs.com/gif.latex?n"/>和<img alt="m" src="http://latex.codecogs.com/gif.latex?m"/><img alt="(n\leq500,m\leq2700)" src="http://latex.codecogs.com/gif.latex?%28n%5Cleq500%2Cm%5Cleq2700%29"/>，表示点和边的个数。
</p>
<p>
以下<img alt="m" src="http://latex.codecogs.com/gif.latex?m"/>行，每行包括<img alt="3" src="http://latex.codecogs.com/gif.latex?3"/>个整数<img alt="u,v,w" src="http://latex.codecogs.com/gif.latex?u%2Cv%2Cw"/>，表示<img alt="u\rightarrow v" src="http://latex.codecogs.com/gif.latex?u%5Crightarrow%20v"/>有一条边权为<img alt="w" src="http://latex.codecogs.com/gif.latex?w"/>的边。<img alt="(1\leq u,v\leq n, -10000\leq w\leq 10000)" src="http://latex.codecogs.com/gif.latex?%281%5Cleq%20u%2Cv%5Cleq%20n%2C%20-10000%5Cleq%20w%5Cleq%2010000%29"/> 
</p>
<h4>
输出格式
</h4>
<p>
对于每组数据，输出边权最小值的最大值；
</p>
<p>
如果无法让所有边权都大于<img alt="0" src="http://latex.codecogs.com/gif.latex?0"/>，输出“<img alt="No\ Solution" src="http://latex.codecogs.com/gif.latex?No%5C%20Solution"/>”；
</p>
<p>
如果边权最小值可以无限大，输出“<img alt="Infinite" src="http://latex.codecogs.com/gif.latex?Infinite"/>”。
</p>
<h4>
样例输入
</h4>
<pre>2 1 <span style="font-family:sans-serif,&#34;">1 2 10 </span><span style="font-family:sans-serif,&#34;">2 1 </span><span style="font-family:sans-serif,&#34;">1 2 -10 </span><span style="font-family:sans-serif,&#34;">3 3 </span><span style="font-family:sans-serif,&#34;">1 2 4 </span><span style="font-family:sans-serif,&#34;">2 3 2 </span><span style="font-family:sans-serif,&#34;">3 1 5 </span><span style="font-family:sans-serif,&#34;">4 5 </span><span style="font-family:sans-serif,&#34;">2 3 4 </span><span style="font-family:sans-serif,&#34;">4 2 5 </span><span style="font-family:sans-serif,&#34;">3 4 2 </span><span style="font-family:sans-serif,&#34;">3 1 0 </span><span style="font-family:sans-serif,&#34;">1 2 -1</span></pre>
<h4>
样例输出
</h4>
<pre>Infinite <span style="font-family:sans-serif,&#34;">Infinite </span><span style="font-family:sans-serif,&#34;">3 </span><span style="font-family:sans-serif,&#34;">1</span></pre>
<h4>
数据范围与约定
</h4>
<ul>
<li>
对于<img alt="30\%" src="http://latex.codecogs.com/gif.latex?30%5C%25"/>的数据:<img alt="2\leq n\leq 10,1\leq m\leq 100" src="http://latex.codecogs.com/gif.latex?2%5Cleq%20n%5Cleq%2010%2C1%5Cleq%20m%5Cleq%20100"/> 
</li>
<li>
对于<img alt="60\%" src="http://latex.codecogs.com/gif.latex?60%5C%25"/>的数据:<img alt="2\leq n\leq 100,1\leq m\leq1000" src="http://latex.codecogs.com/gif.latex?2%5Cleq%20n%5Cleq%20100%2C1%5Cleq%20m%5Cleq1000"/> 
</li>
<li>
对于<img alt="100\%" src="http://latex.codecogs.com/gif.latex?100%5C%25"/>的数据:<img alt="2\leq n\leq 500,1\leq m\leq2700" src="http://latex.codecogs.com/gif.latex?2%5Cleq%20n%5Cleq%20500%2C1%5Cleq%20m%5Cleq2700"/> 
</li>
</ul>
</article>
