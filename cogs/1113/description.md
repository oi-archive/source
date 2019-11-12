# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 给出一个整数 n（n&lt;10^30) 和 k 个变换规则（k&lt;=15）。</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 规则：</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 一位数可变换成另一个一位数：</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 规则的右部不能为零。</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 例如：n=234。有规则（k＝2）：</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 2－&gt; 5</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 3－&gt; 6</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 上面的整数 234 经过变换后可能产生出的整数为（包括原数）:</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 234</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 534</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 264</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 564</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 共 4 种不同的产生数</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;">问题：</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 给出一个整数 n 和 k 个规则。</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;">求出：</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 经过任意次的变换（0次或多次），能产生出多少个不同整数。</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 仅要求输出个数。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p style="color:#656565;font-family:verdana, arial, sans-serif;text-align:justify;">
键盘输人，格式为：<br/>
n k<br/>
x1 y1<br/>
x2 y2<br/>
... ...<br/>
xn yn
</p>
<div>
<br/>
</div>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 屏幕输出，格式为：</span><br/>
<span style="color:#656565;font-family:verdana, arial, sans-serif;line-height:19.96666717529297px;background-color:#FFFFFF;"> 一个整数（满足条件的个数）：</span> 
</p>
<h3>
【样例输入】
</h3>
<pre>234 2
2 5
3 6
</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
<br/>
</h3>
