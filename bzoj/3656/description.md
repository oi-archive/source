
# Description

<div class="content"><div><span style="font-size: medium">初始的时候有n个数，第i个数的大小是2<sup>i-1</sup>,我们依次处理每一个数，第i次把第i个数变为编号为i的约数的所有数的异或。比如当n为6的时候：</span></div>
<div><span style="font-size: medium">初始6个数为：</span></div>
<div><span style="font-size: medium">1 2 4 8 16 32</span></div>
<div><span style="font-size: medium">第一次操作1不变所以它们还是：</span></div>
<div><span style="font-size: medium">1 2 4 8 16 32</span></div>
<div><span style="font-size: medium">第二次操作2异或1得到：</span></div>
<div><span style="font-size: medium">1 3 4 8 16 32</span></div>
<div><span style="font-size: medium">第三次操作4异或1得到：</span></div>
<div><span style="font-size: medium">1 3 5 8 16 32</span></div>
<div><span style="font-size: medium">第四次操作8异或3异或1得到：</span></div>
<div><span style="font-size: medium">1 3 5 10 16 32</span></div>
<div><span style="font-size: medium">第五次操作16异或1得到：</span></div>
<div><span style="font-size: medium">1 3 5 10 17 32</span></div>
<div><span style="font-size: medium">第六次操作32异或5异或3异或1得到：</span></div>
<div><span style="font-size: medium">1 3 5 10 17 39</span></div>
<div><span style="font-size: medium">现在我们想知道有多少个正整数b使得可以通过从这最后n个数中取出k个异或起来得到。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行三个正整数n，k，p。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">一个数输出满足条件的b的数量mod p的值。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">100%的数据n&lt;=109，k&lt;=n，p&lt;=100000<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

