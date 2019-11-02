# 

 
 # 题目背景 
<p>这种题。。。</p> 

 
 # 题目描述 
<p>算式排版<br />
算式的排版常常是一件非常令人头疼的事情。不过对于简单的算式，这项工作就并不是很复杂了。给定一个只包含常数（均为整数，不超过50位），变量（都是1位小写字母）以及&nbsp;+,&nbsp;-,&nbsp;*,&nbsp;/,&nbsp;^（乘方）,(,&nbsp;),&nbsp;{,&nbsp;}&nbsp;构成的算式。对于任何一个排版之后的算式，我们定义这个算式的&ldquo;边框&rdquo;为恰好可以完全盖住这个算式的最小矩形。<br />
例如：算式：<br />
&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....<br />
----&nbsp;&nbsp;&nbsp;&nbsp;====&gt;&nbsp;&nbsp;&nbsp;&nbsp;....<br />
1234&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....<br />
的边框是一个3*4的矩形，而算式<br />
1+2+3&nbsp;&nbsp;&nbsp;&nbsp;====&gt;&nbsp;&nbsp;&nbsp;&nbsp;.....<br />
的边框是一个1*5的矩形。<br />
{&nbsp;和&nbsp;}&nbsp;的作用是规定计算的顺序，但是不必输出。而&nbsp;(&nbsp;和&nbsp;)&nbsp;不仅规定计算顺序，而且是必须输出的。<br />
要求用以下的规则排版这个算式：<br />
(1]&nbsp;对于算式A，(A)必须满足以下规则：<br />
在A的边框左侧每一行增加一个(，右侧每一行增加一个)。<br />
例如：((12345))的正确输出是：<br />
((12345))<br />
(1/12)的正确输出是：<br />
(&nbsp;1)<br />
(--)<br />
(12)<br />
(2]&nbsp;对于算式A和算式B，A+B,&nbsp;A-B&nbsp;和&nbsp;A*B&nbsp;必须满足以下规则：<br />
A的分数线和B的分数线对齐（输入保证不会存在繁分式），并且以+(-,&nbsp;*)左右都必须留有一个空格。算式A,B的<br />
分数线，即作为A+B的分数线。<br />
例如：算式：x+y的正确输出是：<br />
x&nbsp;+&nbsp;y<br />
算式：{1/x}-y的正确输出是：<br />
1<br />
-&nbsp;-&nbsp;y<br />
x<br />
算式：x*(1/y)的正确输出是：<br />
&nbsp;&nbsp;&nbsp;&nbsp;(1)<br />
x&nbsp;*&nbsp;(-)<br />
&nbsp;&nbsp;&nbsp;&nbsp;(y)<br />
&nbsp;&nbsp;&nbsp;&nbsp;<br />
(3]&nbsp;对于算式A和算式B，A^B必须满足以下规则：（保证A不是繁分式）<br />
要求B的边框的左下角和A的边框的右上角重合。A^B的分数线定义为A的分数线。<br />
例如：算式{x+y}^{y+x}的正确输出为：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;y&nbsp;+&nbsp;x<br />
x&nbsp;+&nbsp;y&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;---&nbsp;结果的分数线<br />
算式{1/{x+y+z}}^(1/2)的正确输出为：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(-)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)<br />
&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />
---------&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;---&nbsp;结果的分数线<br />
x&nbsp;+&nbsp;y&nbsp;+&nbsp;z&nbsp;&nbsp;&nbsp;<br />
(4]&nbsp;对于算式A和算式B，A/B必须满足以下规则：（保证A,B的底数不是分式）<br />
要求A作为分子，B作为分母，A,B之间加上一条分数线。分数线的长度必须恰好既能覆盖A的边框，又能覆盖B的<br />
边框。并且如果A或B边框的宽度（列数）小于分数线宽度，那么A或B右侧的空格个数不多于左侧空格个数，并且<br />
至多比左侧少1个。<br />
新添加的分数线，作为A/B结果的分数线。<br />
例如：1/12345的正确输出是：<br />
&nbsp;&nbsp;1<br />
-----&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;---&nbsp;结果的分数线<br />
12345<br />
1/1234的正确输出是：<br />
&nbsp;&nbsp;1<br />
----&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;---&nbsp;结果的分数线<br />
1234<br />
x^{1/23)/y^{a+b+c}的正确输出是：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;23&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;x<br />
----------&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;---&nbsp;结果的分数线<br />
&nbsp;a&nbsp;+&nbsp;b&nbsp;+&nbsp;c<br />
y<br />
(5]&nbsp;另外，本题输出比较特别，要求输出算式的边框覆盖的部分必须被字符填满。也就是说，不足的地方全部<br />
应该由空格填充。例如：<br />
......1...<br />
.....--...<br />
.....23...<br />
....x.....<br />
----------<br />
.a&nbsp;+&nbsp;b&nbsp;+&nbsp;c<br />
y.........<br />
上面的.表示应该填充的空格。</p> 

 
 # 输入格式 
<p>一个算式，占一行，长度不超过255个字符。</p> 

 
 # 输出格式 
<p>满足上面要求的排版后的算式。保证算式长、宽均不超过100个字符。</p> 

 
 # 提示 
<p>非原创，转载</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>样例输入1
1+2+3+4+1/500

样例输入2
(1+2+(3+1/4))^x

样例输入3
{1+2+3^4}/100^100
</td><td>样例输出1
                 1
1 + 2 + 3 + 4 + ---
                500

样例输出2
                 x
(        (    1)) 
(1 + 2 + (3 + -)) 
(        (    4)) 

样例输出3
         4
1 + 2 + 3 
----------
     100  
  100     
</td></tr></table>
