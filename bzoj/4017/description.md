
# Description

<div class="content"><div>背景</div>
<div></div>
<div>小Q学习位运算时发现了异或的秘密。</div>
<div></div>
<div>描述</div>
<div></div>
<div>小Q是一个热爱学习的人，他经常去维基百科（http://en.wikipedia.org/wiki/Main_Page）学习计算机科学。</div>
<div></div>
<div>就在刚才，小Q认真地学习了一系列位运算符（http://en.wikipedia.org/wiki/Bitwise_operation），其中按位异或的运算符 xor 对他影响很大。按位异或的运算符是双目运算符。按位异或具有交换律，即i xor j = j xor i。</div>
<div></div>
<div>他发现，按位异或可以理解成被运算的数字的二进制位对应位如果相同，则结果的该位置为0，否则为1，例如1(01) xor 2(10) = 3(11)。</div>
<div></div>
<div>他还发现，按位异或可以理解成数字的每个二进制位进行了不进位的加法，例如3(11) xor 3(11) = 0(00)。</div>
<div></div>
<div>于是他想到了两个关于异或的问题，这两个问题基于一个给定的非负整数序列A1, A2, ..., An，其中n是该序列的长度。</div>
<div></div>
<div>第一个问题是，如果用f(i, j)表示Ai xor Ai+1 xor ... xor Aj，则任意的1 &lt;= i &lt;= j &lt;= n的f(i, j)相加是多少。</div>
<div></div>
<div>第二个问题是，如果用g(i, j)表示Ai + Ai+1 + ... + Aj，则任意的1 &lt;= i &lt;= j &lt;= n的g(i, j)异或在一起是多少。</div>
<div></div>
<div>比如说，对于序列{1, 2}，所有的f是{1, 2, 1 xor 2}，加起来是6；所有的g是{1, 2, 1 + 2}，异或起来是0。</div>
<div></div>
<div>他觉得这两个问题都非常的有趣，所以他找到了你，希望你能快速解决这两个问题，其中第一个问题的答案可能很大，你只需要输出它对998244353（一个质数）取模的值即可。</div>
<div></div>
<p class="MsoNormal" align="left"></p>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数n，表示序列的长度。</div>
<div>
<div></div>
<div>第二行n个非负整数A1, A2, ..., An，表示这个序列。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>两个整数，表示两个问题的答案，空格隔开，其中第一个问题的答案要对998244353（一个质数）取模。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 0<br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><div>100%的数据满足n &lt;= 10^5, Ai &lt;= 10^6。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

