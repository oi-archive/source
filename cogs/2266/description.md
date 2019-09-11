# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="font-size:14px;">如图所示为某生态系统的食物网示意图，据图回答第一小题。</span> 
</p>
<p>
<img alt="" src="/upload/image/20160424/20160424071725_76207.jpg"/> 
</p>
<p>
<span style="font-size:14px;">1.数一数，在这个食物网中有几条食物链（   ）</span> 
</p>
<p>
<span style="font-size:14px;"><span style="font-size:16px;">现在给你$n$个物种和$m$条能量流动关系，求其中的食物链条数。</span></span> 
</p>
<p>
<span style="font-size:14px;"><span style="font-size:16px;">物种的名称为从$1$到$n$编号，$m$条能量流动关系形如</span></span> 
</p>
<p>
<span style="font-size:14px;"><span style="font-size:16px;">$a_1\ b_1$</span></span> 
</p>
<p>
<span style="font-size:14px;"><span style="font-size:16px;"></span></span>$a_2\ b_2$
</p>
<p>
$a_3\ b_3$
</p>
<p>
$\dots\dots$
</p>
<p>
$a_{m-1}\ b_{m-1}$
</p>
<p>
$a_m\ b_m$
</p>
<p>
其中$a_i\ b_i$表示能量从物种$a_i$流向物种$b_i$。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个正整数$n$和$m$。
</p>
<p>
接下来$m$行每行两个整数$a_i\ b_i$表示$m$条能量流动关系。
</p>
<p>
（数据保证输入数据符<del>号</del>合生物学特点，且不会有重复的能量流动关系出现）
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数即食物网中的食物链条数。
</p>
<h3>
【样例输入】
</h3>
<pre>10 16
1 2
1 4
1 10
2 3
2 5
4 3
4 5
4 8
6 8
7 6
7 9
8 5
9 8
10 6
10 7
10 9
</pre>
<h3>
【样例输出】
</h3>
<pre>9
</pre>
<h3>
【样例解释】
</h3>
<p>
就是上面<strong>题目描述<del>1</del></strong>的那个图。
</p>
<p>
各个物种的编号依次为：
</p>
<p>
草&lt;-&gt;1 兔&lt;-&gt;2 狐&lt;-&gt;3 鼠&lt;-&gt;4 猫头鹰&lt;-&gt;5 吃虫的鸟&lt;-&gt;6 蜘蛛&lt;-&gt;7 蛇&lt;-&gt;8 青蛙&lt;-&gt;9 食草昆虫&lt;-&gt;10。
</p>
<h3>
【数据范围】
</h3>
<p>
$1 \leq n \leq 100000,0 \leq m \leq 200000$。
</p>
<h3>
【来源】
</h3>
<p>
HAOI2016上午第一题 部分题面由ck进行调整
</p>
