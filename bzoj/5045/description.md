
# Description

<div class="content"><div>小Q最近沉迷于一款新型《打砖块》游戏。在每局游戏中，呈现在屏幕上的是一堵无限大小的墙壁。墙壁上镶嵌着</div>
<div>无数长度为2、宽度为1的砖块。墙壁被分成若干行，每行宽度都为1，相邻两个格子形成一个砖块。相邻两行的砖</div>
<div>块是间隔摆放的。墙壁从下往上行编号递增，从左往右列编号递增。如下图所示：</div>
<div><img src="source/bzoj/5045/img/aHR0cDovL2JlZ2luLmx5ZHN5LmNvbS9KdWRnZU9ubGluZS91cGxvYWQvMjI4NS5wbmc=.png" alt=""/></div>
<div>在游戏的一开始，有n块砖块消失了。如果两块在同一行且相邻的砖块都消失了，那么玩家可以移除它们上方与它</div>
<div>们都相邻的那一个砖块。请写一个程序帮助小Q计算最多可以让多少个位置没有砖块。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数n(1&lt;=n&lt;=100000)，表示一开始消失的砖块个数。</div>
<div>接下来n行，每行两个整数x_i,y_i(|x_i|,|y_i|&lt;=10^9)</div>
<div>分别表示每个消失的砖块的位置，即左半部分位于第x_i行第y_i列。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即没有砖块的位置个数的最大值。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
0 0<br/>
0 2<br/>
2 0<br/>
3 1<br/>
1 3<br/>
3 5<br/>
0 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

