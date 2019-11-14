# 题目描述


<h3>
【题目描述】
</h3>
<div class="ptx" lang="zh-CN">
An army of ants walk on a horizontal pole of length l cm, each with a constant speed of 1 cm/s. When a walking ant reaches an end of the pole, it immediatelly falls off it. When two ants meet they turn back and start walking in opposite directions. We know the original positions of ants on the pole, unfortunately, we do not know the directions in which the ants are walking. Your task is to compute the earliest and the latest possible times needed for all ants to fall off the pole.
</div>
<h3>
【输入格式】
</h3>
<div class="ptx" lang="zh-CN">
The first line of input contains one integer giving the number of cases that follow. The data for each case start with two integer numbers: the length of the pole (in cm) and n, the number of ants residing on the pole. These two numbers are followed by n integers giving the position of each ant on the pole as the distance measured from the left end of the pole, in no particular order. All input integers are not bigger than 1000000 and they are separated by whitespace.
</div>
<h3>
【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
For each case of input, output two numbers separated by a single space. The first number is the earliest possible time when all ants fall off the pole (if the directions of their walks are chosen appropriately) and the second number is the latest possible such time. <br/>
</div>
<h3>
【样例输入】
</h3>
<pre class="sio">2
10 3
2 6 7
214 7
11 12 7 13 176 23 191
</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">4 8
38 207
</pre>
<h3>
【提示】
</h3>
<div class="ptx" lang="zh-CN">
<a href="searchproblem?field=source&amp;key=Waterloo+local+2004.09.19">Waterloo local 2004.09.19</a> 
</div>
<h3>
【来源】
</h3>
<h3>
【题目来源】
</h3>
<a href="http://www.poj.org/problem?id=1852&amp;lang=zh-CN&amp;change=true"> 北京大学 POJ 1852</a>
