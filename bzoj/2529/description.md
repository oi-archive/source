
# Description

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Little Johnny was given a birthday present by his grandparents. This present is a box of sticks of various lengths and colours. Johnny wonders if there are three sticks in the set he has been given that would form a triangle with different-coloured sides. Let us note that Johnny is interested in non-degenerate triangles only, i.e., those with positive area. </span></span></div>
<p><span style="font-size: medium">给出若干木棍，每根木棍有特定的颜色和长度。问能否找到三条颜色不同的木棍构成一个三角形。<br/>
(注意这里所说的三角形面积要严格大于0)<br/>
<br/>
第一行给出一个整数k(3&lt;=k&lt;=50),表示颜色的种数。这k种颜色被标号为1至k。<br/>
接下来k行，第i+1描述颜色为i的木棍的信息。<br/>
首先一个整数Ni(1&lt;=Ni&lt;=10^6)表示颜色为i的木棍的数量。<br/>
接下来Ni个整数，表示这Ni根木棍各自的长度。<br/>
所有木棍的长度&lt;=10^9。总木棍数量&lt;=10^6。<br/>
<br/>
你的程序应该仅输出一行<br/>
如果有解，输出6个整数，分别表示第一条边的颜色，第一条边的长度，第二条边的颜色，第二条边的长度，第三条边的颜色，第三条边的长度，这六个整数以空格分割。<br/>
如果有多组解，随便输出一组即可。<br/>
如果无解，输出 NIE<br/>
<br/>
</span></p></div>

# Input

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In the first line of the standard input an integer k(3&lt;=k&lt;=50)is given, which is the number of different colours of sticks. The colours themselves are numbered from 1 to k. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">The following klines contain descriptions of the sticks of particular colours. The line no. i+1holds integers that describe the sticks of colour , separated by single spaces. The first of these numbers, Ni(1&lt;=Ni&lt;=10^6) denotes the number of sticks of colour . It is followed, in the same line, by Niintegers denoting the lengths of the sticks of colour . All lengths are positive and do not exceed10^9. Furthermore, the total number of all sticks does not exceed 10^6.0020</span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">In tests worth at least 30% of the points the following holds in addition: the total number of the sticks does not exceed 250. </span></span></div></div>

# Output

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">Your program should print (on the first and only line of the standard output) either: </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">·<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="color: #444444; line-height: 140%">six integers, separated by single spaces, that describe the construction of a triangle with different-coloured sides as follows: the colour and the length of the first stick, the colour and the length of the second stick, and the colour and the length of the third stick, </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">·<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="color: #444444; line-height: 140%">or the word </span><span style="color: #444444; line-height: 140%">NIE</span><span style="color: #444444; line-height: 140%"> (Polish for <i>no</i>) if no such triple of sticks exists. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: #444444; line-height: 140%">If there are multiple triples of different-coloured sticks that give rise to a triangle, your program may pick one such triple arbitrarily. </span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 42<br/>
2 6 9<br/>
3 8 4 8<br/>
1 12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 8 4 12 2 9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Kac">鸣谢Kac</a></p></div>

