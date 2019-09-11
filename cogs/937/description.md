# 题目描述


<p>
<strong>问题描述</strong><br/>
给出一个字符矩阵及一些国都名：要求从这个矩阵中找出这些国都名，并输出它们的起始位置及方向。
</p>
<p style="text-indent:24pt;">
<br/>
</p>
<p style="text-indent:24pt;">
<img src="http://218.5.5.242:9018/JudgeOnline/upload/201312/a123.bmp" border="0" height="143" width="179"/> 
</p>
<p>
<br/>
</p>
<span style="font-family:&#39;Times New Roman&#39;;font-size:10.5pt;"> </span><strong>输入格式</strong> 
<p>
第一行有一个整数M和N(1≤M,N≤100)，表示该字符矩阵的长和宽。接下来就是M*N的字符矩阵。字符矩阵后有一个整数K(1≤K≤20)，表示国都名的个数，接下来的K行，每一行都是一个国都名，国都名长度不超过10。
</p>
<p>
<strong> 输出格式</strong> 
</p>
<p>
输出共有K行，第i行写入第i个国都名的起始位置及方向。如果一个国都名多次出现，只输出最靠上靠左的那种，起始位置用坐标表示，如没有找到国都名，输出‘No found’。
</p>
<p>
样例<br/>
country.in<br/>
8 8<br/>
okdkbliw<br/>
alpuocen<br/>
rasmusmb<br/>
oslondon<br/>
yiblglrc<br/>
kbrurwih<br/>
oarbxmdz<br/>
tpqglamv<br/>
6<br/>
dublin<br/>
lima<br/>
tokyo<br/>
prbu<br/>
paris<br/>
china
</p>
<p>
country.out<br/>
(1,3)76117<br/>
(5,6)753<br/>
(8,1)4444<br/>
(8,2)614<br/>
(8,2)4684<br/>
No found
</p>
<p>
<br/>
</p>
