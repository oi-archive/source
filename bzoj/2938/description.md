
# Description

<div class="content"><div><span style="font-size: medium">二进制病毒审查委员会最近发现了如下的规律：某些确定的二进制串是病毒的代码。如果某段代码中不存在任何一段病毒代码，那么我们就称这段代码是安全的。现在委员会已经找出了所有的病毒代码段，试问，是否存在一个无限长的安全的二进制代码。</span></div>
<div><span style="font-size: medium">示例：</span></div>
<div><span style="font-size: medium">例如如果{011, 11, 00000}为病毒代码段，那么一个可能的无限长安全代码就是010101…。如果{01, 11, 000000}为病毒代码段，那么就不存在一个无限长的安全代码。</span></div>
<div><span style="font-size: medium">任务：</span></div>
<div><span style="font-size: medium">请写一个程序：</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>读入病毒代码；</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>判断是否存在一个无限长的安全代码；</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>将结果输出</span></div></div>

# Input

<div class="content"><div> </div>
<div><span style="font-size: medium">第一行包括一个整数n，表示病毒代码段的数目。以下的n行每一行都包括一个非空的01字符串——就是一个病毒代码段。所有病毒代码段的总长度不超过30000。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">你应在在文本文件WIN.OUT的第一行输出一个单词：</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>TAK——假如存在这样的代码；</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>NIE——如果不存在。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
01 <br/>
11 <br/>
00000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">NIE<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

