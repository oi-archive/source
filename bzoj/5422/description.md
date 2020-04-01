
# Description

<div class="content"><div>小焰焰有N个妹纸，编号为1~n。N个妹纸的家之间由N-1条双向道路连接，且任意两个妹纸家可以互相到达。为了后</div>
<div>宫和谐，小焰焰每次都会选择两个妹纸一起玩耍，小焰焰对每一个妹纸有一个喜爱程度xi，每次玩耍小焰焰获得的</div>
<div>愉悦值可以通过公式min(xi,xj)*dis(I,j)计算.  dis(I,j)表示妹纸I和妹纸j之间的路径长度。由于这个世界充满</div>
<div>了可能性，所以小焰焰对妹纸的喜爱程度以及城市道路的长度都有可能发生改变，小焰焰希望计算出每次他能获得</div>
<div>的最大愉悦值，但是他忙于泡新的妹纸无暇编程解决这一问题，于是他把这个问题交给了你。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n、m，分别表示妹纸数和操作数。</div>
<div>第二行n个整数，第i个整数xi表示小焰焰对妹纸xi的喜爱程度</div>
<div>接下来n-1行，每行三个整数ai、bi、ci，表示妹纸ai和妹纸bi间有一条ci的道路。</div>
<div>接下来m行，每行是如下格式的一种</div>
<div>1：A ai bi t：表示妹纸ai到妹纸bi的路径上每一条道路加上t </div>
<div>2：C p x：表示妹纸p的喜爱程度改为x</div>
<div>3：Q：表示询问当前小焰焰当前选择两个妹纸所能获得的最大愉悦值（见题目描述）</div>
<div>n&lt;=3000，m&lt;=100000，询问数小于等于50</div>
<div>1&lt;=ai、bi、p&lt;=n，1&lt;=x、ci&lt;=10000，|t|&lt;=10000，数据保证任何时刻道路长度大于0</div>
<p></p></div>

# Output

<div class="content"><div>对于每一个Q，输出一个整数为最大愉悦值</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2 3<br/>
1 3 3<br/>
2 3 2<br/>
Q<br/>
C 2 3<br/>
Q<br/>
A 1 3 2<br/>
Q</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
6<br/>
7<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

