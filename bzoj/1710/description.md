
# Description

<div class="content"><p><span style="font-size: medium">为了跟踪所有的牛,农夫JOHN在农场上装了一套自动系统. 他给了每一个头牛一个电子牌号 当牛走过这个系统时,牛的名字将被自动读入. 每一头牛的电子名字是一个长度为M (1 &lt;= M &lt;= 2,000) 由N (1 &lt;= N &lt;= 26) 个不同字母构成的字符串.很快,淘气的牛找到了系统的漏洞:它们可以倒着走过读 码器. 一头名字为&#34;abcba&#34;不会导致任何问题,但是名为&#34;abcb&#34;的牛会变成两头牛(&#34;abcb&#34; 和 &#34;bcba&#34;).农 夫JOHN想改变牛的名字,使得牛的名字正读和反读都一样.例如,&#34;abcb&#34;可以由在尾部添加&#34;a&#34;.别的方法包 括在头上添加&#34;bcb&#34;,得到&#34;bcbabcb&#34;或去掉&#34;a&#34;,得到&#34;bcb&#34;.JOHN可以在任意位置添加或删除字母.因为名字 是电子的,添加和删除字母都会有一定费用.添加和删除每一个字母都有一定的费用(0 &lt;= 费用 &lt;= 10,000). 对与一个牛的名字和所有添加或删除字母的费用,找出修改名字的最小的费用.空字符串也是一个合法的名字. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第一行: 两个用空格分开的数, N 和 M. </span></p>
<p><span style="font-size: medium">* 第二行: M个自符,初始的牛的名字. </span></p>
<p><span style="font-size: medium">* 第3...N+2行: 每行含有一个字母和两个整数,分别是添加和删除这个字母的费用.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个整数, 改变现有名字的最小费用. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 4<br/>
abcb<br/>
a 1000 1100<br/>
b 350 700<br/>
c 200 800<br/>
输入解释:<br/>
名字是 &#34;abcb&#34;, 操作费用如下:<br/>
<br/>
    添加   删除<br/>
a  1000   1100<br/>
b   350    700<br/>
c   200    800<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
900<br/>
输出解释:<br/>
在尾部添加&#34;a&#34;得到&#34;abcba&#34;的费用为1000. 删除头上的&#34;a&#34;,得到&#34;bcb&#34;的费用为1100.在头上添加&#34;bcb&#34;可以得到最小费用,350+200+350=900.<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

