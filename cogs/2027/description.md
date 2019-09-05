# 题目描述


<h3>
【题目描述】
</h3>
<p>
<img src="/upload/image/20150818/20150818192106_73831.gif" alt=""/> 
</p>
<p>
一个实数集合S，把它分成k部分，<strong><u>k部分的元素先求和</u><strong><u>再</u></strong></strong><strong><u>相乘</u></strong>后得到一个数，这种把集合映射为实数的变换称为可达鸭集合变换。现在给定一个<strong><u>自然数集合</u></strong>，请求出可达鸭集合变换在k=2意义下所能得到的<strong><u>最大值</u></strong> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数n
</p>
<p>
接下来n个整数b1,b2,….bn
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数ANS,表示能得到的最大值
</p>
<h3>
【样例输入】
</h3>
<pre>4
1 2 3 4
</pre>
<h3>
【样例输出】
</h3>
<pre> 25
</pre>
<h3>
【提示】
</h3>
<p>
令(1,4)一个集合，(2,3)一个集合，答案为5*5=25最大
</p>
<p>
定义S=b1+b2+…bn
</p>
<p>
对于30%的数据，n&lt;=20,S&lt;=1000
</p>
<p>
对于70%的数据，n&lt;=100,S&lt;=15000
</p>
<p>
对于100%的数据，n&lt;=200,S&lt;=1000000，bi&gt;=0
</p>
<p>
集合满足互异性，即没有任何一种元素会在同一集合中出现两次。
</p>
<h3>
【来源】
</h3>
<p>
<br/>
</p>