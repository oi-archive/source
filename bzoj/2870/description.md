
# Description

<div class="content"><div><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">H城很大，有N个路口（从1到N编号），路口之间有N-1边，使得任意两个路口都能互相到达，这些道路的长度我们视作一样。每个路口都有很多车辆来往，所以每个路口i都有一个拥挤程度v[i]，我们认为从路口s走到路口t的痛苦程度为s到t的路径上拥挤程度的最小值，乘上这条路径上的路口个数所得的积。现在请你求出痛苦程度最大的一条路径，你只需输出这个痛苦程度。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">简化版描述：</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">给定一棵N个点的树，求树上一条链使得链的长度乘链上所有点中的最小权值所得的积最大。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">其中链长度定义为链上点的个数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行N</span></div>
<div><span style="font-size: medium">第二行N个数分别表示1~N的点权v[i]</span></div>
<div><span style="font-size: medium">接下来N-1行每行两个数x、y，表示一条连接x和y的边</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">一个数，表示最大的痛苦程度。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
5 3 5<br/>
1 2<br/>
1 3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
 <br/>
【样例解释】<br/>
选择从1到3的路径，痛苦程度为min(5,5)*2=10<br/>
 </span></div>

# Hint

<div class="content"><p></p><p>100%的数据n&lt;=50000<br/><br/>
其中有20%的数据树退化成一条链<br/><br/>
所有数据点权&lt;=65536<br/><br/>
Hint：建议答案使用64位整型</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

