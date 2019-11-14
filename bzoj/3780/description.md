
# Description

<div class="content"><div>小A正在研究一些数字统计问题。有一天他突然看到了一个这样的问题：</div>
<div>将[L..R]中的所有整数用M位二进制数表示（允许出现前导0）。现在将这些数中的每一个作如下变换：</div>
<div>从这个数的最低两位开始，如果这两位都是0，那么X=1，否则X=0。现在将这两位删去，然后将X放在原来最低位的位置上。重复这个变换直到这个数只剩下一位为止。</div>
<div>例如01001的变换过程如下：</div>
<div>01001--&gt;0100--&gt;011--&gt;00--&gt;1。</div>
<div>现在的问题是变换后的所有数中，值为Y（Y为0或1）的有多少个？</div>
<div>小A不会了，他想让你帮助他完成这个问题。</div>
<p></p></div>

# Input

<div class="content"><div>输入文件包含多组测试数据。</div>
<div>第一行，一个整数T，表示测试数据的组数。</div>
<div>接下来的T节，每节对应一组测试数据，格式如下：</div>
<div>第一行，两个整数M、Y。</div>
<div>第二行，两个M位二进制数L、R。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组测试数据，输出一行，一个二进制数，表示该组测试数据中[L..R]中的所有整数变换后的值为Y的个数。这里的二进制数不允许出现前导0。</div>
<div></div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3 1<br/>
001 101<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="text-indent:21.0pt;mso-char-indent-count:2.0">对于全部的数据，1&lt;=M&lt;=200，1&lt;=T&lt;=50。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

