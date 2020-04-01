<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　不同的进制数在自然科学中发挥着巨大的作用。人类最早时由于手指是十个所以广泛采用了十进制计数。在计算机科学中，由于电路一般为开和关两种状态，所以在机器内部都是使用二进制。人们为了方便处理二进制，使用了十六进制、八进制。<br/>
　　其实对于任何大于等于2的正整数p，p进制都存在。<br/>
　　给定一个非负整数a，请将a表示成p进制的形式。<br/>
　　这个问题有一个通用的处理方法，可以使用短除法来完成。它的规则是：<b>除p取余倒数</b><br/>
　　以将6转换成二进制为例。我们首先将6写下来，然后在它的左边写上2，将6除2的商3写在6下面，余数0写在右边。然后再对3做同样的操作，直到商变为0为止。如下图所示：<br/>
<img width="150" height="125" src="source/tsinsen/A1012/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9YXRGNjZuZkY=.do"/><br/>
　　下图中给出了一个将11转换成三进制数的例子：<br/>
<img width="150" height="125" src="source/tsinsen/A1012/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZTdRbVlOYWY=.do"/><br/>
　　在p进制数中，有0,1,...,p-1这p个最基本的符号，当p&gt;10时，使用数字无法合理的表示，所以引入A,B,...来表示这些大于等于10的符号，其中A表示10，B表示11，C表示12，依此类推。</div>
# 输入格式

<div class="pdcont">　　输入包含两个非负整数a和p，表示要转换的数和所用的进制。0&lt;=a&lt;=2147483647，2&lt;=p&lt;=36</div>
# 输出格式

<div class="pdcont">　　输出整数a的p进制表示</div>
# 样例输入

<div class="pddata">30 16</div>
# 样例输出

<div class="pddata">1E</div>

</div>