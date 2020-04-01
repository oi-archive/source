
# Description

<div class="content"><p style="background: white; line-height: 13.5pt"><span style="font-size: medium;"><span lang="EN-US" style="color: rgb(68, 68, 68); font-family: Tahoma;">Byteasar lives in Byteburg, a city famous for its milk bars on every corner. One day Byteasar came up with an idea of a &#34;milk multidrink&#34;: he wants to visit each milk bar for a drink exactly once. Ideally, Byteasar would like to come up with a route such that the next bar is always no further than two blocks (precisely: intersections) away from the previous one.</span></span><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体"><font size="3"><o:p></o:p></font></span></p>
<p style="background: white; line-height: 13.5pt"><span style="font-size: medium;"><span lang="EN-US" style="color: rgb(68, 68, 68); font-family: Tahoma;">The intersections in Byteburg are numbered from<span class="apple-converted-space"> </span>1<span class="apple-converted-space"> </span>to<span class="apple-converted-space"> </span>N, and all the streets are bidirectional. Between each pair of intersections there is a unique direct route, ie, one that does not visit any intersection twice. Byteasar begins at the intersection no.<span class="apple-converted-space"> </span>1<span class="apple-converted-space"> </span>and finishes at the intersection no.<span class="apple-converted-space"> </span>N.</span></span><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体"><font size="3"><o:p></o:p></font></span></p>
<p style="background: white; line-height: 13.5pt"><span style="font-size: medium;"><span lang="EN-US" style="color: rgb(68, 68, 68); font-family: Tahoma;">Your task is to find any route that satisfies Byteasar&#39;s requirements if such a route exists.</span></span><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体"><font size="3"><o:p></o:p></font></span></p>
<p><span style="font-size: medium;"> <img width="392" height="531" src="/source/bzoj/3424/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS9mZigyKS5qcGc=.jpg" alt=""/></span></p>
<pre><span style="font-size: medium;">给一棵树，输出遍历序列a[]，要求每个节点被访问到到恰好一次  要求从1号节点出发，结束在n号节点 要求对于所有i,a[i]与a[i+1]的距离 小于等于2 </span></pre>
<p><span style="font-size: medium;"><br/>
</span></p></div>

# Input

<div class="content"><p style="background: white; line-height: 13.5pt"><span style="font-size: medium"><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体">In the first line of the standard input there is a single integer<span class="apple-converted-space"> </span>N(2&lt;=N&lt;=500000)<span class="apple-converted-space"> </span>, denoting the number of intersections in Byteburg. Each of the following<span class="apple-converted-space"> </span>N-1<span class="apple-converted-space"> </span>lines holds a pair of distinct integers<span class="apple-converted-space"> </span>Ai<span class="apple-converted-space"> </span>and<span class="apple-converted-space"> </span>Bi(1&lt;=Ai,Bi&lt;=N)<span class="apple-converted-space"> </span> separated by a single space, that represent the street linking the intersections no.<span class="apple-converted-space"> </span>Ai<span class="apple-converted-space"> </span>and<span class="apple-converted-space"> </span>Bi.</span></span><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体"><font size="3"><o:p></o:p></font></span></p></div>

# Output

<div class="content"><p style="background: white; line-height: 15.05pt"><span style="font-size: medium"><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体">If there is no route satisfying Byteasar&#39;s requirements, your program should print a single word &#34;</span><tt><span lang="EN-US" style="color: #444444"><font face="宋体">BRAK</font></span></tt><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体">&#34; (Polish for<span class="apple-converted-space"> </span><i>none</i>), without the quotation marks to the standard output. Otherwise, your program should print<span class="apple-converted-space"> </span>N<span class="apple-converted-space"> </span>lines to the standard output, the i-th of which should contain the number of the<span class="apple-converted-space"> </span>i-th intersection on an arbitrary route satisfying Byteasar&#39;s requirements. Obviously, in that case the first line should hold the number<span class="apple-converted-space"> </span>1, and the<span class="apple-converted-space"> </span>N-th line - number<span class="apple-converted-space"> </span>N.</span></span><font size="3"><span lang="EN-US" style="color: #444444; font-family: Tahoma; mso-bidi-font-family: 宋体"><o:p></o:p></span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">12<br/>
1 7<br/>
7 8<br/>
7 11<br/>
7 2<br/>
2 4<br/>
4 10<br/>
2 5<br/>
5 9<br/>
2 6<br/>
3 6<br/>
3 12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
11<br/>
8<br/>
7<br/>
4<br/>
10<br/>
2<br/>
9<br/>
5<br/>
6<br/>
3<br/>
12<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Wcmg提供SPJ 译文">鸣谢Wcmg提供SPJ 译文</a></p></div>

