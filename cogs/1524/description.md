# 题目描述


<h3>
【题目描述】
</h3>
<p>
儿童机协会（Association of Children Machines,ACM）正计划给小朋友们设计一类新的拼图游戏。这些拼图都是3*N的网格，并且使用如下的图形进行拼接。这些图形都可以出现任意次。由于ACM推出的这种拼图供不应求，因此许多别的公司发布了外观相同的仿制品，例如“穿越拼图”，“拼图联盟”。
</p>
<p>
<img src="/upload/image/20140215/20140215111148_97703.png" alt=""/> 
</p>
<p>
为了阻止假冒产品，ACM已经采取了措施，他们希望借此帮助商家避免自己的商店中出现仿品。因为所有的拼图都是3*N的网格，并且对于较大的N，一个3*N的拼图可能有无数种放法。ACM的工厂制作的所有拼图都只会有几种特定的放法数量。这个数量是独一无二的，并且只是所有N对应放法数的一小部分。因此假冒产品的放法数很可能不同。你将在最初的部分帮助他们：给出N的值，你将要找出用给定图形填满3*N拼图的方案总数。这些图形不能旋转，但每个图形都可以用任意多次。当然，有的图形仅仅是另外图形旋转得到的，但它们同样不能被旋转。例如，倒着的T型（棕色块）不能被旋转成正着的T型（粉色块）。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件包含多组数据。
</p>
<p>
每组数据有1行，包含一个正整数N(0&lt;N&lt;2001)。N表示网格的宽度。网格的高度总是3.
</p>
<p>
输入结束标志为N=0.不必处理这组数据。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出一行。这一行是一个固定的串，后面跟上方案数模10^12的值。具体格式见样例。
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
5
</p>
<p>
100
</p>
<p>
0
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
<br/>
</p>
<p>
Case 1: 26
</p>
<p>
Case 2: 584039302899
</p>
<p>
<br/>
</p>
<h3>
【样例解释】
</h3>
<p>
<img src="/upload/image/20140215/20140215112309_16010.png" alt=""/> 
</p>
<p>
N=5的情况
</p>
<h3>
【来源】
</h3>
<p>
<span style="background-color:white;font-family:serif;font-size:16px;font-weight:normal;line-height:20px;">Problem setter: Shahriar Manzoor, Special Thanks: Derek Kisman</span> 
</p>
<p>
<span style="background-color:white;font-family:serif;font-size:16px;font-weight:normal;line-height:20px;"><a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=571&amp;page=show_problem&amp;problem=3269" target="_blank">UVa12117 ACM Puzzles</a><br/>
</span> 
</p>
