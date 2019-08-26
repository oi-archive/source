
# Description

<div class="content"><p><span style="font-size: medium">Logic_IU和Lao5是T国的花匠，平时的一大爱好是除草。<br/>
清晨天气晴朗，阳光明媚，Logic_IU和Lao5奉命给皇宫新建的花园除草。由于技术捉鸡，被去花园采花的公主Freda训斥。郁闷的Logic_IU听说Hengzo星人非常擅长花匠工艺，于是决定踏上寻找Hengzo星的道路。<br/>
Logic_IU来到了HE星系，这个星系共有N座星球，以及M条规划好的飞行路线（是的，Logic_IU自己会飞！）。星系管理局规划飞行路线时遵守一个准则：只有在某两颗星球间尚不存在可以直接或间接到达的路径时，他们才会在这两颗星球间直接设置一条路线。他们允许在飞行路线上进行双向飞行。星系管理局保证所有星球间都是可以互相到达的。<br/>
最近，为了方便人们的出行，星系管理局开通了一系列单向传送通道。为了鼓励人们使用，现在每位游客在经过某条单向传送通道时均可获得该通道限定版的人偶一个。显然，Logic_IU非常喜欢人偶，她希望收集全部的限定版人偶。<br/>
不幸的是，这个星系的人非常讨厌来自异世界的客人，如果有人在离开某座星球之后又回到了那座星球，他就会被 吃☆掉 。<br/>
Logic_IU现在位于编号为s的星球，根据来自Lao5的可靠情报，Hengzo星是编号为t的星球。她想知道有没有一种方案可以从s星出发，经过每座星球最多一次，并且收集齐所有的限定版人偶（即使用过全部的单向传送通道），最终到达t星。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行包含一个正整数T，表示有T组测试数据。<br/>
每组测试数据的第一行包含三个整数N,M,K，分别表示星球的数量，飞行路线的数量和单向传送通道的数量。<br/>
第二行包含两个整数s,t，表示出发星球和目标星球。<br/>
接下来的M行每行包含两个整数a,b，表示a星球和b星球之间有一条飞行路线。<br/>
之后有K行每行包括两个整数a,b，表示存在一条从a星球到b星球的单向传送通道。注意：从a星球到b星球可能存在多条单向传送通道，经过时赠送的限定版人偶并不同。<br/>
在学习了现代科技的基本知识之后，Logic_IU认为从0开始给星球编号有利于解决此问题，因此她这么做了。她还保证了输入数据中没有重复的飞行路线。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">对于每组测试数据，在单独的一行内输出一个字符串，若存在符合要求的方案，则输出TAK，否则输出NIE。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3 2 1<br/>
1 0<br/>
0 1<br/>
0 2<br/>
1 2<br/>
3 2 1<br/>
1 0<br/>
0 1<br/>
0 2<br/>
2 1<br/>
3 2 2<br/>
0 1<br/>
0 2<br/>
2 1<br/>
0 1<br/>
1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE<br/>
NIE<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据，保证1 ≤ N ≤ 100000,1 ≤ M ≤ 100000,0 ≤ K ≤ 100000，每条飞行路线和单向传送通道中a≠b。<br/><br/>
测试数据组数T可能很大，请注意相关操作。保证测试数据有一定梯度。<br/><br/>
样例解释<br/><br/>
在第一组样例中，Logic_IU可以先经过从1到2的传送门，再通过从2到0的飞行路线，最终到达1。<br/><br/>
注意到不能重复经过某座星球，因此第二组样例的答案是NIE。<br/><br/>
第三组样例中，我们可以注意到出发星球和目标星球也是不能重复经过的。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Adera 3 杯省选模拟赛">Adera 3 杯省选模拟赛</a></p></div>

