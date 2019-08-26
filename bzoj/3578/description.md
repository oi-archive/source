
# Description

<div class="content"><p><span style="font-size: medium">  GTY召唤了n个人来做实验，GTY家的房子很大，有m个房间一开始所有人都在1号房间里，GTY会命令某人去某个房间等待做实验，或者命令一段区间的房间开始实验，实验会获得一些实验信息点数，点数为房间里的人数，如果一个房间里的一群人已经做过实验了那么这些人将不会增加实验信息点数(不会增加是针对这一群人的，不是对这群人中的每个人，即1,2,3做了实验，1,2再做实验还会增加2点实验点数)<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行两个整数n,m,q(n,m,q&lt;=10^5)表示人数，房间数和操作数<br/>
接下来q行每行一个操作 &#34;C i j&#34;表示让第i个人去房间j &#34;W l r&#34; 表示让区间[l,r]的房间做实验<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">对于每一个W操作，输出一个数，表示此次操作所获得的实验点数<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 7<br/>
C 1 2<br/>
C 2 2<br/>
W 1 2<br/>
C 3 2<br/>
W 1 2<br/>
C 3 3<br/>
W 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">善用STL<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By orzpzmaimeng">By orzpzmaimeng</a></p></div>

