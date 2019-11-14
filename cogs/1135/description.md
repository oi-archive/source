# 题目描述


<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【问题描述】</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">由于矩阵乘法满足结合律，故其连乘积的计算可以有许多不同的计算次序。计算次序可以通过加括号的方式来确定。例如A1A2A3的连乘积可以有两种加括号的方式：((A1A2)A3)和(A1(A2A3))</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">矩阵连乘积的计算次序与连乘积的计算量有关。已知两个矩阵Apq和Aqr相乘的计算量为p*q*r，请确定矩阵连乘积A1A2...An的最小计算量的计算次序。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">假设Ai的维数是Pi-1×Pi（ i=1,2,...,n ， 1&lt;=n&lt;10）</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行　　组数M　　（1&lt;=m&lt;=6）</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">以下有M组，每组有两行，格式如下： </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">N</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">P0  P1  P2 ... Pn</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出文件(t1.out)：</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">共有M组，每组有两行，其格式为：</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">连乘积的最小计算量L          （在[1,1000000]内）</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">矩阵连乘积的计算顺序</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入输出样例】</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">样例输入：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 3 5 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 3 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 2 5 100 2</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">样例输出：</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">30</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> (A1A2)</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> 1020</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> (A1(A2A3))</span> 
</p>
<p>
<br/>
</p>
