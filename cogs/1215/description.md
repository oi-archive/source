# 题目描述


<span style="font-family:Microsoft YaHei;font-size:16px;">TYVJ八月月赛提高组第2题<br/>
<br/>
测试点数目：5<br/>
测试点分值：20<br/>
--内存限制：128M<br/>
--时间限制：1s</span> 
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【题目描述】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:16px;"> </span> 
</p>
<div>
北冰洋有一座孤岛，多年来一直没电。近日，令岛民们振奋的消息传来：S国的专家要为他们修建电网！！！<br/>
孤
岛上共有N个村庄，发电站要建在第K个村庄中。S国的专家要在N个村庄间修建M条输电线路，但由于地理原因，M条线路无法保证每个村庄都与第K个村庄(建
有发电站)直接相连，同样，也不一定能保证每个村庄都与第K个村庄间接相连(假设A与B直接相连，B与C直接相连，那么A与C间接相连)。<br/>
然而，由于S国的专家智商实在太“高”了，以至于设计出了许多冗余线路。现给出第i条线路两个端点Ui,Vi(分别表示线路连接的两个村庄,Ui!=Vi)和长度Li，请你帮岛民算一下：如果电网可以覆盖全岛，最少需要多长的电线；若不能，有多少个村庄无电可用。<br/>
注意：0&lt;=冗余线路数目<m；部分数据有重边。电网可双向导电。<br>
</m；部分数据有重边。电网可双向导电。<br>
</div>
<p>
<br/>
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:16px;"> </span> 
</p>
<div>
第一行：N M K<br/>
接下来M行：Ui Vi Li<br/>
具体含义见题目描述<br/>
</div>
<p>
<br/>
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:16px;">如果电网可以覆盖全岛，输出最少需要的电线长度；<br/>
若不能，输出无电可用的村庄的个数。</span> 
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【样例输入】</span> 
</h3>
<pre>【样例1】
5 5 1
1 2 1
2 3 1
3 4 1
4 5 1
5 1 1

【样例2】
5 5 1
1 2 1
1 2 2
1 2 3
3 4 1
5 4 2
</pre>
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【样例输出】</span> 
</h3>
<pre>【样例1】
4

【样例2】
3
</pre>
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【提示】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:16px;">样例解释：<br/>
对于样例一，电网可以覆盖全岛，最短长度为4；<br/>
对于样例二，电网无法覆盖3,4,5这3个村庄。<br/>
<br/>
数据范围：</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;font-size:16px;">对于100的数据，1&lt;=n,m&lt;=200000,  1&lt;=li&lt;=10^7;<br/>
对于20%的数据，有1<m,n<=10;<br>
对于60%的数据，有1<m,n<=1000;<br>
对于100%的数据，有1<m,n<=200000,0<li<=1e+7;<br>
对于40%的数据，电网无法覆盖全岛。</m,n<=200000,0<li<=1e+7;<br>
</m,n<=1000;<br>
</m,n<=10;<br>
</span> 
</p>
<h3>
<span style="font-family:Microsoft YaHei;font-size:16px;">【来源】</span> 
</h3>
<p>
<span style="font-family:Microsoft YaHei;font-size:16px;">From tbcaaa8 <a href="http://www.tyvj.cn/Problem_Show.aspx?id=1591" target="_blank">http://www.tyvj.cn/Problem_Show.aspx?id=1591</a></span> 
</p>
