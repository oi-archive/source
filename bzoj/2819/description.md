
# Description

<div class="content"><p><span style="font-size: medium">著名游戏设计师vfleaking，最近迷上了Nim。普通的Nim游戏为：两个人进行游戏，N堆石子，每回合可以取其中某一堆的任意多个，可以取完，但不可以不取。谁不能取谁输。这个游戏是有必胜策略的。于是vfleaking决定写一个玩Nim游戏的平台来坑玩家。<br/>
为了设计漂亮一点的初始局面，vfleaking用以下方式来找灵感：拿出很多石子，把它们聚成一堆一堆的，对每一堆编号1,2,3,4,...n,在堆与堆间连边，没有自环与重边，从任意堆到任意堆都只有唯一一条路径可到达。然后他不停地进行如下操作：<br/>
<br/>
1.随机选两个堆v,u，询问若在v到u间的路径上的石子堆中玩Nim游戏，是否有必胜策略，如果有，vfleaking将会考虑将这些石子堆作为初始局面之一，用来坑玩家。<br/>
2.把堆v中的石子数变为k。<br/>
<br/>
由于vfleaking太懒了，他懒得自己动手了。请写个程序帮帮他吧。<br/>
<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4"> 第一行一个数n，表示有多少堆石子。<br/>
接下来的一行，第i个数表示第i堆里有多少石子。<br/>
接下来n-1行，每行两个数v,u，代表v,u间有一条边直接相连。<br/>
接下来一个数q，代表操作的个数。<br/>
接下来q行，每行开始有一个字符：<br/>
如果是Q，那么后面有两个数v,u，询问若在v到u间的路径上的石子堆中玩Nim游戏，是否有必胜策略。<br/>
如果是C，那么后面有两个数v,k，代表把堆v中的石子数变为k。<br/>
<br/>
对于100%的数据：<br/>
1≤N≤500000, 1≤Q≤500000, 0≤任何时候每堆石子的个数≤32767<br/>
其中有30%的数据：<br/>
石子堆组成了一条链，这3个点会导致你DFS时爆栈（也许你不用DFS？）。其它的数据DFS目测不会爆。<br/>
<br/>
</font><span style="font-family: arial, verdana, helvetica, sans-serif; font-size: medium; text-align: left; ">注意：石子数的范围是0到INT_MAX</span></p></div>

# Output

<div class="content"><p><font size="4">对于每个Q，输出一行Yes或No，代表对询问的回答。<br/>
<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入】<br/>
5<br/>
1 3 5 2 5<br/>
1 5<br/>
3 5<br/>
2 5<br/>
1 4<br/>
6<br/>
Q 1 2<br/>
Q 3 5<br/>
C 3 7<br/>
Q 1 2<br/>
Q 2 4<br/>
Q 5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No<br/>
Yes<br/>
Yes<br/>
Yes<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=湖北省队互测">湖北省队互测</a></p></div>

