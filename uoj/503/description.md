# 题目描述

<p>比太郎的房间是一个直角边长度为$N$的等腰直角三角形。以直角定点为原点，两条直角边分别为$x,y$轴建立坐标系，$(x,y)(0 \leq x \leq N, 0 \leq y \leq N, x + y \leq N)$就表示比太郎房间中的一个点。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/503/saochu.webp" alt="比太郎的房间"/></p>
<p>一天，比太郎注意到他的房间里充满了灰尘。一开始，房间里有$M$片灰尘，其中第$i$片的坐标是$(X_i,Y_i)$。不同的灰尘可以重叠。</p>
<p>现在，比太郎打算用扫帚打扫房间。我们可以把扫帚看作房间里的一条线段，并把线段的长度称作扫帚的<strong>宽度</strong>。比太郎是一个井井有条的人，他只会按照以下两种方式打扫房间：</p>
<ul><li>比太郎把扫帚放在$y$轴上，使扫帚的一个端点落在原点。然后，他沿着$x$轴的方向水平移动扫帚，直到扫帚碰到房间的斜边为止，保持扫帚的一个端点在$x$轴上，并且与$y$轴平行。如果扫帚的宽度是$l$，原来位于$(x,y) (x &lt; N - l,y \leq l)$的灰尘将会被扫到$(N-l,y)$处。（$(N-l,y)$处可能有其它灰尘。）这被称作<strong>过程H</strong>。</li>
<li>比太郎把扫帚放在$x$轴上，使扫帚的一个端点落在原点。然后，他沿着$y$轴的方向竖直移动扫帚，直到扫帚碰到房间的斜边为止，保持扫帚的一个端点在$y$轴上，并且与$x$轴平行。如果扫帚的宽度是$l$，原来位于$(x,y) (x \leq l,y &lt; N - l)$的灰尘将会被扫到$(x,N - l)$处。（$(x,N-l)$处可能有其它灰尘。）这被称作<strong>过程V</strong>。</li>
</ul><p>比太郎的房间中依次发生了$Q$个事件。其中的第$j$个是以下四种中的一种：</p>
<ul><li>比太郎询问第$j$片灰尘的坐标</li>
<li>比太郎用宽度为$L_j$的扫帚进行过程H</li>
<li>比太郎用宽度为$L_j$的扫帚进行过程V</li>
<li>一片新的灰尘出现在了$(A_j,B_j)$处。如果原来有$c$片灰尘，新的灰尘的编号就是$c+1$</li>
</ul><p>给定$L_j$或$(A_j,B_j)$，请写一个程序回答比太郎对灰尘坐标的询问。</p>

# 输入格式


<p>第一行三个整数$N,M,Q$</p>
<p>接下来$M$行中的第$i$行为两个整数$(X_i,Y_i)$</p>
<p>接下来$Q$行每行表示一个操作，含有两个或三个整数。每行的第一个整数$T_j$表示操作类型：</p>
<ul><li>如果$T_j=1$，这一行还含有一个整数$P_j$。这表示比太郎想查询第$j$片灰尘的坐标。</li>
<li>如果$T_j=2$，这一行还含有一个整数$L_j$。这表示比太郎用一个宽度为$L_j$的扫帚进行过程H。</li>
<li>如果$T_j=3$，这一行还含有一个整数$L_j$。这表示比太郎用一个宽度为$L_j$的扫帚进行过程V。</li>
<li>如果$T_j=4$，这一行还含有两个整数$A_j,B_j$。这表示$(A_j,B_j)$处出现了一片新的灰尘。</li>
</ul>
# 输出格式


<p>对$T_j=1$的每个操作输出一行两个整数，表示比太郎查询的灰尘的$x,y$坐标。</p>

# 样例数据


