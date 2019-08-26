
# Description

<div class="content"><div><span style="font-size: medium">说有一个01串，去掉前导0和结尾0，那么现在有一头一尾两个1对不对……</span></div>
<div><span style="font-size: medium">如果一个1，它处于<span style="line-height: 22px">开头</span><span style="line-height: 22px">或者</span><span style="line-height: 22px">结尾</span><span style="line-height: 22px">，且不与1相邻，那么就称之为ufo……</span></span></div>
<div><span style="font-size: medium">10001010有两个ufo……10000000000011000000有一个ufo……10000001000000有两个ufo……00000100000000000只有一个ufo</span></div>
<div><span style="font-size: medium"><span style="line-height: 22px">sks(n) = 1..n这n个数的二进制表示中ufo的总个数。</span></span></div>
<div><span style="font-size: medium">sks(5) = 5, sks(256) = 249</span></div>
<div><span style="font-size: medium">现在REP(n)表示把相同的叠在一起……啥意思呢……就是</span></div>
<div><span style="font-size: medium">REP(111111000001100) = {6, 5, 2, 2}</span></div>
<div><span style="font-size: medium">代表一开始有6个1，5个0，2个1，2个0。</span></div>
<div><span style="font-size: medium">现在给你REP(n)，要你求REP(sks(n))。</span></div>
<div><span style="font-size: medium">|REP(n)| &lt;= 10^6, n &lt;= 2 ^ (10 ^ 9)</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">输入：第一行一个整数n（1&lt;=n&lt;=1000,000），第二行n个由空格隔开的整数xi（1&lt;=xi的总和&lt;=1000,000,000）用题目开头说过的方法描述了一个二进制数这个二进制数表示的整数，这个整数大于0，小于2的1000,000,000此方。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出：第一行一个整数，为描述的二进制数的数字个数，第二行用题目开头的方法输出（用空格隔开），表示这个二进制数。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 1 1 1 1 1  </span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1 1 2 1 1  </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

