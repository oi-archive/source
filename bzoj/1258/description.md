
# Description

<div class="content"><div>画一个等边三角形，把三边的中点连接起来，得到四个三角形，把它们称为T1,T2,T3,T4，如图1。把前三个三角形</div>
<div>也这样划分，得到12个更小的三角形：T11,T12,T13,T14,T21,T22,T23,T24,T31,T32,T33,T34，如图2。把编号以1</div>
<div>，2，3结尾的三角形又继续划分…最后得到的分形称为Sierpinski三角形。</div>
<p> <img border="0" src="/source/bzoj/1258/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEyNTguanBn.jpg" alt=""/> </p>
<div>如果B不包含A，且A的某一条完整的边是B的某条边的一部分，则我们说A靠在B的边上。例如T12靠在T24和T4上，但</div>
<div>不靠在T32上。给出Spierpinski三角形中的一个三角形，找出它靠着的所有三角形。</div></div>

# Input

<div class="content"><div>输入仅一行，即三角形的编号，以T开头，后面有n个1到4的数字。仅最后一个数字可能为4。</div>
<div>1&lt;=n&lt;=50</div></div>

# Output

<div class="content"><p>输出每行一个三角形编号，按字典序从小到大排列。</p></div>

# Sample Input

<div class="content"><span class="sampledata">T312</span></div>

# Sample Output

<div class="content"><span class="sampledata">T314<br/>
T34<br/>
T4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

