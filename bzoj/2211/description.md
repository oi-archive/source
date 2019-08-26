
# Description

<div class="content">给你一个长度为L的正整数序列，每次你可以从两端取数字，直到取完为止。假设你第i次取的数字为Ai-1，那么你最后的得分S=Sigma(Ai*5^i)(0&lt;=i&lt;=N-1) 。当然，这个游戏获胜并不是比分的高低，它获胜的条件是：S mod 8=3！ 现在随机构建了一棵树，并且给树上的每个点都标上了一个正整数。这样，他就可以在树上选两个点A和B，把A和B之间的路径作为一个游戏用的序列。他把这样一个游戏称为Game(A，B)。如果Game(A，B)是可能赢的，那么他就认为Game(A，B)是一个好点，否则就认为它是一个坏点。问有多少点对（A，B，C）满足Game（A，B）、Game（B，C）、Game(A，C)均是好点或或点且A<b<c。< div=""><h2>Input</h2><div class="content">第一行包含一个整数T，表示数据组数。
对于每组数据，第一行包含一个整数n，表示树上的点的数目。接下来n行,第i行包含两个整数Fi和Vi，分别表示第i个点的父亲、第i个点上的数字。如果Fi=0，则表示第i个点为根。
</div><h2>Output</h2><div class="content">对于每组数据输出一个整数ans，表示满足条件的点对数目。



</div><h2>Sample Input</h2>
			<div class="content"><span class="sampledata">1<br/>
3<br/>
0 3<br/>
1 5<br/>
1 7<br/>
<br/>
</span></div><h2>Sample Output</h2>
			<div class="content"><span class="sampledata">0<br/>
数据范围：<br/>
对于100%的数据 n&lt;=100000 T&lt;=10 Vi&lt;=10^9<br/>
<br/>
<br/>
<br/>
<br/>
</span></div><h2>HINT</h2>
			<div class="content"><p></p></div><h2>Source</h2>
			<div class="content"><p><a href="problemset.php?search=相比原题有变动">相比原题有变动</a></p></div><center>[<a href="submitpage.php?id=2211">Submit</a>][<a href="problemstatus.php?id=2211">Status</a>][<a href="bbs.php?id=2211">Discuss</a>]</center>﻿<br/>
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


</b<c。<></div>

# Input

<div class="content">第一行包含一个整数T，表示数据组数。
对于每组数据，第一行包含一个整数n，表示树上的点的数目。接下来n行,第i行包含两个整数Fi和Vi，分别表示第i个点的父亲、第i个点上的数字。如果Fi=0，则表示第i个点为根。
</div>

# Output

<div class="content">对于每组数据输出一个整数ans，表示满足条件的点对数目。



</div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3<br/>
0 3<br/>
1 5<br/>
1 7<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
数据范围：<br/>
对于100%的数据 n&lt;=100000 T&lt;=10 Vi&lt;=10^9<br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=相比原题有变动">相比原题有变动</a></p></div>

