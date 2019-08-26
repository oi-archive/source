
# Description

<div class="content">小可可在欢乐岛的快乐旅程还在继续，他想买一些纪念品带回去给同学们，于是来到了礼品部，在这里他发现了一个有趣的计算器，这个计算器是一种特殊的、支持变进制整数加减运算的计算器(所谓变进制，就是每一位的进制可以不同．例如，如果最低位是3进制，次低位是5进制，那么这种情况的42转化成十进制就是4*3+2=14)。店主看小可可对这个计算器非常感兴趣，于是他问小可可：“小朋友，如果我告诉你这个计算器最多可以支持N位的变进制整数，且每一位的进制分别是x1…xn，那么你知道它能表示的最大整数M是多少吗?”，小可可想了想说到：“它所能表示的最大的整数M是(x1×x2…×xn)-l。”店主非常
高兴，说到：“你真是个聪明的孩子，如果我告诉你两个长度为N的变进制整数A，B，你按照我的要求来计算(A＋B)mod(M+1)或(A-B)mod(M+1)，答案还是用相同的变进制来表示，如果你算对了，那么我就把这个计算器送给你。”这下把小可可难住了，但是他非常想要这个计算器，聪明的你能够帮助小可可吗?
</div>

# Input

<div class="content">第一行包含一个整数N(N&lt;=100000)，表示计算器所支持的变进制数的长度；第二行包含N个整数x1…xn(1<x1…xn<100)，表示第l～n位的进制(从最高位到最低位)；第三行包含n个整数a1…an，表示第一个运算数；第四行包含一个字符op，表示需要实现的运算类型；第五行包含n个整数b1…bn，表示第二个运算数． <="" div=""><h2>Output</h2><div class="content">若op为&#39;＋&#39;，则输出(A+B)mod(M+1)的值，否则输出(A-B)mod(M+1)的值，每一位之间用一个空格隔开，注意高位补零，最高位之前和最低位之后不要有空格。
</div><h2>Sample Input</h2>
			<div class="content"><span class="sampledata">3<br/>
3 2 5<br/>
1 1 2<br/>
+<br/>
0 0 3<br/>
</span></div><h2>Sample Output</h2>
			<div class="content"><span class="sampledata">2 0 0<br/>
<br/>
</span></div><h2>HINT</h2>
			<div class="content"><p>100％的数据中，N &lt; = 100000，1 &lt; (X1,x2…，XN )&lt;100<br/>
30％的数据中，N &lt; = 9，x1 = x2 =… = xN =l0<br/>
</p></div><h2>Source</h2>
			<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div><center>[<a href="submitpage.php?id=1788">Submit</a>][<a href="problemstatus.php?id=1788">Status</a>][<a href="bbs.php?id=1788">Discuss</a>]</center>﻿<br/>
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


</x1…xn<100)，表示第l～n位的进制(从最高位到最低位)；第三行包含n个整数a1…an，表示第一个运算数；第四行包含一个字符op，表示需要实现的运算类型；第五行包含n个整数b1…bn，表示第二个运算数．></div>

# Output

<div class="content">若op为&#39;＋&#39;，则输出(A+B)mod(M+1)的值，否则输出(A-B)mod(M+1)的值，每一位之间用一个空格隔开，注意高位补零，最高位之前和最低位之后不要有空格。
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3 2 5<br/>
1 1 2<br/>
+<br/>
0 0 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 0 0<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>100％的数据中，N &lt; = 100000，1 &lt; (X1,x2…，XN )&lt;100<br/>
30％的数据中，N &lt; = 9，x1 = x2 =… = xN =l0<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

