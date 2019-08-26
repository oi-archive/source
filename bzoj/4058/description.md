
# Description

<div class="content"><p> 定义一种操作&#34;Bit Bang&#34;，设操作前序列为S，操作后序列为S&#39;，则有S&#39;_i = S_(i-1) xor S_(i+1)，如果S_(i-1)或S_(i+1)不存在则对应数字视为0。问对于给定的01序列A，问是否经过有限次&#34;Bit Bang&#34;操作后序列会变成全0序列。</p></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。每组数据占一行，为一个长度至少1至多200000的01序列。</p></div>

# Output

<div class="content"><div>
<div>对于每组数据输出一行，如果不能变成全0序列，输出&#34;LIVES&#34;，否则输出&#34;DIES&#34;。（不含引号）</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
01<br/>
0010100<br/>
11011</span></div>

# Sample Output

<div class="content"><span class="sampledata">LIVES<br/>
DIES<br/>
LIVES </span></div>

# Hint

<div class="content"><p></p><p> 样例一会一直01 10 01下去，样例二会很快变成全0序列(0010100 0100010 1010101 0000000)，样例三一直不会变。</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

