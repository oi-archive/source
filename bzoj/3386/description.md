
# Description

<div class="content"><div><span style="font-size: medium">贝茜在谷仓外的农场上，她想回到谷仓，在第二天早晨农夫约翰叫她起来挤奶之前尽可能多地睡上一觉．由于需要睡个好觉，贝茜必须尽快回到谷仓．农夫约翰的农场上有N(2≤N≤1000)个路标，每一个路标都有唯一的编号（1到N）．路标1是谷仓，路标N是贝茜一整天呆在那里的果树园．农场的所有路标之间共有T(1≤T≤2000)条不同长度的供奶牛走的无向小路．贝茜对她识别方向的能力不是很自信，所以她每次总是从一条小路的头走到尾，再以这条路的尾作为下一条路的头开始走．  现给出所有路标之间的小路，要求输出贝茜回到谷仓的最短路程（每组输入数据都保证有解）．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第1行：2个整数T和N．</span></div>
<div><span style="font-size: medium">第2到T+1行：每行用空格隔开的三个整数描述一条小路．前两个整数是这条小路的尾和头，</span></div>
<div><span style="font-size: medium">第三个整数是这条小路的长度（不大于100）．</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">一个整数，表示贝茜从路标N到路标1所经过的最短路程</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 20<br/>
2 3 30<br/>
3 4 20<br/>
4 5 20<br/>
1 5 100</span></div>

# Sample Output

<div class="content"><span class="sampledata">90<br/>
//共有5个路标，贝茜可以依次经过路标4，3，2，1到家</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

