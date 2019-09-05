# 题目描述


<span style="font-family:sans-serif;font-size:18px;line-height:27px;background-color:#FFFFFF;"> 
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
<span>描述 USACO 2.3.1 IOI96</span> 
</h2>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
在生物学中，一些生物的结构是用包含其要素的大写字母序列来表示的。生物学家对于把长的序列分解成较短的序列（即元素）很感兴趣。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
如果一个集合 P 中的元素可以通过串联（元素可以重复使用，相当于 Pascal 中的 “+” 运算符）组成一个序列 S ，那么我们认为序列 S 可以分解为 P 中的元素。元素不一定要全部出现（如下例中BBC就没有出现）。举个例子，序列 ABABACABAAB 可以分解为下面集合中的元素：
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
{A, AB, BA, CA, BBC}
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
如果序列S前面K个字符可以由某一集合中的元素组成，那么我们就说这K个字符为序列S的一个长度为K的前缀。设计一个程序，输入一个元素集合以及一个大写字母序列 S ，设S&#39;是序列S的最长前缀，使其可以分解为给出的集合P中的元素，求S&#39;的长度K。
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
<span><br/>
格式</span> 
</h2>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
<b>PROGRAM NAME</b>: prefix
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
<b>INPUT FORMAT</b> 
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
输入数据的开头包括 1..200 个元素（长度为 1..10 ）组成的集合，用连续的以空格分开的字符串表示。字母全部是大写，数据可能不止一行。元素集合结束的标志是一个只包含一个 “.” 的行。集合中的元素没有重复。接着是大写字母序列 S ，长度为 1..200,000 ，用一行或者多行的字符串来表示，每行不超过 76 个字符。换行符并不是序列 S 的一部分。
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
<b>OUTPUT FORMAT</b> 
</p>
<p style="font-family:sans-serif;font-size:18px;background-color:#FFFFFF;">
只有一行，输出一个整数，表示 S 符合条件的前缀的最大长度。
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
<span><br/>
SAMPLE INPUT (file prefix.in)</span> 
</h2>
<pre>A AB BA CA BBC
.
ABABACABAABC
</pre>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:28px;font-family:sans-serif;">
<span><br/>
SAMPLE OUTPUT (file prefix.out)</span> 
</h2>
<pre>11</pre>
</span>
