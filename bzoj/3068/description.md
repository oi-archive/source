
# Description

<div class="content"><p><span style="font-size: medium">背景：<br/>
  小白家门前有一颗小白树，树上的每个节点u都有一个权值W(u)。<br/>
  小白树的奇特之处在于树上有两个不同的中心点x和y。<br/>
  这两个中心点满足F(x,y)=ΣMin(Dis(u,x),Dis(u,y))*W(u)最小，其中Dis表示两个节点的距离。<br/>
  通俗地讲，就是对于每个节点u，求出G(u)表示它到x的距离和到y的距离中间小的那个乘以它的权值。<br/>
  那么所有G(u)的和就是F(x,y)。<br/>
  现在小白想让你找出这两个中心点。你只需要输出F(x,y)就可以了。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">  第一行有一个整数N(2&lt;=N&lt;=500000)N表示小白树的节点个数。<br/>
  之后N-1行每行有两个整数a和b表示a和b之间有一条边。<br/>
  之后N行每行有一个整数，第i个整数表示W(i)(0&lt;=W&lt;=10000)。<br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">  一个整数表示F(x,y)。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">  5<br/>
  1 2<br/>
  1 3<br/>
  3 4<br/>
  3 5<br/>
  5<br/>
  7<br/>
  6<br/>
  5<br/>
  4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">  14</span></div>

# Hint

<div class="content"><p></p><p>总共10个测试点<br/><br/>
2&lt;=n&lt;=500000 0&lt;=w&lt;=10000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Martin">By Martin</a></p></div>

