
# Description

<div class="content"><p>S航空公司在N座城市之间有N-1条航线，航线是双向的。任意两座城市都是可以互相到达的，但是可能需要在一些城市换乘不同的航线。</p>
<p>目前有人抱怨要到达有些城市需要换乘太多次，S航空公司为了缓解这一现状，决定取消目前的一条航线，添加另一条航线，在保证任意两座城市还是可以互相到达的前提下，使得两座城市之间需要乘坐的航线次数的最大值最小。</p></div>

# Input

<div class="content"><p></p>
<p>第一行为一个整数N（4&lt;=N&lt;=2500），表示城市的个数。城市从1到N编号。</p>
<p>接下来N-1行，每行是一对整数a和b，表示一条连接a和b的航线（1&lt;=a,b&lt;=N）。</p>
<p></p></div>

# Output

<div class="content"><p>输出仅一行，即航空公司进行调整后，任意两座城市之间需要乘坐的航班次数的最大值。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
4<br/>
<br/>
1 2<br/>
<br/>
2 3<br/>
<br/>
3 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
2<br/>
<br/>
【样例解释】<br/>
<br/>
取消3-4的航线，添加2-4的航线。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N&lt;=2500。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

