
# Description

<div class="content"><div></div>
<div></div>
<div><span style="font-size: medium">Seter建造了一个很大的星球，他准备建造N个国家和无数双向道路。N个国家很快建造好了，用1..N编号，但是他发现道路实在太多了，他要一条条建简直是不可能的！于是他以如下方式建造道路：(a,b),(c,d)表示，对于任意两个国家x,y，如果a&lt;=x&lt;=b,c&lt;=y&lt;=d，那么在xy之间建造一条道路。Seter保证一条道路不会修建两次，也保证不会有一个国家与自己之间有道路。</span></div>
<div><span style="font-size: medium">Seter好不容易建好了所有道路，他现在在位于P号的首都。Seter想知道P号国家到任意一个国家最少需要经过几条道路。当然，Seter保证P号国家能到任意一个国家。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div></div>
<div>
<pre style="font-size: 13px; color: rgb(68,68,68); line-height: 18px"></pre>
</div>
<div style="clear: both; table-layout: fixed; margin: 10px 30px; overflow: auto; word-break: break-all; white-space: normal; text-align: left"><span style="color: #ff0000"><span style="font-size: medium">注意：可能有重边 </span></span></div></div>

# Input

<div class="content"><p></p>
<div></div>
<div>
<div><span style="font-size: medium">第一行三个数N,M,P。N&lt;=500000,M&lt;=100000。</span></div>
<div><span style="font-size: medium">后M行，每行4个数A，B，C，D。<span style="line-height: 1.5">1&lt;=A&lt;=B&lt;=N,</span><span style="line-height: 1.5">1&lt;=C&lt;=D&lt;=N。</span></span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div></div>
<div>
<pre style="font-size: 13px; color: rgb(68,68,68); line-height: 18px"></pre>
</div>
</div></div>

# Output

<div class="content"><p></p>
<div></div>
<div>
<div><span style="font-size: medium">N行，第i行表示P号国家到第i个国家最少需要经过几条路。显然第P行应该是0。</span></div>
<div><span style="font-size: medium"><br/>
</span></div>
<div>
<h2 style="color: rgb(68,68,68); line-height: 18px; font-family: Tahoma, Arial"></h2>
<pre style="font-size: 13px; color: rgb(68,68,68); line-height: 18px"></pre>
</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 4<br/>
1 2 4 5<br/>
5 5 4 4<br/>
1 1 3 3<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
2<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=seter翻译">seter翻译</a></p></div>

