
# Description

<div class="content"><p>给你N个点的无向图 (1 &lt;= N &lt;= 15,000)，记为：1…N。 <br/>
图中有M条边 (1 &lt;= M &lt;= 30,000) ，第j条边的长度为： d_j ( 1 &lt; = d_j &lt; = 1,000,000,000).</p>
<p>现在有 K个询问 (1 &lt; = K &lt; = 20,000)。 <br/>
每个询问的格式是：A B，表示询问从A点走到B点的所有路径中，最长的边最小值是多少？</p></div>

# Input

<div class="content"><p>第一行： N, M, K。 <br/>
第2..M+1行: 三个正整数：X, Y, and D (1 &lt;= X &lt;=N; 1 &lt;= Y &lt;= N). 表示X与Y之间有一条长度为D的边。 <br/>
第M+2..M+K+1行: 每行两个整数A B,表示询问从A点走到B点的所有路径中，最长的边最小值是多少？</p></div>

# Output

<div class="content"><p> 对每个询问，输出最长的边最小值是多少。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6 8<br/>
1 2 5<br/>
2 3 4<br/>
3 4 3<br/>
1 4 8<br/>
2 5 7<br/>
4 6 2<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
2 4<br/>
5 1<br/>
6 2<br/>
6 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
5<br/>
5<br/>
4<br/>
4<br/>
7<br/>
4<br/>
5</span></div>

# Hint

<div class="content"><p></p><p>1 &lt;= N &lt;= 15,000 <br/><br/>
1 &lt;= M &lt;= 30,000 <br/><br/>
1 &lt;= d_j &lt;= 1,000,000,000 <br/><br/>
1 &lt;= K &lt;= 15,000 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

