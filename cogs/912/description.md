# 题目描述


<h3>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">【题目描述】</span>
</h3>
<p>
这个问题需要你写一个程序完成字符识别的任务。
</p>
<p>
每个完整的字符图案有 <span style="font-family:&#39;Times New Roman&#39;;">20 </span>行，<span style="font-family:&#39;Times New Roman&#39;;">20 </span>位。每个位是<span style="font-family:&#39;Times New Roman&#39;;">“0”</span>或<span style="font-family:&#39;Times New Roman&#39;;">“1”</span>。图 <span style="font-family:&#39;Times New Roman&#39;;">1a 是</span>输入文件中的符号图案的一部分。
</p>
<p>
输入文件charrec1.in的前541行包含了27个字符图案的信息，以这样的顺序记录：
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">_abcdefghijklmnopqrstuvwxyz</span> 
</p>
<p>
其中 <span style="font-family:&#39;Times New Roman&#39;;">_ </span>表示空格字符。每个完整字符长 <span style="font-family:&#39;Times New Roman&#39;;">20 </span>行。
</p>
<p>
输入文件的其余部分包含一个或多个可能损坏的字符图案。一个字符图案可能以这些方式被损坏。
</p>
<ul>
<li>
最多有一行被可能被复制了（一定接在原来那一行的下面）
</li>
<li>
最多有一行可能丢失了
</li>
<li>
有些<span style="font-family:&#39;Times New Roman&#39;;">“0”</span>可能被改成<span style="font-family:&#39;Times New Roman&#39;;">“1”</span> 
</li>
<li>
有些<span style="font-family:&#39;Times New Roman&#39;;">“1”</span>可能被改成<span style="font-family:&#39;Times New Roman&#39;;">“0”</span> 
</li>
</ul>
<p>
不会有任何一个字符图案既多余了一行<b>并且</b>又丢失了一行。
</p>
<p>
被复制的那一行中，原来的行和多余的行可能都损坏了，而且损坏的部分可能并不相同。
</p>
<p>
写一个程序，使用输入文件提供的字体，在输入文件提供的图象中识别出一个或多个的字符序列。
</p>
<p>
使用提供的字体图象来识别字符的时候，要找出最佳的多余行或遗漏行，使找出的所有<span style="font-family:&#39;Times New Roman&#39;;">“0”</span>和<span style="font-family:&#39;Times New Roman&#39;;">“1”</span>的变化数量最小。你必须确定和输入序列最接近的字符序列（就是损坏数据最少的那一个）。每个测试数据有唯一的最优解。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT (both input files)</span> 
</h3>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">    输入文件charrec1.in的第一行是一个正整数N1，描述了字体文件的行数（在所有的数据中N1=540）</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">    输入文件charrec1.in的第2~第541行是由0和1组成的字体文件，形如下图所示</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"> </span> 
</p>
<p>
(位1)(位2)(位3) ... (位20)
</p>
<p>
(位1)(位2)(位3) ... (位20)
</p>
<p>
...<span style="font-family:&#39;Times New Roman&#39;;"><br/>
</span><span style="font-family:&#39;Times New Roman&#39;;">输入文件charrec1.in的第542行是一个正整数N2，描述了要求识别的文件行数（19&lt;N2&lt;1200）</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">输入文件charrec1.in的第543~542+N2行是由0和1组成的文本文件，表示要求识别的文本，形式与字体文件相同。</span> 
</p>
<p>
<br/>
</p>
<p>
字体文件和文本文件的每行有<span style="font-family:&#39;Times New Roman&#39;;">20</span>位的宽度。在<span style="font-family:&#39;Times New Roman&#39;;">0</span>和<span style="font-family:&#39;Times New Roman&#39;;">1</span>之间没有空格分开。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;background-color:#F0F8FF;font-size:20px;font-weight:bold;line-height:25px;">OUTPUT FORMAT</span> 
</h3>
<p>
你的程序必须建立一个输出文件，包含一个识别出来的字符串。它的格式是一个单行的 <span style="font-family:&#39;Times New Roman&#39;;">ASCII </span>文本。输出文件中不应该包含任何分隔符。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file charrec1.in)</span> 
</h3>
<table border="1" cellspacing="1" cellpadding="7" width="491">
<tbody>
<tr>
<td valign="top" width="232">
<p>
例：charrec1.in<span style="font-family:&#39;Times New Roman&#39;;"> </span>的<i>开头</i>（不完全的），有<span style="font-family:&#39;Times New Roman&#39;;">“</span>空格<span style="font-family:&#39;Times New Roman&#39;;">”</span>和<span style="font-family:&#39;Times New Roman&#39;;">“<b>a</b>”</span> 
</p>
</td>
<td valign="top">
<p>
例：<span style="font-family:&#39;Times New Roman&#39;;">charrec1.in 的其余部分</span>显示了一个损坏的<span style="font-family:&#39;Times New Roman&#39;;">“<b>a</b>”</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="232">
<span style="font-family:&#39;Times New Roman&#39;;"><b> </b></span> 
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b>charrec1.in的前若干行(部分)</b></span> 
</p>
</td>
<td valign="top">
<b> </b> 
<p>
<b><span style="font-family:&#39;Times New Roman&#39;;">charrec1.in的其余部分</span></b> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="232">
<span style="font-family:&#39;Times New Roman&#39;;">540<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000011100000000000<br/>
00000111111011000000<br/>
00001111111001100000<br/>
00001110001100100000<br/>
00001100001100010000<br/>
00001100000100010000<br/>
00000100000100010000<br/>
00000010000000110000<br/>
00000001000001110000<br/>
00001111111111110000<br/>
00001111111111110000<br/>
00001111111111000000<br/>
00001000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000</span> 
</td>
<td valign="top">
<span style="font-family:&#39;Times New Roman&#39;;">19<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000000000000000000<br/>
00000011100000000000<br/>
00100111011011000000<br/>
00001111111001100000<br/>
00001110001100100000<br/>
00001100001100010000<br/>
00001100000100010000<br/>
00000100000100010000<br/>
00000010000000110000<br/>
00001111011111110000<br/>
00001111111111110000<br/>
00001111111111000000<br/>
00001000010000000000<br/>
00000000000000000000<br/>
00000000000001000000<br/>
00000000000000000000<br/>
00000000000000000000</span> 
</td>
</tr>
<tr align="middle">
<td width="232">
<span style="font-size:x-small;">图 </span><span style="font-family:&#39;Times New Roman&#39;;font-size:x-small;">1a</span> 
</td>
<td>
<span style="font-size:x-small;">图 </span><span style="font-family:&#39;Times New Roman&#39;;font-size:x-small;">1b</span> 
</td>
</tr>
</tbody>
</table>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file charrec1.out)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">a</span></pre>
<h3>
 提示
</h3>
<p>
1.少的一行不计算在变化数量内
</p>
<p>
2.对于多的一行，若第i+1行是第i行的重复，那么应计算第i行的变化数量而忽略第i+1行
</p>
<p>
3.原题称改变量不会超过30%（否则输出一个问号），但这个说法是错误的。你的程序不应在任何情况下输出问号，也不必判断改变量是否大于30%
</p>
<h3>
【题目来源】
</h3>
<p>
USACO/charrec(译 by Felicia Crazy)
</p>
