# 题目描述


USACO/game1
<div id="bodyContent">
<div dir="ltr" lang="zh-cn" class="mw-content-ltr">
<p>
<b>A Game</b>游戏
</p>
<p>
译 by 肖遥
</p>
<hr/>
</div>
</div>
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
<p>
有如下一个双人游戏:N(2 &lt;= N &lt;= 100)个正整数的序列放在一个游戏平台上，游戏由玩家1开始，两人轮流从序列的两端取数，取数后该数字被去掉并累加到本玩家的得分中，当数取尽时，游戏结束。以最终得分多者为胜。
</p>
<p>
编一个执行最优策略的程序，最优策略就是使玩家在与最好的对手对弈时，能得到的在当前情况下最大的可能的总分的策略。你的程序要始终为第二位玩家执行最优策略。
</p>
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
<p>
<b>PROGRAM NAME</b>: game1
</p>
<p>
<b>INPUT FORMAT</b>:
</p>
<p>
(file game1.in)
</p>
<p>
第一行: 正整数N, 表示序列中正整数的个数。
</p>
<p>
第二行至末尾: 用空格分隔的N个正整数（大小为1-200）。
</p>
<p>
<b>OUTPUT FORMAT</b>:
</p>
<p>
(file game1.out)
</p>
<p>
只有一行，用空格分隔的两个整数: 依次为玩家一和玩家二最终的得分。
</p>
<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span> 
<pre>6 
4 7 2 9 5 2
</pre>
<span id="SAMPLE_OUTPUT" class="mw-headline">SAMPLE OUTPUT </span> 
<pre>18 11
</pre>
<!-- NewPP limit report Preprocessor node count: 15/1000000 Post-expand include size: 0/2097152 bytes Template argument size: 0/2097152 bytes Expensive parser function count: 0/100 --><!-- Saved in parser cache with key newnocow:pcache:idhash:855-0!*!*!!zh-cn!*!* and timestamp 20120711015649 -->
<p>
 
</p>
