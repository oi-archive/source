
# Description

<div class="content"><div>给定三个字符串a,b,c，它们的字符集均为小写字母，即a,b,c…z。</div>
<div>另F0=a，F1=b，，．，Fi=Fi-1+Fi-2(i &lt;= 2)</div>
<div>其中十表示字符串的连接</div>
<div>现在有q个询问，每次询问给定n，l,r,L，R，求在Fn的第l个到第r个字符组</div>
<div>成的字符串中，s的第L个字符到第R个字符组成的字符串的出现次数。</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个字符串a</div>
<div>第二行一个字符串b</div>
<div>第三行一个字符串s</div>
<div>第四行一个正整数q</div>
<div>下接q行，每行五个数：n，l，r，L，R，表示询问</div>
<div></div>
<div>
<div>1&lt;= |Fn|≤ 10^9,  I &lt; l &lt;=r&lt;=|Fn|,  1≤ L≤ R&lt;=|S|</div>
<div>1&lt;=|a|,|b|,|S|&lt;=10^4,1&lt;=Q&lt;=10000</div>
</div>
<div></div></div>

# Output

<div class="content"><div>共q行，每行对应一个询问的答案</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">a<br/>
b<br/>
bb<br/>
4<br/>
4 1 5 1 2<br/>
4 1 1 1 2<br/>
4 2 4 1 1<br/>
6 1 13 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
2<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

