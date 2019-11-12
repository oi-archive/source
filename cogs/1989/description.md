# 题目描述


<article class="span9">
                <header class="page-header">
<h2 class="text-right">
BD <small>NOI2015 HA省队胡扯-第三场</small> 
</h2>
</header>
<h4>
背景
</h4>
<p>
背景太麻烦了……（此处省略一万字）
</p>
<h4>
描述
</h4>
<p>
给一个<img alt="N * M * P" src="http://latex.codecogs.com/gif.latex?N%20*%20M%20*%20P"/>的三维网格，每个格子里有一盏灯。
</p>
<p>
每次均匀随机选择一个格子<img alt="A" src="http://latex.codecogs.com/gif.latex?A"/>和格子<img alt="B" src="http://latex.codecogs.com/gif.latex?B"/>（二者可以相同），然后把以<img alt="A,B" src="http://latex.codecogs.com/gif.latex?A%2CB"/>为顶点的长方体内所有灯的状态改变（开变关，关变开）。具体来说，如果<img alt="A(x_1,y_1,z_1),B(x_2,y_2,z_2)" src="http://latex.codecogs.com/gif.latex?A%28x_1%2Cy_1%2Cz_1%29%2CB%28x_2%2Cy_2%2Cz_2%29"/>，则状态改变的灯的坐标满足<img alt="min(x_1,x_2)\leq x\leq max(x_1,x_2)\wedge min(y_1,y_2)\leq y \leq max(y_1,y_2)\wedge min(z_1,z_2)\leq z\leq max(z_1,z_2)" src="http://latex.codecogs.com/gif.latex?min%28x_1%2Cx_2%29%5Cleq%20x%5Cleq%20max%28x_1%2Cx_2%29%5Cwedge%20min%28y_1%2Cy_2%29%5Cleq%20y%20%5Cleq%20max%28y_1%2Cy_2%29%5Cwedge%20min%28z_1%2Cz_2%29%5Cleq%20z%5Cleq%20max%28z_1%2Cz_2%29"/>这个很重要，大家一定要看清楚！！！
</p>
<p>
一开始所有灯都是灭的，经过<img alt="K" src="http://latex.codecogs.com/gif.latex?K"/>次操作之后，平均情况下有多少灯是亮着的？
</p>
<h4>
输入格式
</h4>
<p>
第一行一个整数<img alt="T" src="http://latex.codecogs.com/gif.latex?T"/>，表示数据组数。
</p>
<p>
对于每组数据，输入仅一行，共四个整数<img alt="N,M,P,K" src="http://latex.codecogs.com/gif.latex?N%2CM%2CP%2CK"/>。
</p>
<h4>
输出格式
</h4>
<p>
对于每组数据，输出一个实数，表示期望值。（精确到<img alt="10^{-6}" src="http://latex.codecogs.com/gif.latex?10%5E%7B-6%7D"/>）
</p>
<h4>
样例输入
</h4>
<pre>2 <span style="font-family:sans-serif,&#34;">2 3 4 1 </span><span style="font-family:sans-serif,&#34;">2 3 4 2</span></pre>
<h4>
样例输出
</h4>
<pre>6.375000
9.097656
</pre>
<h4>
数据范围与约定
</h4>
<ul>
<li>
对于<img alt="10\%" src="http://latex.codecogs.com/gif.latex?10%5C%25"/>的数据：<img alt="K = 1" src="http://latex.codecogs.com/gif.latex?K%20%3D%201"/> 
</li>
<li>
对于另外<img alt="30\%" src="http://latex.codecogs.com/gif.latex?30%5C%25"/>的数据:<img alt="1\leq N,M,P\leq 10,K \leq 1000" src="http://latex.codecogs.com/gif.latex?1%5Cleq%20N%2CM%2CP%5Cleq%2010%2CK%20%5Cleq%201000"/> 
</li>
<li>
对于另外<img alt="30\%" src="http://latex.codecogs.com/gif.latex?30%5C%25"/>的数据:<img alt="T=1" src="http://latex.codecogs.com/gif.latex?T%3D1"/> 
</li>
<li>
对于<img alt="100\%" src="http://latex.codecogs.com/gif.latex?100%5C%25"/>的数据：<img alt="1\leq N,M,P\leq 100,K\leq10000" src="http://latex.codecogs.com/gif.latex?1%5Cleq%20N%2CM%2CP%5Cleq%20100%2CK%5Cleq10000"/> 
</li>
</ul>
</article>
