
# Description

<div class="content"><div><span style="font-size: medium">      小N最近在做关于树的题。今天她想了这样一道题，给定一棵N个节点的树，节点按1~N编号，一开始每个节点上的权值都是0，接下来有M个操作。第一种操作是修改，给出4个整数X,Y,A,B,对于X到Y路径上加上一个首项是A，公差是B的等差数列，因为小N十分谨慎，所以她每做完一个修改操作就会保存一次，初始状态是第0次保存的局面。第二种操作是求和，给出2个整数X,Y，输出X到Y路径上所有节点的权值和。第三种操作是读取之前第X次保存的局面，所有节点的状态回到之前第X次保存的状态。现在请你对每一个求和操作输出答案。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">      第一行2个整数N,M表示节点个数和操作次数。</span></div>
<div><span style="font-size: medium">      接下来N-1行每行2个整数Ui,Vi表示了这棵树中Ui和Vi这2个节点间有边相连。</span></div>
<div><span style="font-size: medium">      接下来M行每行先有一个字符表示了操作的类型：</span></div>
<div><span style="font-size: medium">           如果是’c’，那么代表了一个修改操作，接下来有4个整数X1,Y1,A,B，为了使得询问在线，正确的X=X1 xor上次输出的数,Y=Y1 xor上次输出的数,如果之前没有输出过那么当成0。</span></div>
<div><span style="font-size: medium">           如果是’q’，那么代表了一个求和操作，接下来有2个整数X1,Y1,和修改操作一样需要xor上次输出。</span></div>
<div><span style="font-size: medium">           如果是’l’，那么代表了一次读取操作，接下来1个整数X1，正确的X=X1 xor上次输出的数。</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">      对于每一个求和操作，输出求和后的值。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
c 2 5 2 3<br/>
c 3 4 5 10<br/>
q 1 3<br/>
l 13<br/>
q 13 15<br/>
l 6<br/>
q 6 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
7<br/>
7 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
     </span><span style="font-size: medium"><span lang="EN-US"><font face="Calibri">100%</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">的数据中</span><span lang="EN-US"><font face="Calibri">N,M&lt;=100000,0&lt;=A,B&lt;=1000,0&lt;=X1,Y1&lt;=10^1,</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">修改次数</span><span lang="EN-US"><font face="Calibri">&lt;M/2</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，不会读取没保存的局面</span></span><span lang="EN-US" style="font-size: 15pt"><o:p></o:p></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

