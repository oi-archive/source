
# Description

<div class="content"><p class="MsoNormal"></p>
<div>Bovinia设计了连接N (1 &lt; = N &lt; = 20,000)个农场的航班。对于任何航班，指定了其中的k个农场作为枢纽。 (1 &lt; = K &lt;= 200 , K &lt; = N)。</div>
<div>目前，共有M种单向航班（ 1 &lt; = M &lt; = 20,000 ），第i个航班从农场u_i至农场v_i花费d_i ( 1 &lt; = d_i &lt; =10,000 )美元。航班保证u_i或者v_i至少有一个是枢纽，任意两个农场至多只有一个航班，保证u_i≠v_i。</div>
<div>Bessie负责票务服务。共收到Q个度假请求，(1 &lt; = Q &lt; = 50,000)，其中第i个请求是从农场a_i至农场b_i 。请帮助她计算，每个请求是否满足 ，并计算：能满足的度假请求的最小费用总和。</div>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><div> 第1行：四个整数N,M,K,Q</div>
<div> 第2 - M+1行：三个整数ui,vi,di</div>
<div> 第M+2 - M+K+1行：枢纽的农场编号X (0&lt;=X&lt;=N)</div>
<div> 第M+K+2..M+K+Q+1：两个整数，度假请求ai,bi</div>
<p class="MsoNormal"></p>
<p></p></div>

# Output

<div class="content"><div>
<div>第1行：能够满足的度假请求数</div>
<div>
<div>第2行：能满足的度假请求的最小费用总和</div>
</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 1 2<br/>
1 2 10<br/>
2 3 10<br/>
2 1 5<br/>
2<br/>
1 3<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
20<br/>
【样例解释】<br/>
第1个请求，航线设计为1-&gt;2-&gt;3,费用为20<br/>
第2个请求，无法满足<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

