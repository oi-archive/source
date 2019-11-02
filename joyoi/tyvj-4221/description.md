# 

 
 # 题目背景 
<p style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20px;">蒟蒻中学的蒟蒻遇到了一些小问题。</p> 

 
 # 题目描述 
<p>蒟蒻考完noip也就要回家种田了，他老家的田地在s点，可是种子市场在e点，为了购买种子，中途要经过很多城市，这导致快递费非常的贵（因为快到双11了），于是他准备自己开车，可现在油价也不便宜，他想尽量省一些油。</p>

<p>已知蒟蒻掌握着熟练的漂移技巧，当他在点A(x1,y1)时，他可以使用漂移到达点B(x2,y2)，这样耗费的油量为<u>|x1-x2|和|y1-y2|(x差值的绝对值和y差值的绝对值)中<strong>较小</strong></u>的那一个。</p>

<p>现在蒟蒻要从s点到e点，请问他最少消耗多少油？</p> 

 
 # 输入格式 
<p>第一行三个数&nbsp;n,s,e，代表有n个点，起点为s号点，终点为e号点</p>

<p>第2到第n+1行，第i行两个数&nbsp;代表一个点(x,y)&nbsp;</p>

<p><strong>点的标号从</strong><strong>1</strong><strong>开始</strong></p> 

 
 # 输出格式 
<p>一行一个数&nbsp;为消耗的最少油量</p>

<p>&nbsp;</p> 

 
 # 提示 
<p><strong>样例输入</strong><strong>1</strong></p>

<p>5&nbsp;1&nbsp;5</p>

<p>1&nbsp;1</p>

<p>2&nbsp;1</p>

<p>3&nbsp;1</p>

<p>4&nbsp;1</p>

<p>5&nbsp;1</p>

<p>&nbsp;</p>

<p><strong>样例输出</strong><strong>1</strong></p>

<p>0</p>

<p>&nbsp;</p>

<p><strong>样例解释</strong><strong>1</strong></p>

<p>直接从1号点（1,1）漂移到5号点（5,1）花费为1-1=0</p>

<p>&nbsp;</p>

<p><strong>样例输入</strong><strong>2</strong></p>

<p>5&nbsp;1&nbsp;5</p>

<p>2&nbsp;1</p>

<p>3&nbsp;3</p>

<p>5&nbsp;2</p>

<p>1&nbsp;4</p>

<p>6&nbsp;6</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p><strong>样例输出</strong><strong>2</strong></p>

<p>2</p>

<p>&nbsp;</p>

<p><strong>样例解释</strong><strong>2</strong></p>

<p>从1号点（2,1）漂移到3号点（5,2）花费为2-1=1</p>

<p>从3号点（5,2）漂移到终点5号点（6,6）花费为6-5=1</p>

<p>这是一个消耗油量最少的解&nbsp;为2</p>

<p>&nbsp;</p>

<p><strong>数据范围：</strong></p>

<p>对于50%的数据&nbsp;2&lt;=n&lt;=3000</p>

<p>对于100%的数据&nbsp;2&lt;=n,s,e&lt;=100000&nbsp;&nbsp;0&lt;=x,y&lt;=1000000000</p> 
