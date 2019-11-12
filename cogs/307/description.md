# 题目描述


<p>
<strong>【问题描述】 </strong> 
</p>
<p align="left">
    已知N个正整数：A1，A2，……，An。今要将它们分成M组，使得各组数据的数值和最平均，即各组的均方差最小。均方差公式如下：
</p>
<p align="left">
<br/>
</p>
<div>
<img border="0" alt="Image:Data1.gif" width="135" height="55" src="../../../mw/images/8/8e/Data1.gif"/> <img border="0" alt="Image:Data2.gif" width="77" height="49" src="../../../mw/images/d/d4/Data2.gif"/> 
</div>
<p align="left">
<br/>
</p>
<p align="left">
其中第一个公式是均方差，第二个公式是各组数据和的平均值，xi为第i组数据的数值和。
</p>
<p align="left">
【输入格式】 <br/>
    第一行是两个整数，表示N，M的值（N是整数个数，M是要分成的组数）。<br/>
    第二行有N个整数，表示A1，A2，……，An。整数的范围是1--50。
</p>
<p align="left">
（同一行的整数间用空格分开）
</p>
<p align="left">
【输出格式】 <br/>
    输出文件只有一行，包括一个数 ，表示最小均方差的值（保留小数点后两位数字）。
</p>
<p>
【输入样例】 <br/>
6 3 <br/>
1 2 3 4 5 6
</p>
<p>
【输出样例】
</p>
<p>
0.00
</p>
<p>
(1和6，2和5，3和4分别为一组)
</p>
<p>
【数据范围】
</p>
<p>
对于40%的数据，保证有M&lt;=N&lt;=10,2&lt;=M&lt;=6<br/>
对于100%的数据，保证有M&lt;=N&lt;=20,2&lt;=M&lt;=6
</p>
