
# Description

<div class="content"><p><span style="font-size: medium">　　给一个由小写字母组成的字符串，我们可以用一种简单的方法来压缩其中的重复信息。压缩后的字符串除了小<br/>
写字母外还可以（但不必）包含大写字母R与M，其中M标记重复串的开始，R重复从上一个M（如果当前位置左边没<br/>
有M，则从串的开始算起）开始的解压结果（称为缓冲串）。 bcdcdcdcd可以压缩为bMcdRR，下面是解压缩的过程<br/>
<br/>
</span></p>
<p><span style="font-size: medium"> <img border="0" alt="" src="/source/bzoj/1068/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEwNjgvMS5qcGc=.jpg"/> </span></p>
<p><span style="font-size: medium">　　另一个例子是abcabcdabcabcdxyxyz可以被压缩为abcRdRMxyRz。<br/>
</span></p></div>

# Input

<div class="content"><p>　　输入仅一行，包含待压缩字符串，仅包含小写字母，长度为n。</p></div>

# Output

<div class="content"><p>　　输出仅一行，即压缩后字符串的最短长度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">bcdcdcdcdxcdcdcdcd</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">在第一个例子中，解为aaaRa，在第二个例子中，解为bMcdRRxMcdRR。 <br/><br/>
【限制】 <br/><br/>
100%的数据满足：1&lt;=n&lt;=50 100%的数据满足：1&lt;=n&lt;=50<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

