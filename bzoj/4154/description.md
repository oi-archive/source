
# Description

<div class="content"><div>
<div>给定一棵以1为根的有根树,初始所有节点颜色为1,每次将距离节点a不超过l的a的子节点染成c,或询问点a的颜色</div>
<div></div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行一个数T,表示数据组数</div>
<div>接下来每组数据的第一行三个数n,c,q表示结点个数,颜色数和操作数</div>
<div>接下来一行n-1个数描述2..n的父节点</div>
<div>接下来q行每行三个数a,l,c</div>
<div>若c为0,表示询问a的颜色</div>
<div>否则将距离a不超过l的a的子节点染成c</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>设当前是第i个操作,y_i为本次询问的答案(若本次操作是一个修改则y_i为0),令z_i=i*y_i,请输出z_1+z_2+...+z_q模10^9+7</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
4 3 7<br/>
1 2 2<br/>
3 0 0<br/>
2 1 3<br/>
3 0 0<br/>
1 0 2<br/>
2 0 0<br/>
4 1 1<br/>
4 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">32</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div><br/>
<div>第1,3,5,7的询问的答案分别为1,3,3,1,所以答案为 1*1+2*0+3*3+4*0+5*3+6*0+7*1=32.</div><br/>
<div>数据范围:</div><br/>
<div>对于100%的数据T&lt;=6,n,m,c&lt;=10^5,</div><br/>
<div>1&lt;=a&lt;=n,0&lt;=l&lt;=n,0&lt;=c&lt;=c</div><br/>
</div><br/>
</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

