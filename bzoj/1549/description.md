
# Description

<div class="content">这一天,Hnsdfz信息组的众人决定上岳麓山玩.岳麓山上的可以探险的地方非常多,而信息组的Oier们給每一个地方都设定了一个危险值,代表探险这个景点需要承担的危险,而整个岳麓山可以抽象为由n行数字组成的数字梯形.而梯形顶端有m个数字,在每个数字处可以往左上或右上移动,形成一条从梯形底至顶的路径.
而一开始,每个人都觉得如果走过别人走过的地方就太没个性了.于是有
任务一: 找出m条完全不相交的至底至顶的路径.
但略一思考,又都觉得如果限定这么死,那就太无趣了,于是有:
任务二: 找出m条仅在数字处相交的路径.
现在,做为整个浏览计划的发起者,你要计算出对于任务一与任务二,每个人观赏线路所能经受的最小危险.
</div>

# Input

<div class="content">第一行两个正整数n,m.表示整个梯形有n行,第一行有m个列.
接下来n行描述整个数字梯形.第I行有n+I-1个数字.

</div>

# Output

<div class="content">分两行输出,分别是对应任务一与任务二的结果.
</div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
1 2<br/>
2 1 2<br/>
2 2 2 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10 <br/>
9<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>样例解释<br/>
第I个数字表示每条路线在第I行走第几个数字.<br/>
任务一的两条路线 1 1 1;2 2 2;<br/>
任务二的两条路线 1 2 1;2 2 2;<br/>
<br/>
数据范围<br/>
对于 10% 的数据 n&lt;=10;  m&lt;=5;<br/>
对于100% 的数据 n&lt;=80;  m&lt;=80; 每个数字&lt;=20;<br/>
<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day4">HNOI2009集训Day4</a></p></div>

