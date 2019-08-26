
# Description

<div class="content"><div>给定一大小为n的有点权树，每次询问一对点(u,v)，问是否能在u到v的简单路径上取三个点权，以这三个权值为边</div>
<div>长构成一个三角形。同时还支持单点修改。</div></div>

# Input

<div class="content"><div>第一行两个整数n、q表示树的点数和操作数</div>
<div>第二行n个整数表示n个点的点权</div>
<div>以下n-1行，每行2个整数a、b，表示a是b的父亲（以1为根的情况下）</div>
<div>以下q行，每行3个整数t、a、b</div>
<div>若t=0，则询问(a,b)</div>
<div>若t=1，则将点a的点权修改为b</div>
<div></div>
<div>n,q&lt;=100000，点权范围[1,2^31-1]<br/>
 </div></div>

# Output

<div class="content"><p>对每个询问输出一行表示答案，“Y”表示有解，“N”表示无解。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 3 4 5<br/>
1 2<br/>
2 3<br/>
3 4<br/>
1 5<br/>
0 1 3<br/>
0 4 5<br/>
1 1 4<br/>
0 2 5<br/>
0 2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">N<br/>
Y<br/>
Y<br/>
N<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