<h4>input1</h4>
<pre><code>6 2 10
1 1
4 0
4 2 3
3 3
1 1
4 1 2
2 3
2 0
1 4
3 2
1 3
1 2</code></pre>
<h4>output1</h4>
<pre><code>1 3
3 2
3 3
6 0</code></pre>
<h4>样例解释1</h4>
<ul><li>一开始，第一片灰尘落在$(1,1)$，第二片落在$(4,0)$，参照图$1$。</li>
<li>在第一个事件中，第三片灰尘出现在$(2,3)$，参照图$2$。</li>
<li>在第二个事件中，比太郎用宽度为$3$的扫帚进行过程V。第一片灰尘被移动到了$(1,3)$，参照图$3$。</li>
<li>在第三个事件中，比太郎计算第一片灰尘的坐标$(1,3)$。</li>
<li>在第四个事件中，第四片灰尘出现在了$(1,2)$处，参照图$4$。</li>
<li>在第五个事件中，比太郎用宽度为$3$的扫帚进行过程H。第一片灰尘的坐标现在是$(3,3)$，第三片灰尘的坐标现在是$(3,3)$，第四片灰尘的坐标现在是$(3,2)$，参照图$5$。</li>
<li>在第六个事件中，比太郎用宽度为$0$的扫帚进行过程H。第二片灰尘被移到了$(6,0)$，参照图$6$。</li>
<li>在第七个事件中，比太郎计算第$4$片灰尘的坐标$(3,2)$。</li>
<li>在第八个事件中，比太郎使用宽度为$2$的扫帚进行操作V。没有灰尘被移动，参照图$7$。</li>
<li>在第九个事件中，比太郎计算第三片灰尘的坐标$(3,3)$。</li>
<li>在第十个事件中，比太郎计算第二片灰尘的坐标$(6,0)$。</li>
</ul><p><a href="https://sm.ms/image/SsW67DAuG8wdtTk"><img src="/source/uoj/503/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDMvMjMvU3NXNjdEQXVHOHdkdFRrLnBuZw==.png" alt="SsW67DAuG8wdtTk.png"/></a></p>
<p><a href="https://sm.ms/image/JmKNY4qynpFMoXT"><img src="/source/uoj/503/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDMvMjMvSm1LTlk0cXlucEZNb1hULnBuZw==.png" alt="JmKNY4qynpFMoXT.png"/></a></p>
<h4>input2</h4>
<pre><code>9 4 8
2 3
3 1
1 6
4 3
2 6
1 3
2 2
1 4
2 3
1 2
2 4
1 1</code></pre>
<h4>output2</h4>
<pre><code>3 6
4 3
7 1
6 3</code></pre>
<p>这组测试数据符合子任务$1,2,4,5$的要求。</p>
<h4>input3</h4>
<pre><code>8 1 8
1 5
4 4 1
2 6
1 2
2 3
4 2 2
2 5
1 1
1 3</code></pre>
<h4>output3</h4>
<pre><code>4 1
3 5
3 2</code></pre>
<p>这组测试数据符合子任务$1,2,5$的要求。</p>

# 限制与约定


<ul><li>$1 \leq N \leq 1 000 000 000$</li>
<li>$1 \leq M \leq 500 000$</li>
<li>$1 \leq Q \leq 1 000 000$</li>
<li>$0 \leq X_i \leq N (1 \leq i \leq M)$</li>
<li>$0 \leq Y_i \leq N (1 \leq i \leq M)$</li>
<li>$X_i + Y_i \leq N (1 \leq i \leq M)$</li>
<li>第$P_j$片灰尘存在</li>
<li>$0 \leq L_j \leq N-1 (1 \leq j \leq Q)$</li>
<li>$0 \leq A_j \leq N (1 \leq j \leq Q)$</li>
<li>$0 \leq B_j \leq N (1 \leq j \leq Q)$</li>
<li>$A_j + B_j \leq N (1 \leq j \leq Q)$</li>
<li>至少有一个$T_j=1$的操作。</li>
</ul>
# 子任务


<ol><li>($1$ 分) $M \leq 2000, Q \leq 5000$</li>
<li>($10$ 分) $T_j = 1,2,4$</li>
<li>($11$ 分) $T_j = 1,2,3, X_j \leq X_{j+1}, Y_j \geq Y_{j+1} (1 \leq j \leq M-1)$</li>
<li>($53$ 分) $T_j = 1,2,3$</li>
<li>($25$ 分) 没有额外的限制</li>
</ol><p>时间限制:$\texttt{10S}$。</p>
<p>空间限制:$\texttt{1GB}$。</p>
<p>祝大家一遍 AC，求不虐萌萌哒测评机！</p>
