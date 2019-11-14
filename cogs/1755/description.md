# 题目描述


<p class="default" style="margin-left:7.5pt;">
<span style="font-size:13.5pt;">【背景】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default" style="text-indent:23pt;">
<span style="font-size:13.5pt;">乃们都玩过赛尔号吧</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">……</span><span style="font-size:13.5pt;">，那有木有玩过赛尔号</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">2</span><span style="font-size:13.5pt;">呢？（众人：你</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">TM</span><span style="font-size:13.5pt;">都多大了</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">……</span><span style="font-size:13.5pt;">）</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">(</span><span style="font-size:13.5pt;">⊙</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">o</span><span style="font-size:13.5pt;">⊙</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">)…</span><span style="font-size:13.5pt;">，多大怎么了，哥一直怀着一颗永不泯灭的童心</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">~</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【问题描述】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">    </span><span style="font-size:13.5pt;">众所周知（呃，没玩过的除外），卡顿啾啾是赛尔号</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">2</span><span style="font-size:13.5pt;">里的一个普通系精灵，其未进化体名叫啾啾，进化后体型肥胖，励志减肥。历经磨难终于摆脱肥胖的困扰，前后变化实在让人难以想象。咳咳，这不是问题的重点</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">……</span><span style="font-size:13.5pt;">（众人：</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">-_-#</span><span style="font-size:13.5pt;">）</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">   <span class="apple-converted-space"> </span></span><span style="font-size:13.5pt;">（从众人乱拳中挤了出来）好吧，开始今天的重点。啾啾是个很调皮的精灵，它特别喜欢玩捉迷藏，本题即是由赛尔号</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">2</span><span style="font-size:13.5pt;">中爱上捉迷藏这一小游戏改编而来。通关小游戏就可以</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">……</span><span style="font-size:13.5pt;">（瞥了一眼青筋暴起的一群禽兽</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">…</span><span style="font-size:13.5pt;">）呃，不要那么暴力好不好</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">~TAT</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default" style="text-indent:22.5pt;">
<span style="font-size:13.5pt;">啾啾藏在了一个</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">m*n</span><span style="font-size:13.5pt;">的矩阵中，这个矩阵有</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">m*n</span><span style="font-size:13.5pt;">个格子，啾啾就在其中之一。这种格子采用特殊材料制成，外表透明，藏在其中用眼睛根本无法看到什么变化。但是这毕竟是赛尔号的科技，所以小赛尔只要把手在格子上轻轻敲击就会得到回复，我们记为该格子的状态。其中若返回为</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">X</span><span style="font-size:13.5pt;">，则该点可能啾啾藏身的格子，但也有可能是距离啾啾很远的格子；若返回为</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">N</span><span style="font-size:13.5pt;">，则啾啾就在以该点为中心的</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">7*7</span><span style="font-size:13.5pt;">的矩阵中的某个格子；若返回为</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">C,<span class="apple-converted-space"> </span></span><span style="font-size:13.5pt;">则啾啾就在以该点为中心的</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">5*5</span><span style="font-size:13.5pt;">的矩阵中的某个格子；若返回为</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">Z</span><span style="font-size:13.5pt;">；则啾啾就在以该点为中心的</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">3*3</span><span style="font-size:13.5pt;">的矩阵中的某个格子。</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default" style="text-indent:22.5pt;">
<span style="font-size:13.5pt;">现在某个小赛尔为了快速通关而获得奖励，使用了外挂，从而获得了每个格子的返回值，但是看着眼花缭乱的字母，却无从下手，于是便找到了你（至于怎么找到的，为了我的生命安全，我还是不说了），请你编写程序帮助他找到啾啾所在的格子。（众人：这种水题还好意思说这么长时间！）啊！！！！！！（惨叫声）</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【输入数据格式】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">第一行两个数</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">n,m,</span><span style="font-size:13.5pt;">表示一个</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">m*n</span><span style="font-size:13.5pt;">的矩阵；</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">第二行到第</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">m−1</span><span style="font-size:13.5pt;">行每行一个长度为</span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">n</span><span style="font-size:13.5pt;">的字符串，表示矩阵状态。</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【输出数据格式】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">一行两个数，分别为啾啾藏身的格子的列数和行数。</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【输入样例】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">6 4</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">ZZZCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">ZXZCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">ZZZCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">CCCCNX</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【输出样例】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;">2 2</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【数据范围及约定】</span><span class="apple-converted-space"><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;"> </span></span><span style="font-size:13.5pt;font-family:&#39;Times New Roman&#39;, serif;"> </span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;color:windowtext;">20%</span><span style="font-size:13.5pt;">的数据：</span><span style="font-size:13.5pt;font-family:&#39;color:windowtext;">1≤n,m≤5;</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;color:windowtext;">60%</span><span style="font-size:13.5pt;">的数据：</span><span style="font-size:13.5pt;font-family:&#39;color:windowtext;">1≤n,m≤70;</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;font-family:&#39;color:windowtext;">100%</span><span style="font-size:13.5pt;">的数据：</span><span style="font-size:13.5pt;font-family:&#39;color:windowtext;">1≤n,m≤100;<span class="apple-converted-space"> </span></span><span style="font-size:13.5pt;font-family:&#34;"> </span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">【</span><span style="font-size:13.5pt;font-family:&#34;">Hite</span><span style="font-size:13.5pt;">】</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="default">
<span style="font-size:13.5pt;">真的真的很水。</span><span style="font-family:&#39;Times New Roman&#39;, serif;"></span> 
</p>
<p class="MsoNormal">
<span> </span> 
</p>
