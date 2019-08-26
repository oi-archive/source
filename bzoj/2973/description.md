
# Description

<div class="content"><div style="text-indent: 24pt" align="left"><span style="font-size: 12pt">石头游戏的规则是这样的。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">石头游戏在一个</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">行</span><span style="font-size: 12pt">m</span><span style="font-size: 12pt">列的方格阵上进行。每个格子对应了一个编号在</span><span style="font-size: 12pt">0~9</span><span style="font-size: 12pt">之间的操作序列。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">操作序列是一个长度不超过</span><span style="font-size: 12pt">6</span><span style="font-size: 12pt">且循环执行、每秒执行一个字符的字符串。它包括：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">数字</span><span style="font-size: 12pt">0~9</span><span style="font-size: 12pt">：拿</span><span style="font-size: 12pt">0~9</span><span style="font-size: 12pt">个石头到该格子。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">NWSE</span><span style="font-size: 12pt">：把这个格子内所有的石头推到相邻的格子。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">D</span><span style="font-size: 12pt">：拿走这个格子的石头。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">石头游戏的问题是：当这个石头游戏进行了</span><span style="font-size: 12pt">t</span><span style="font-size: 12pt">秒之后，所有方格中最多的格子有多少个石头。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">注意：所有格子的操作同时执行。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">第一行三个整数</span><span style="font-size: 12pt">n, m, t, act</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">行，每行</span><span style="font-size: 12pt">m</span><span style="font-size: 12pt">个字符，表示每个格子对应的</span><span style="font-size: 12pt">操作序列。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">最后</span><span style="font-size: 12pt">act</span><span style="font-size: 12pt">行，每行一个字符串，表示从</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">开始的每个操作序列。</span></div></div>

# Output

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">一个整数：游戏进行了</span><span style="font-size: 12pt">t</span><span style="font-size: 12pt">秒之后，所有方格中最多的格子有多少个石头。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 6 10 3<br/>
011112<br/>
1E<br/>
E<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
【样例解释】<br/>
这是另一个类似于传送带的结构。左边的设备0间隔地产生石头并向东传送。设备1向右传送，直到设备2。10秒后，总共产生了5个石头，2个在传送带上，3个在最右边。<br/>
【数据约定】<br/>
0≤n, m≤8。<br/>
1≤act≤10。<br/>
1≤t≤10^9。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

