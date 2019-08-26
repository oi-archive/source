
# Description

<div class="content"><p><span style="font-size: medium">　一棵n个点的树，每个点的初始权值为1。对于这棵树有q个操作，每个操作为以下四种操作之一：<br/>
+ u v c：将u到v的路径上的点的权值都加上自然数c；<br/>
- u1 v1 u2 v2：将树中原有的边(u1,v1)删除，加入一条新边(u2,v2)，保证操作完之后仍然是一棵树；<br/>
* u v c：将u到v的路径上的点的权值都乘上自然数c；<br/>
/ u v：询问u到v的路径上的点的权值和，求出答案对于51061的余数。<br/>
</span></p>
<div class="pdcont"></div></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　第一行两个整数n，q<br/>
接下来n-1行每行两个正整数u，v，描述这棵树<br/>
接下来q行，每行描述一个操作<br/>
</span></div>
<div class="pdcont"></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　对于每个/对应的答案输出一行<br/>
</span></div>
<div class="pddata"></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
1 2<br/>
2 3<br/>
* 1 3 4<br/>
/ 1 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模和约定<br/><br/>
10%的数据保证，1&lt;=n，q&lt;=2000<br/><br/>
另外15%的数据保证，1&lt;=n，q&lt;=5*10^4，没有-操作，并且初始树为一条链<br/><br/>
另外35%的数据保证，1&lt;=n，q&lt;=5*10^4，没有-操作<br/><br/>
100%的数据保证，1&lt;=n，q&lt;=10^5，0&lt;=c&lt;=10^4</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

