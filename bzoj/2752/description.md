
# Description

<div class="content"><p><span style="font-size: medium">Y901高速公路是一条重要的交通纽带，政府部门建设初期的投入以及使用期间的养护费用都不低，因此政府在这条高速公路上设立了许多收费站。<br/>
Y901高速公路是一条由N-1段路以及N个收费站组成的东西向的链，我们按照由西向东的顺序将收费站依次编号为1~N，从收费站i行驶到i+1(或从i+1行驶到i)需要收取Vi的费用。高速路刚建成时所有的路段都是免费的。<br/>
政府部门根据实际情况，会不定期地对连续路段的收费标准进行调整，根据政策涨价或降价。<br/>
无聊的小A同学总喜欢研究一些稀奇古怪的问题，他开车在这条高速路上行驶时想到了这样一个问题:对于给定的l,r(l&lt;r),在第l个到第r个收费站里等概率随机取出两个不同的收费站a和b，那么从a行驶到b将期望花费多少费用呢?<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">第一行2个正整数N,M，表示有N个收费站，M次调整或询问<br/>
接下来M行，每行将出现以下两种形式中的一种<br/>
C l r v 表示将第l个收费站到第r个收费站之间的所有道路的通行费全部增加v<br/>
Q l r   表示对于给定的l,r，要求回答小A的问题<br/>
所有C与Q操作中保证1&lt;=l&lt;r&lt;=N<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">对于每次询问操作回答一行，输出一个既约分数<br/>
若答案为整数a，输出a/1<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
C 1 4 2<br/>
C 1 2 -1<br/>
Q 1 2<br/>
Q 2 4<br/>
Q 1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1/1<br/>
8/3<br/>
17/6<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模<br/><br/>
所有C操作中的v的绝对值不超过10000<br/><br/>
在任何时刻任意道路的费用均为不超过10000的非负整数<br/><br/>
所有测试点的详细情况如下表所示<br/><br/>
Test N M<br/><br/>
1 =10 =10<br/><br/>
2 =100 =100<br/><br/>
3 =1000 =1000<br/><br/>
4 =10000 =10000<br/><br/>
5 =50000 =50000<br/><br/>
6 =60000 =60000<br/><br/>
7 =70000 =70000<br/><br/>
8 =80000 =80000<br/><br/>
9 =90000 =90000<br/><br/>
10 =100000 =100000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

