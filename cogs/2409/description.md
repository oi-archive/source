# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;"> 给一个由小写字母组成的字符串，我们可以用一种简单的方法来压缩其中的重复信息。压缩后的字符串除了小<br/>
写字母外还可以（但不必）包含大写字母R与M，其中M标记重复串的开始，R重复从上一个M（如果当前位置左边没<br/>
有M，则从串的开始算起）开始的解压结果（称为缓冲串）。 bcdcdcdcd可以压缩为bMcdRR，下面是解压缩的过程<br/>
<br/>
</span> 
</p>
<p>
<span style="font-size:medium;"> <img border="0" alt="" src="http://www.lydsy.com/JudgeOnline/images/1068/1.jpg"/> </span> 
</p>
<p>
<span style="font-size:medium;"> 另一个例子是abcabcdabcabcdxyxyz可以被压缩为abcRdRMxyRz。<br/>
</span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
输入仅一行，包含待压缩字符串，仅包含小写字母，长度为n。
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
输出仅一行，即压缩后字符串的最短长度。
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>bcdcdcdcdxcdcdcdcd</pre>
<h3>
【样例输出】
</h3>
<pre>12</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
<p>
<span style="font-size:medium;">在第一个例子中，解为aaaRa，在第二个例子中，解为bMcdRRxMcdRR。 <br/>
<br/>
【限制】 <br/>
<br/>
100%的数据满足：1&lt;=n&lt;=50 100%的数据满足：1&lt;=n&lt;=50<br/>
<br/>
</span> 
</p>
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search="></a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1068">耒阳大世界（衡阳八中） OJ 1068</a>
