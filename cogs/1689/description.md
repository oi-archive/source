# 题目描述


<h3>
【题目描述】
</h3>
<p>
某天，Lostmonkey发明了一种超级弹力装置，为了在他的绵羊朋友面前显摆，他邀请小绵羊一起玩个游戏。游戏一开始，Lostmonkey在地上沿着一条直线摆上n个装置，每个装置设定初始弹力系数ki，当绵羊达到第i个装置时，它会往后弹ki步，达到第i+ki个装置，若不存在第i+ki个装置，则绵羊被弹飞。绵羊想知道当它从第i个装置起步时，被弹几次后会被弹飞。为了使得游戏更有趣，Lostmonkey可以修改某个弹力装置的弹力系数，任何时候弹力系数均为正整数。
</p>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
第一行包含一个整数n，表示地上有n个装置，装置的编号从0到n-1,接下来一行有n个正整数，依次为那n个装置的初始弹力系数。第三行有一个正整数m，接下来m行每行至少有两个数i、j，若i=1，你要输出从j出发被弹几次后被弹飞，若i=2则还会再输入一个正整数k，表示第j个弹力装置的系数被修改成k。对于10%的数据n,m&lt;=10000，对于100%的数据n&lt;=200000,m&lt;=100000
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
对于每个i=1的情况，你都要输出一个需要的步数，占一行。
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>4                              
1 2 1 1						   
3
1 1
2 1 1
1 1
  </pre>
<h3>
【样例输出】
</h3>
<pre>2
3
  </pre>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=2002">耒阳大世界（衡阳八中） OJ 2002</a>