
# Description

<div class="content"><div>BESSIE准备用从牛棚跑到池塘的方法来锻炼. 但是因为她懒,她只准备沿着下坡的路跑到池塘, 然后走回牛棚. BES</div>
<div>SIE也不想跑得太远,所以她想走最短的路经. 农场上一共有M (1 &lt;= M &lt;= 10,000)条路, 每条路连接两个用1..N(1</div>
<div> &lt;= N &lt;= 1000)标号的地点. 更方便的是,如果X&gt;Y,则地点X的高度大于地点Y的高度. 地点N是BESSIE的牛棚;地点1</div>
<div>是池塘. 很快, BESSIE厌倦了一直走同一条路.所以她想走不同的路,更明确地讲,她想找出K (1 &lt;= K &lt;= 100)条不</div>
<div>同的路经.为了避免过度劳累,她想使这K条路经为最短的K条路经. 请帮助BESSIE找出这K条最短路经的长度.你的程</div>
<div>序需要读入农场的地图, 一些从X_i到Y_i 的路经和它们的长度(X_i, Y_i, D_i). 所有(X_i, Y_i, D_i)满足(1 &lt;=</div>
<div> Y_i &lt; X_i; Y_i &lt; X_i &lt;= N, 1 &lt;= D_i &lt;= 1,000,000).</div></div>

# Input

<div class="content"><div>* 第1行: 3个数: N, M, 和K</div>
<div>* 第 2..M+1行: 第 i+1 行包含3个数 X_i, Y_i, 和 D_i, 表示一条下坡的路.</div></div>

# Output

<div class="content"><div>* 第1..K行: 第i行包含第i最短路经的长度,或-1如果这样的路经不存在.</div>
<div>如果多条路经有同样的长度,请注意将这些长度逐一列出.</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 8 7<br/>
5 4 1<br/>
5 3 1<br/>
5 2 1<br/>
5 1 1<br/>
4 3 4<br/>
3 1 1<br/>
3 2 1<br/>
2 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
2<br/>
3<br/>
6<br/>
7<br/>
-1<br/>
输出解释:<br/>
路经分别为(5-1), (5-3-1), (5-2-1), (5-3-2-1), (5-4-3-1),<br/>
(5-4-3-2-1).</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

