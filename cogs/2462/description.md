# 题目描述


<h3>
【题目描述】
</h3>
<p>
小A和小B用C++的rand()函数玩随机数游戏，刚开始小A有a分，小B有b分，每一轮游戏两个人使用rand()函数生成一个$[-k,k]$之间的整数作为得分(比如k=2的时候可能会生成-2,1,0,1,2)，游戏一共进行T轮，求总共有多少种不同的游戏使得小A的最终得分大于小B？<strong>两个游戏不同当且仅当至少有一轮存在一个人的得分不同。</strong> 
</p>
<h3>
【输入格式】
</h3>
<p>
只有一行四个数字，为a,b,k,T
</p>
<h3>
【输出格式】
</h3>
<p>
只有一行一个数字，为答案对$10^9+7$取膜后的值
</p>
<h3>
【样例输入1】
</h3>
<pre>1 2 2 1</pre>
<h3>
【样例输出1】
</h3>
<pre>6</pre>
<h3>
【样例输入2】
</h3>
<pre>1 1 1 2</pre>
<h3>
【样例输出2】
</h3>
<pre>31</pre>
<h3>
【提示】
</h3>
<p>
In the first sample test, A starts with 1 and B starts with 2. If B picks  - 2, A can pick 0, 1, or 2 to win. If B picks  - 1, A can pick 1 or 2 to win. If B picks 0, A can pick 2 to win. If B picks 1 or 2, A cannot win. Thus, there are 3 + 2 + 1 = 6 possible games in which A wins.
</p>
<p>
对于20%的数据,$T&lt;=3$
</p>
<p>
对于60%的数据,$k&lt;=100,T&lt;=50$
</p>
<p>
对于100%的数据,$0&lt;=a,b&lt;=10^6,k&lt;=1000,T&lt;=100$
</p>
<h3>
【来源】
</h3>
<p>
CF 712D
</p>
