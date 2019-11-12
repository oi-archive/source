# 题目描述


<h1 style="font-family:arial, sans-serif;font-size:15px;color:#1798E9;font-weight:normal;text-align:justify;">
题目描述
</h1>
<p style="color:#656565;font-family:verdana, arial, sans-serif;text-align:justify;">
丁丁最近沉迷于一个数字游戏之中。这个游戏看似简单，但丁丁在研究了许多天之后却发觉原来在简单的规则下想要赢得这个游戏并不那么容易。游戏是这样的，在你面前有一圈整数（一共n个），你要按顺序将其分为m个部分，各部分内的数字相加，相加所得的m个结果对10取模后再相乘，最终得到一个数k。游戏的要求是使你所得的k最大或者最小。<br/>
例如，对于下面这圈数字（n=4，m=2）：<br/>
<img src="/upload/image/20120902/20120902103350_18481.bmp" alt=""/><br/>
当要求最小值时，((2-1) mod 10)×((4+3) mod 10)=1×7=7，要求最大值时，为((2+4+3) mod 10)×(-1 mod 10)=9×9=81。特别值得注意的是，无论是负数还是正数，对10取模的结果均为非负值。<br/>
丁丁请你编写程序帮他赢得这个游戏。
</p>
<h1 style="font-family:arial, sans-serif;font-size:15px;color:#1798E9;font-weight:normal;text-align:justify;">
输入格式
</h1>
<p style="color:#656565;font-family:verdana, arial, sans-serif;text-align:justify;">
输入文件第一行有两个整数，n（1≤n≤50）和m（1≤m≤9）。以下n行每行有个整数，其绝对值不大于10^4，按顺序给出圈中的数字，首尾相接。
</p>
<h1 style="font-family:arial, sans-serif;font-size:15px;color:#1798E9;font-weight:normal;text-align:justify;">
输出格式
</h1>
<p style="color:#656565;font-family:verdana, arial, sans-serif;text-align:justify;">
输出文件有两行，各包含一个非负整数。第一行是你程序得到的最小值，第二行是最大值。
</p>
<dd>
【输入样例】
</dd>
<dd>
</dd>
<dt>
<pre>4 2
4
3
-1
2</pre>
</dt>
<dd>
【输出样例】
</dd>
<dd>
</dd>
<dt>
<pre>7
81</pre>
</dt>
