
# Description

<div class="content"><div>　　定义函数H(s)其中s为一个2进制数，返回s转成字符串以后，把所有的&#34;1&#34;变成&#34;10&#34;,&#34;0&#34;变成&#34;1&#34;,比如H(&#34;1001&#34;</div>
<div>)=&#34;101110&#34;,特殊的H(&#34;&#34;)=&#34;&#34;,Hm(s)=H(H(H(...H(s))))...),即自我运算m次,H<sup>0</sup>(s)=s.输入n个数T<sub>1</sub>...T<sub>n</sub>判断H<sup><sub>T</sub></sup><sub><sup>1</sup></sub>(&#34;</div>
<div>0&#34;)H<sup>T</sup><sub><sup>2</sup></sub>(&#34;0&#34;)..H<sup>T</sup><sub><sup>n</sup></sub>(&#34;0&#34;)是否是H<sup>m</sup>(&#34;0&#34;)的子串，M为任意正整数</div></div>

# Input

<div class="content"><div>
<div>第一行正整数T(1≤T≤13)表示数据组数.</div>
<div>每组数据包括：</div>
<div>第一行n（1≤n≤100,000）</div>
<div>第二行n个非负整数T1—Tn（每组数据ΣTi不超过10^7）</div>
</div></div>

# Output

<div class="content"><p>N行，每行一个字符串TAK/NIE表示是/否。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2<br/>
1 2<br/>
2<br/>
2 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img border="0" alt="" src="/source/bzoj/1141/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNDFfMi5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

