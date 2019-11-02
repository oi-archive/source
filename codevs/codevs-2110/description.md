<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>曾经有一个颇为流行的小游戏，名称已无法考证，我们姑且把它叫做“尔虞我诈”。游戏规则是这样的：有N人参加比赛，每两人进行一场游戏（因此共进行N*(N-1)/2场游戏），每场游戏分十轮，在每轮中，两人同时说出“TRADE”和“CHEAT”其中之一，如果两人都“TRADE”，各得一分，如果两人都“CHEAT”，各扣一分，如果一个“TRADE”，一个“CHEAT”，则CHEAT的那个人得2分，TRADE的扣2分。每人得的N-1场分数的总和为该人的最后得分,看谁的得分最高。当然，在比赛之前每人的得分为0。如何才能取胜呢？人们设计了很多战术，可以用以下的“战术语言”来描述：</span><br><span>&lt;program&gt; ::= &lt;statement&gt;. </span><br><span>&lt;statement&gt; ::= &lt;command&gt; | &lt;ifstat&gt; </span><br><span>&lt;ifstat&gt; ::= IF &lt;condition&gt; THEN &lt;statement&gt; ELSE &lt;statement&gt; </span><br><span>&lt;condition&gt; ::= &lt;cond&gt; | &lt;cond&gt; &lt;op&gt; &lt;condition&gt; </span><br><span>&lt;op&gt; ::= AND | OR </span><br><span>&lt;cond&gt; ::= &lt;memory&gt; {= | #} {&lt;command&gt; | NULL} </span><br><span>&lt;memory&gt; ::= {MY | YOUR} LAST {1 | 2} </span><br><span>&lt;command&gt; ::= TRADE | CHEAT </span><br><span>#的意思是“不等于”，NULL的意思是空，不存在。</span><br><span>空格可以在任何地方出现。</span><br><span>例如：</span><br><span>CHEAT.</span><br><span>和</span><br><span>IFYOURLAST2=NULLTHENTRADEELSEIFYOURLAST1=TRADETHENTRADEELSECHEAT.</span><br><span>是两个合法的战术语言程序。</span><br><span>编程模拟给定程序间的游戏情况。 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行，N（&lt;=10），以下 N 行，每一行为一个程序（长度&lt;=255）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>共 1 行，有 N 个整数，分别为各程序的最后得分。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>输入：</span><br><span>3</span><br><span>CHEAT.</span><br><span>IF MY LAST1 = CHEAT THEN TRADE ELSE CHEAT.</span><br><span>IFYOURLAST2=NULLTHENTRADEELSEIFYOURLAST1=TRADETHENTRADEELSECHEAT.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>输出：</span><br><span>1 -12 -13</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题目</p>
</div>
</div>