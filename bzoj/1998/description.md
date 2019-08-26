
# Description

<div class="content">现在找工作不容易，Lostmonkey费了好大劲才得到fsk公司基层流水线操作员的职位。流水线上有n个位置，从0到n-1依次编号，一开始0号位置空，其它的位置i上有编号为i的盒子。Lostmonkey要按照以下规则重新排列这些盒子。
规则由5个数描述，q，p，m，d，s，s表示空位的最终位置。首先生成一个序列c，c0=0，ci+1=(ci*q+p) mod m。接下来从第一个盒子开始依次生成每个盒子的最终位置posi，posi=(ci+d*xi+yi) mod n，xi,yi是为了让第i个盒子不与之前的盒子位置相同的由你设定的非负整数，且posi还不能为s。如果有多个xi，yi满足要求，你需要选择yi最小的，当yi相同时选择xi最小的。
这样你得到了所有盒子的最终位置，现在你每次可以把某个盒子移动到空位上，移动后原盒子所在的位置成为空位。请问把所有的盒子移动到目的位置所需的最少步数。
</div>

# Input

<div class="content">第一行包含一个整数t，表示数据组数。接下来t行，每行6个数，n，s，q，p，m，d意义如上所述。
对于30%的数据n&lt;=100，对于100%的数据t&lt;=20,n&lt;=100000,s<n。其余所有数字均为不超过100000的正整数。 <="" div=""><h2>Output</h2><div class="content">对于每组数据输出一个数占一行，表示最少移动步数。
</div><h2>Sample Input</h2>
			<div class="content"><span class="sampledata">1                              <br/>
8 3 5 2 7 4<br/>
<br/>
</span></div><h2>Sample Output</h2>
			<div class="content"><span class="sampledata">6</span></div><h2>HINT</h2>
			<div class="content"><p>说明：第1个到第7个盒子的最终位置依次是：2 5 6 4 1 0 7<br/>
		  计算过程可能超过整型范围。<br/>
</p></div><h2>Source</h2>
			<div class="content"><p><a href="problemset.php?search="></a></p></div><center>[<a href="submitpage.php?id=1998">Submit</a>][<a href="problemstatus.php?id=1998">Status</a>][<a href="bbs.php?id=1998">Discuss</a>]</center>﻿<br/>
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


</n。其余所有数字均为不超过100000的正整数。></div>

# Output

<div class="content">对于每组数据输出一个数占一行，表示最少移动步数。
</div>

# Sample Input

<div class="content"><span class="sampledata">1                              <br/>
8 3 5 2 7 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p>说明：第1个到第7个盒子的最终位置依次是：2 5 6 4 1 0 7<br/>
		  计算过程可能超过整型范围。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

