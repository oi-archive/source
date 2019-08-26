
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">给定一个<i>N</i>个顶点的凸多边形，多边形可能有多个点在一条直线上。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">给定<i>M</i>条直线，对于每条直线，问这条直线将多边形划分成的两个区域中，面积较小的那个区域的面积。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第1行包含一个<b><u>正整数</u></b><i>N</i>，表示了多边形顶点数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">接下来<i>N</i>行，每行两个绝对值不超过10000的整数<i>x</i>, <i>y</i>，按顺时针或者逆时针顺序给出了多边形每个顶点坐标。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第<i>N</i>+2行包含一个正整数<i>M</i>，表示了询问直线的个数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">接下来M行，每行4个绝对值不超过10000的整数<i>x</i><sub>1</sub>, <i>y</i><sub>1</sub>, <i>x</i><sub>2</sub>, <i>y</i><sub>2</sub>，表示了询问直线过(<i>x</i><sub>1</sub>, <i>y</i><sub>1</sub>), (<i>x</i><sub>2</sub>, <i>y</i><sub>2</sub>)两点，并保证了(<i>x</i><sub>1</sub>, <i>y</i><sub>1</sub>) ≠ (<i>x</i><sub>2</sub>, <i>y</i><sub>2</sub>)。<b><u>若直线将凸多边形划分成两部分，则输出较小那部分的面积，否则输出</u></b><b><u>0</u></b><b><u>。</u></b></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">应包含<i>M</i>行，对于每条直线输出对应结果，<b><u>保留</u></b><b><u>4</u></b><b><u>位小数</u></b>。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"> 5<br/>
0 0<br/>
0 5<br/>
0 10<br/>
10 10<br/>
10 0<br/>
4<br/>
0 0 10 10<br/>
9 10 10 9<br/>
10 -1 12 11<br/>
10 10 0 5<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">50.0000<br/>
0.5000<br/>
0.0000<br/>
25.0000<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据，有N, M ≤ 50000</span></p><br/>
<p><span style="font-size: medium">保留小数点后6位或以上，SPJ检查精度为小数点后4位</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训  Jason丶Hsiao 提供SPJ">2011福建集训  Jason丶Hsiao 提供SPJ</a></p></div>

