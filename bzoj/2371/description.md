
# Description

<div class="content"><div style="text-indent: 21pt" align="left"><span style="color: black">一栋高F层的楼（每层按高度从1到F编号），你有很多个一模一样的鹰蛋。已知，如果某个鹰蛋从第i层摔下时会摔碎，则所有的蛋从j(j&gt;=i)层摔下时都会摔碎；同样的，如果某个鹰蛋从第i层摔下时不会摔碎，则所有的蛋从j(j&lt;=i)层摔下时都不会摔碎。</span></div>
<div style="text-indent: 21pt" align="left"><span style="color: black">现在定义Solvable(F,D,B)表示是否存在一种策略，使得你可以在实验不超过D次（摔一次蛋算一次实验），摔碎不超过B只鹰蛋的前提下，判断出这些鹰蛋从这栋高F的楼的每层摔下去时是否会摔碎。</span></div>
<div align="left"><b><span style="font-size: 12pt; color: black">Your Task</span></b></div>
<div style="text-indent: 21pt" align="left"><span style="color: black">给定F D B满足Solvable(F,D,B)，求最大的FF满足Solvable(FF,D,B)（若</span><span style="color: black">则返回-1），最小的DD满足Solvable(F,DD,B)，最小的BB满足Solvable(F,D,BB)。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt" align="left"><span style="color: black">第一行T表示数据组数</span></div>
<div style="text-indent: 21pt" align="left"><span style="color: black">对于每组数据，一行中F D B</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt" align="left"><span style="color: black">对于每组数据，在一行中输出FF DD BB</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3 3<br/>
7 5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7 2 1<br/>
25 3 2<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据约定<br/><br/>
100%：T&lt;=10,1&lt;=F,D,B&lt;=2*10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

