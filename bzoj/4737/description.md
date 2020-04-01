
# Description

<div class="content"><p> 组合数C(n,m)表示的是从n个物品中选出m个物品的方案数。举个例子，从(1,2,3)三个物品中选择两个物品可以有(</p>
<div>1,2),(1,3),(2,3)这三种选择方法。根据组合数的定义，我们可以给出计算组合数C(n,m)的一般公式：</div>
<div>C(n,m)=n!/m!*(n?m)!</div>
<div>其中n!=1×2×?×n。（额外的，当n=0时，n!=1）</div>
<div>小葱想知道如果给定n,m和k，对于所有的0≤i≤n，0≤j≤min(i,m)有多少对(i,j)满足C(i,j)是k的倍数。</div>
<div></div></div>

# Input

<div class="content"><div>第一行有两个整数t,k，其中t代表该测试点总共有多少组测试数据，k的意义见。</div>
<div>接下来t行每行两个整数n,m，其中n,m的意义见。</div>
<div></div></div>

# Output

<div class="content"><p> t行，每行一个整数代表所有的0≤i≤n，0≤j≤min(i,m)中有多少对(i,j))满足C(i,j)是k的倍数</p>
<div>答案对10^9+7取模。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 23<br/>
23333333 23333333<br/>
233333333 233333333<br/>
2333333333 2333333333</span></div>

# Sample Output

<div class="content"><span class="sampledata">851883128<br/>
959557926<br/>
680723120</span></div>

# Hint

<div class="content"><p></p><p> 1≤n,m≤10^18，1≤t,k≤100，且 k 是一个质数</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

