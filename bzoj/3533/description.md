
# Description

<div class="content"><p><span style="font-size: medium">维护一个向量集合，在线支持以下操作：<br/>
&#34;A x y (|x|，|y| &lt; =10^8)&#34;：加入向量(x，y);<br/>
&#34; Q x y l r (|x|，|y| &lt; =10^8，1 &lt; =L &lt; =R &lt; =T，其中T为已经加入的向量个数)询问第L个到第R个加入的向量与向量(x，y)的点积的最大值。<br/>
    集合初始时为空。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">    输入的第一行包含整数N和字符s，分别表示操作数和数据类别；<br/>
    接下来N行，每行一个操作，格式如上所述。<br/>
    请注意s≠&#39;E&#39;时，输入中的所有整数都经过了加密。你可以使用以下程序<br/>
得到原始输入：<br/>
inline int decode (int x long long lastans) {<br/>
     return x ^ (lastans &amp; Ox7fffffff);<br/>
}<br/>
function decode<br/>
begin<br/>
    其中x为程序读入的数，lastans为之前最后一次询问的答案。在第一次询问之前，lastans=0。<br/>
</font></p>
<p><font size="4">注：向量(x，y)和(z，W)的点积定义为xz+yw。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">  对每个Q操作，输出一个整数表示答案。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">    6 A<br/>
    A 3 2<br/>
    Q 1 5 1 1<br/>
    A 15 14<br/>
    A 12 9<br/>
    Q 12 8 12 15<br/>
    Q 21 18 19 18<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    13<br/>
    17<br/>
    17<br/>
<br/>
解释：解密之后的输入为<br/>
  6 E<br/>
    A 3 2<br/>
    Q 1 5 1 1<br/>
    A 2 3<br/>
    A 1 4<br/>
    Q 1 5 1 2<br/>
    Q 4 3 2 3</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">1 &lt; =N &lt; =4×10^5</span></p><br/>
<p>新加数据一组..2015.315</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 Day 2">Round 1 Day 2</a></p></div>

