
# Description

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">The Byteotian Cave is composed of  n chambers and n-1 corridors that connect them. For every pair of chambers there is unique way to move from one of them to another without leaving the cave. Dynamite charges are set up in certain chambers. A fuse is laid along every corridor. In every chamber the fuses from the adjacent corridors meet at one point, and are further connected to the dynamite charge if there is one in the chamber. It takes exactly one unit of time for the fuse between two neighbouring chambers to burn, and the dynamite charge explodes in the instant that fire reaches the chamber it is inside. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">We would like to light the fuses in some m chambers (at the joints of fuses) in such a way that all the dynamite charges explode in the shortest time possible since the fuses are lit. Write a program that will determine the minimum such time possible. </span></span></div>
<div style="line-height: 140%" align="left"></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium">Byteotian Cave的结构是一棵N个节点的树，其中某些点上面已经安置了炸药，现在需要点燃M个点上的引线引爆所有的炸药。</span></div>
<p></p>
<pre style="font-family: arial, verdana, helvetica, sans-serif! important"><span style="font-size: medium">某个点上的引线被点燃后的1单位时间内，在树上和它相邻的点的引线会被点燃。如果一个有炸药的点的引信被点燃，那么这个点上的炸药会爆炸。
求引爆所有炸药的最短时间。

输入：
第一行是两个整数N,M。(1&lt;=m&lt;=n&lt;=300000）
接下来一行有N个整数Di，第I个数为1表示该点有炸药。
接下来N-1行每行有两个数A,B，表示A和B之间有一条边。
输出：
最短时间。
样例解释： 
点燃3,5上的引线。<br/><br/></span></pre></div>

# Input

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">The first line of the standard input holds two integers n and m (1&lt;=M&lt;=N&lt;=300000)</span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">, separated by a single space, that denote, respectively, the number of chambers in the cave and the number of chambers in which fire can be set to the fuses. The chambers are numbered from 1 to n . The next line contains  n integers d1,d2…dn (Di</span><span style="color: #444444; line-height: 140%">属于</span><span style="color: #444444; line-height: 140%">{0,1}, separated by single spaces. If Di=1 , then there is dynamite in the -th chamber, and if di=0 , there is none. The following n -1 lines specify the corridors of the cave. Each of them holds two integers a,b (a&lt;=a&lt;b&lt;=n), separated by a single space, denoting that there is a corridor connecting the chambers a and b . Every corridor appears exactly once in the description. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">You may assume that in tests worth 10% of the points it holds additionally that n&lt;= 10, while in tests worth 40% of the points it holds that N&lt;=1000. </span></span></div></div>

# Output

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">The first and only line of the standard output should hold a single integer, equal to the minimum time it takes from lighting the fuses to the explosion of all the charges. </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 2<br/>
1 0 1 1 0 1 1<br/>
1 3<br/>
2 3<br/>
3 4<br/>
4 5<br/>
5 6<br/>
5 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 Object022">鸣谢 Object022</a></p></div>

