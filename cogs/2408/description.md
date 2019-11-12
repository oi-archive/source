# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;line-height:25px;background-color:#F0F8FF;">给一个数字串s和正整数d, 统计s有多少种不同的排列能被d整除（可以有前导0）。例如123434有90种排列能被2整除，其中末位为2的有30种，末位为4的有60种。</span> 
</p>
<p>
<span style="font-family:sans-serif;"><span style="font-size:20px;line-height:25px;background-color:#F0F8FF;"><b>输入：</b></span></span> 
</p>
<p>
<span style="font-family:sans-serif;"><span style="font-size:20px;line-height:25px;background-color:#F0F8FF;"><b>输入第一行是一个整数T，表示测试数据的个数，以下每行一组s和d，中间用空格隔开。s保证只包含数字0, 1, 2, 3, 4, 5, 6, 7, 8, 9.</b></span></span> 
</p>
<p>
<span style="font-family:sans-serif;"><span style="font-size:20px;line-height:25px;background-color:#F0F8FF;"><b>输出：</b></span></span> 
</p>
<p>
<span style="font-family:sans-serif;"><span style="font-size:20px;line-height:25px;background-color:#F0F8FF;"><b>每个数据仅一行，表示能被d整除的排列的个数。<br/>
</b></span></span> 
</p>
<h3>
【样例输入】
</h3>
<pre><p>
7
</p>

<p>
000
</p>

<p>
1
</p>

<p>
001
</p>

<p>
1
</p>

<p>
1234567890
</p>

<p>
1
</p>

<p>
123434
</p>

<p>
2
</p>

<p>
1234
</p>

<p>
7
</p>

<p>
12345
</p>

<p>
17
</p>

<p>
12345678
</p>

<p>
29
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
1
</p>

<p>
3
</p>

<p>
3628800
</p>

<p>
90
</p>

<p>
3
</p>

<p>
6
</p>

<p>
1398
</p>
</pre>
<h3>
【提示】
</h3>
<p>
</p><p>
数据范围：
</p>
<p>
20%的数据满足：s的长度不超过5, 1&lt;=T&lt;=5
</p>
<p>
50%的数据满足：s的长度不超过8
</p>
<p>
100%的数据满足：s的长度不超过10, 1&lt;=d&lt;=1000, 1&lt;=T&lt;=15
</p>
<p></p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
