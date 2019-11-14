
# Description

<div class="content"><div style="line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">终于到达了这次选拔赛的最后一题，想必你已经厌倦了小蓝和小白的故事，为了回馈各位比赛选手，此题的主角是贯穿这次比赛的关键人物——小蓝的好友。</span></span></div>
<div style="text-indent: 24pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">在帮小蓝确定了旅游路线后，小蓝的好友也不会浪费这个难得的暑假。与小蓝不同，小蓝的好友并不想将时间花在旅游上，而是盯上了最近发行的即时战略游戏——</span><span style="line-height: 150%">SangoCraft</span><span style="line-height: 150%">。但在前往通关之路的道路上，一个小游戏挡住了小蓝的好友的步伐。</span></span></div>
<div style="text-indent: 24pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">“国家的战争其本质是抢夺资源的战争”是整款游戏的核心理念，这个小游戏也不例外。简单来说，用户需要在给定的长方形土地上选出一块子矩形，而系统随机生成了</span><span style="line-height: 150%">N</span><span style="line-height: 150%">个资源点，位于用户所选的长方形土地上的资源点越多，给予用户的奖励也越多。悲剧的是，小蓝的好友虽然拥有着极其优秀的能力，但同时也有着极差的</span><span style="line-height: 150%">RP</span><span style="line-height: 150%">，小蓝的好友所选的区域总是没有一个资源点。</span></span></div>
<div style="text-indent: 24pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">终于有一天，小蓝的好友决定投诉这款游戏的制造厂商，为了搜集证据，小蓝的好友想算出至少包含一个资源点的区域的数量。作为小蓝的好友，这自然是你分内之事。</span></span></div>
<div style="line-height: 150%"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 26.25pt; line-height: 150%"><span style="font-size: medium"> <span style="line-height: 150%">每个输入文件中仅包含一个测试数据。</span></span></div>
<div style="text-indent: 30pt; line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">第一行包含两个由空格隔开的正整数</span><span style="line-height: 150%">R,C,N</span><span style="line-height: 150%">，表示游戏在一块</span><span style="line-height: 150%">[1,R]X[1,C]</span><span style="line-height: 150%">的地图上生成了</span><span style="line-height: 150%">N</span><span style="line-height: 150%">个资源点。</span></span></div>
<div style="line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">     </span><span style="line-height: 150%">接下来有</span><span style="line-height: 150%">N</span><span style="line-height: 150%">行，每行包含两个整数</span><span style="line-height: 150%"> x,y</span><span style="line-height: 150%">，表示这个资源点的坐标</span></span></div>
<div style="line-height: 150%"><span style="font-size: medium"><span style="line-height: 150%">(1&lt;=x&lt;=R,1&lt;=Y&lt;=c)</span><span style="line-height: 150%">。</span></span></div></div>

# Output

<div class="content"><div style="line-height: 150%"><span style="font-size: medium">      <span style="line-height: 150%">输出文件应仅包含一个整数，表示至少包含一个资源点的区域的数量。具体的说，设</span><span style="line-height: 150%">N</span><span style="line-height: 150%">个资源点的坐标为</span><span style="line-height: 150%">(i=1..n),</span><span style="line-height: 150%">你需要计算有多少个<b>四元组</b></span><b><span style="line-height: 150%">(LB,DB,RB,UB)</span></b><b><span style="line-height: 150%">满足</span></b><b><span style="line-height: 150%">1&lt;=LB&lt;=RB&lt;=R,1&lt;=DB&lt;=UB&lt;=C</span></b><b><span style="line-height: 150%">，且存在一个</span></b><b><span style="line-height: 150%">i</span></b><b><span style="line-height: 150%">使得</span></b></span></div>
<div style="line-height: 150%"><span style="font-size: medium"><b><span style="line-height: 150%">LB&lt;=Xi&lt;=RB,DB&lt;=Yi&lt;=UB</span></b></span></div>
<div style="line-height: 150%"><span style="font-size: medium"><b><span style="line-height: 150%">均成立</span></b><span style="line-height: 150%">。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">      5 5 4<br/>
     1 2<br/>
     2 3<br/>
     3 5<br/>
     4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">139<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】<br/><br/>
对于100%的数据，R,C&lt;=40000,N&lt;=100000，资源点的位置两两不同，且位置为随机生成。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

