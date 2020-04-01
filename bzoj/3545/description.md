
# Description

<div class="content"><p><span style="font-size: medium">在Bytemountains有N座山峰，每座山峰有他的高度h_i。有些山峰之间有双向道路相连，共M条路径，每条路径有一个困难值，这个值越大表示越难走，现在有Q组询问，每组询问询问从点v开始只经过困难值小于等于x的路径所能到达的山峰中第k高的山峰，如果无解输出-1。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行三个数N，M，Q。<br/>
第二行N个数，第i个数为h_i<br/>
接下来M行，每行3个数a b c，表示从a到b有一条困难值为c的双向路径。<br/>
接下来Q行，每行三个数v x k，表示一组询问。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每组询问，输出一个整数表示答案。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 11 4<br/>
1 2 3 4 5 6 7 8 9 10<br/>
1 4 4<br/>
2 5 3<br/>
9 8 2<br/>
7 8 10<br/>
7 1 4<br/>
6 7 1<br/>
6 4 8<br/>
2 1 5<br/>
10 8 10<br/>
3 4 7<br/>
3 4 6<br/>
1 5 2<br/>
1 5 6<br/>
1 5 8<br/>
8 9 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
1<br/>
-1<br/>
8<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【数据范围】<br/><br/>
N&lt;=10^5, M,Q&lt;=5*10^5，h_i,c,x&lt;=10^9。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Sbullet">By Sbullet</a></p></div>

