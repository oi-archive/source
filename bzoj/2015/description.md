
# Description

<div class="content"><p><span style="font-size: medium">Farmer John有B头奶牛(1&lt;=B&lt;=25000)，有N(2*B&lt;=N&lt;=50000)个农场，编号1-N，有M(N-1&lt;=M&lt;=100000)条双向边，第i条边连接农场R_i和S_i(1&lt;=R_i&lt;=N;1&lt;=S_i&lt;=N)，该边的长度是L_i(1&lt;=L_i&lt;=2000)。</span><span style="font-size: medium">居住在农场P_i的奶牛A(1&lt;=P_i&lt;=N)，它想送一份新年礼物给居住在农场Q_i(1&lt;=Q_i&lt;=N)的奶牛B，但是奶牛A必须先到FJ(居住在编号1的农场)那里取礼物，然后再送给奶牛B。你的任务是：奶牛A至少需要走多远的路程？</span></p>
<p><span style="font-size: medium"> </span><wbr/></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">　　第1行：三个整数：N,M,B。</span></p>
<p><span style="font-size: medium">   　第2..M+1行：每行三个整数：R_i,S_i和L_i，描述一条边的信息。</span></p>
<p><span style="font-size: medium">　　第M+2..M+B+1行：共B行，每行两个整数P_i和Q_i，表示住在P_i农场的奶牛送礼物给住在Q_i农场的奶牛。</span></p>
<p><span style="font-size: medium">　　</span></p></div>

# Output

<div class="content"><p><wbr/></p>
<p><span style="font-size: medium">　　样例输出：</span></p>
<p><span style="font-size: medium">　　共B行，每行一个整数，表示住在P_i农场的奶牛送礼给住在Q_i农场的奶牛至少需要走的路程</span></p>
<p><span style="font-size: medium">　</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 7 3<br/>
<br/>
　　1 2 3<br/>
<br/>
　　5 4 3<br/>
<br/>
　　3 1 1<br/>
<br/>
　　6 1 9<br/>
<br/>
　　3 4 2<br/>
<br/>
　　1 4 4<br/>
<br/>
　　3 2 2<br/>
<br/>
　　2 4<br/>
<br/>
　　5 1<br/>
<br/>
　　3 6<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">　6<br/>
<br/>
　6<br/>
<br/>
  10<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

