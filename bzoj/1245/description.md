
# Description

<div class="content">Mickey坐在已经升空的飞机上俯瞰大地，他发现土地被分成了很多个不同的矩形状，且由于覆盖的植被不同而显出不同的颜色。Mickey想寻找一个最大的矩形，它里面只显出一种颜色。在以下几张图中你可以看见样例中的几幅图，其中最终的答案区域已经被标记了出来。
 
<img border="0" src="/source/bzoj/1245/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEyNDVfMS5qcGc=.jpg"/>
请你编写一个程序计算一下所能看到的这样的矩形的面积，当然你可以放心，没有任何两块会互相重叠，然而二个矩形之间允许有共同点或公共边。

</div>

# Input

<div class="content">输入文件的第一行将包含一个数字N, 1 ≤ N ≤ 2500,它代表着土地上一共有N个矩形块。
接下来的N行中，每行都将有5个整数，依次记作X1,Y1,X2,Y2和C，其中X1<x2,y1<y2。 这些数字描绘了由(x1,y1),(x2,y2)围成的这样一个矩形块里显示出了颜色c,="" 1="" ≤="" c="" ≤="" 100。我们保证x1,y1,x2,y2的值都在0到1,000,000,000之间（包含0和1,000,000,000）。="" <="" div=""><h2>Output</h2><div class="content">输出文件应该只有一行，请输出如上题描述中的最大的矩形的面积。

注意
得出的答案数据范围在64位整型数以内，也就是Pascal的int64，C/C++的long long 以内。

</div><h2>Sample Input</h2>
			<div class="content"><span class="sampledata">5 <br/>
1 1 3 3 1 <br/>
3 1 5 3 1 <br/>
1 4 3 6 1 <br/>
3 4 5 6 1 <br/>
0 3 6 4 2<br/>
<br/>
</span></div><h2>Sample Output</h2>
			<div class="content"><span class="sampledata">8 <br/>
</span></div><h2>HINT</h2>
			<div class="content"><p></p></div><h2>Source</h2>
			<div class="content"><p><a href="problemset.php?search="></a></p></div><center>[<a href="submitpage.php?id=1245">Submit</a>][<a href="problemstatus.php?id=1245">Status</a>][<a href="bbs.php?id=1245">Discuss</a>]</center>﻿<br/>
<a href="./"><span class="red">HOME</span></a>
<a href="javascript:history.go(-1)"><span class="red">Back</span></a>

<hr/>
<center>
	<div class="footer">
			<a href="setlang.php?lang=ko">한국어</a> 
		<a href="setlang.php?lang=cn">中文</a> 
		<a href="setlang.php?lang=fa">فارسی</a> 
		<a href="setlang.php?lang=en">English</a> 
		<a href="setlang.php?lang=th">ไทย</a>
	<br/><div>版权所有 ©2008-2018 大视野在线测评 | <a href="http://www.miitbeian.gov.cn">湘ICP备13009380号</a></div>
		<div>Based on opensource project <a href="http://hustoj.googlecode.com">hustoj</a>.</div>
	</div>
</center>


</x2,y1<y2。></div>

# Output

<div class="content">输出文件应该只有一行，请输出如上题描述中的最大的矩形的面积。

注意
得出的答案数据范围在64位整型数以内，也就是Pascal的int64，C/C++的long long 以内。

</div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
1 1 3 3 1 <br/>
3 1 5 3 1 <br/>
1 4 3 6 1 <br/>
3 4 5 6 1 <br/>
0 3 6 4 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

