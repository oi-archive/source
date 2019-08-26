
# Description

<div class="content"><div>
<div>Bessie有了一套新的做牌技术，M张牌被Bessie洗牌后，第i张牌会跑到p[i]的位置。现有N张牌从1..N编号，称为卡组。Bessie从卡组取前M张进行一次洗牌，然后将最上面的牌面朝下放置到一边的牌堆，剩下的牌面朝下放回卡组。重复此过程直至卡组剩下M-1张牌。接着Bessie将这M-1张牌逐一面朝下放到牌堆中。接下来有Q个询问，问第x[Q]张牌的编号。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>
<div>第1行N, M, Q (2&lt;=M &lt;= N, 1&lt;=Q &lt;= 5,000)</div>
<div>接下来M行，每行一个p[i]</div>
<div>接下来Q行，每行是一个x[i]， 表示一个询问</div>
</div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每一个询问的编号</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 5<br/>
3<br/>
1<br/>
2<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
5<br/>
3<br/>
1<br/>
2<br/>
<br/>
OUTPUT DETAILS:<br/>
The shuffle proceeds as:<br/>
[1, 2, 3, 4, 5] -&gt; [2, 3, 1, 4, 5] (put 2 face down)<br/>
[3, 1, 4, 5] -&gt; [1, 4, 3, 5] (put 1 face down)<br/>
[4, 3, 5] -&gt; [3, 5, 4] (put 3 face down)<br/>
[5, 4] (put 5 face down)<br/>
[4] (put 4 face down)<br/>
This produces the final order of [4, 5, 3, 1, 2]<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 100% 数据，N &lt;= 1,000,000,000, M&lt;=100,000</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

