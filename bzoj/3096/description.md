
# Description

<div class="content"><p><span style="font-size: medium">一个无限大的边长为1的网格地图上一开始有一个跳棋在(0,0),要跳到(Tx,Ty)。每次在x方向的位移量为[0,Mx], 每次在y方向的位移量为[0,My]，每次必须移动，不能留在原位置上。现在想知道通过R次跳到目标的方案数。限制条件是：给定n个数字bi，要求每次跳的向量不能为(bi,bi)。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行六个整数Tx,Ty,Mx,My,R,n<br/>
第二行n个整数为bi </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个整数为方案数mod 10007（质数）后的值</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 1 1 2 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 1<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模<br/><br/>
100%的数据保证1&lt;=Tx,Ty,Mx,My&lt;=800,1&lt;=R&lt;=1600,0&lt;=n&lt;=50，输入数据保证每个bi都是10的倍数，1&lt;=bi&lt;=min(Mx,My)，且bi各不相同。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

