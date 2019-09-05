# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
自miner在地狱炼魂完后，miner终于有了去击杀末影龙的勇气，但是，领域中同时极大限度的加强了末影龙的攻打难度，使得全身附魔的miner不敢独身前往末地。于是miner找到了领域中的MINER LEAGUE,请求league调动人员一同击杀末影龙。
</p>
<p>
但是与末影龙相对抗是一定会有人员损伤的，而league master也不能让成员们听这么一个无名小卒（miner）的调动，所以，league master决定跟miner玩一个小游戏。如果miner赢了，那么master就调动成员前去斩杀末影龙；如果miner输了，那么master就调动成员前去斩杀miner。。。
</p>
<p>
游戏规则如下：
</p>
<p>
   Master拿出一张卡片，miner在卡片上写下一个数字1；
</p>
<p>
   然后miner和master轮流操作，每一次可以把数字卡片上的数字x变成x+1或2x；
</p>
<p>
（miner先写下数字1，然后master进行操作）,规定写下数字n的人胜利.
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行一个整数T(T&lt;=10000),表示共有T个正整数n需要进行判断；
</p>
<p>
   第二行到第T+1行 每一行一个正整数n(n &lt; 2^63);
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
现在，对于一个给定的正整数n，判断miner是否有必胜策略:
</p>
<p>
如果有,输出miner win
</p>
<p>
如果没有,输出miner lose
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
2
</p>

<p>
<br/>

</p>

<p>
7
</p>

<p>
<br/>

</p>

<p>
8
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
miner win
</p>

<p>
miner lose
</p>
</pre>
<h3>
【来源】
</h3>
<p>
lyc
</p>
