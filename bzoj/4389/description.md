
# Description

<div class="content"><p>最初有一棵带点权的树。<br/>
给出下列操作：<br/>
1 x y z  在x为根的树里，y到根路径链加z<br/>
2 x y z  x~y链上点权都修改为z<br/>
3 x y    在x为根的树里，对y子树的点权求和 <br/>
4 x y    x~y链上取点权max<br/>
5 x y    x~y链上求点权和<br/>
6 x y    连接 x~y<br/>
7 x y    断开 x~y <br/>
<br/>
保证操作1~5上x和y在同一棵树上。<br/>
保证6和7操作合法（即操作前后都是森林）。</p></div>

# Input

<div class="content"><p>第一行一个数N。<br/>
第二行N个数表示最开始N个数的权值。<br/>
接下来N-1行，每行一个数xi。第i行表示xi和i+1有一条边。<br/>
接下来一个数M表示操作数。<br/>
接下来M行每行3个或4个数，形式如上。<br/>
N,M&lt;=200000<br/>
1&lt;=x,y&lt;=N<br/>
1&lt;=z&lt;=500000<br/>
一共有4组数据。不卡常数。</p></div>

# Output

<div class="content"><p>对于每一个3~5操作输出答案。<br/>
保证结果不超过long long。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 1 1 1<br/>
1 1 1 1<br/>
7<br/>
1 1 2 1<br/>
2 3 4 1<br/>
3 3 4<br/>
4 1 5<br/>
5 1 3<br/>
7 1 2<br/>
6 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=jiangshibiao&amp;&amp;gyz_gyz">jiangshibiao&amp;&amp;gyz_gyz</a></p></div>

