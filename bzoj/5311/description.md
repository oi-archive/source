
# Description

<div class="content"><div>
<div>众所周知，贞鱼是一种高智商水生动物。不过他们到了陆地上智商会减半。</div>
<div>这不？他们遇到了大麻烦！</div>
<div>n只贞鱼到陆地上乘车，现在有k辆汽车可以租用。</div>
<div>由于贞鱼们并不能在陆地上自由行走，一辆车只能载一段连续的贞鱼。</div>
<div>贞鱼们互相有着深深的怨念，每一对贞鱼之间有怨气值。</div>
<div>第i只贞鱼与第j只贞鱼的怨气值记为Y<sub>ij</sub>，且Y<sub>ij</sub>=Y<sub>ji</sub>，Y<sub>ii</sub>=0。</div>
<div>每辆车载重不限，但是每一对在同辆车中的贞鱼都会产生怨气值。</div>
<div>当然,超级贞鱼zzp长者希望怨气值的总和最小。</div>
<div>不过他智商已经减半,想不出分配方案。</div>
<div>他现在找到了你,请你帮助他分配贞鱼们,并输出最小怨气值之和ans。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数:n,k。</div>
<div>接下来读入一个n行n列的矩阵。矩阵中第i行j列的元素表示Y<sub>ij</sub>。</div>
<div>当然这个矩阵是对称的。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一个整数ans，表示：最小的怨气值之和</div>
<div>★注意：同辆车中，贞鱼i,j之间的怨气只算一次！</div>
<div>1 ≤ n ≤4000 ，1 ≤ k ≤min(n , 800) , 0 ≤ Yij≤10 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 3<br/>
0 1 1 1 1 1 1 1<br/>
1 0 1 1 1 1 1 1<br/>
1 1 0 1 1 1 1 1<br/>
1 1 1 0 1 1 1 1<br/>
1 1 1 1 0 1 1 1<br/>
1 1 1 1 1 0 1 1<br/>
1 1 1 1 1 1 0 1<br/>
1 1 1 1 1 1 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
编号为1，2，3的贞鱼一辆车：怨气值和为3；<br/>
编号为4，5，6的贞鱼一辆车：怨气值和为3；<br/>
编号为7，8的贞鱼一辆车：怨气值和为1。<br/>
最小怨气值总和为 3 + 3 + 1 = 7 。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

