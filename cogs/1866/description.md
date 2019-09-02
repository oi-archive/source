
<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->

# 试题来源


<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>

# 问题描述


<div class="pdcont">
众所周知，新世纪的科学很发达，于是Ray 和DarkRaven 开始了星<br/>
际探险，他们在宇宙中开辟了一片空间，建造了N 个空间站。这N 个空<br/>
间站由一些单向的时空隧道连接，这些时空隧道都有一个穿越指数，穿过<br/>
这些时空隧道，你可以走到未来或者回到过去，当然，这些都是由穿越指<br/>
数决定的。<br/>
有一天，Ray 和DarkRaven 开始了一场比赛。他们要从一个空间站S<br/>
出发去另一个空间站T，先到的人获胜。DarkRaven 一定会选一条能最快<br/>
到达T 的路线。他希望Ray 输给他，所以事先在Ray 的飞船上设定了飞<br/>
行路径，使得Ray 从S 到T 只能走一条特定的路径。但是，Ray 有对策，<br/>
他有一台能够操纵时空隧道的机器，这台机器每次可以把某一条时空隧道<br/>
的穿越指数增加或减少1，但是因为操纵机器很累，所以Ray 希望尽可能<br/>
少改动，当然，如果改动后从某个空间站经过一系列的穿越可以在从这个<br/>
空间站出发之前回到这个空间站，那么这样的改动是不允许的。修改之后，<br/>
DarkRaven 依然会走能最快到达终点的路线，所以Ray 是不可能赢的。但<br/>
他请你帮助他确定改动时空隧道的方案，使得他能和DarkRaven 同时到达<br/>
T。
</div>

# 输入格式


<div class="pdcont">
输入的第一行包含两个整数N 和M，代表空间站的数目和时空隧道<br/>
的数目。N　　接下来M 行，每行三个整数u、v 和w，代表从空间站u 到空间站<br/>
v 有一条时空隧道，它的穿越指数是w。u,v是0 ... N - 1。<br/>
第M + 2 行包含一个整数p，代表DarkRaven 在Ray 的飞船上设定<br/>
的那条路径的空间站数。第M + 3 行包含p 个数，那条路径上的空间站的<br/>
编号，第一个数是S，最后一个数是T。
</div>

# 输出格式


<div class="pdcont">
输出的第一行包含一个整数，表示Ray 走那条路径并且能够赢得比赛<br/>
的情况下操纵时间机器的最小次数。<br/>
接来来输出M 行，其中第i 行输出一个整数w，表示把输入中第i 条<br/>
时空隧道的穿越指数增加w， w 可以是负数。<br/>
4<br/>
如果第一问（操纵时间机器的最小次数）正确，可以得到该测试点<br/>
20% 的分数，如果在此基础上方案可行，能得到该测试点100% 的分数。
</div>

# 样例输入


<div class="pddata">
3 3<br/>
0 1 1<br/>
1 2 2<br/>
0 2 1<br/>
3<br/>
0 1 2
</div>

# 样例输出



# 数据规模


一共有10 个数据，对于第i (1 ≤ i ≤ 10)
个数据， N = i * 500，M
= i * 5000。
<div id="pcont2" style="margin-top:20px;display:none;">

# 问题描述


<div class="probcontent">
众所周知，新世纪的科学很发达，于是Ray 和DarkRaven 开始了星<br/>
际探险，他们在宇宙中开辟了一片空间，建造了N 个空间站。这N 个空<br/>
间站由一些单向的时空隧道连接，这些时空隧道都有一个穿越指数，穿过<br/>
这些时空隧道，你可以走到未来或者回到过去，当然，这些都是由穿越指<br/>
数决定的。<br/>
有一天，Ray 和DarkRaven 开始了一场比赛。他们要从一个空间站S<br/>
出发去另一个空间站T，先到的人获胜。DarkRaven 一定会选一条能最快<br/>
到达T 的路线。他希望Ray 输给他，所以事先在Ray 的飞船上设定了飞<br/>
行路径，使得Ray 从S 到T 只能走一条特定的路径。但是，Ray 有对策，<br/>
他有一台能够操纵时空隧道的机器，这台机器每次可以把某一条时空隧道<br/>
的穿越指数增加或减少1，但是因为操纵机器很累，所以Ray 希望尽可能<br/>
少改动，当然，如果改动后从某个空间站经过一系列的穿越可以在从这个<br/>
空间站出发之前回到这个空间站，那么这样的改动是不允许的。修改之后，<br/>
DarkRaven 依然会走能最快到达终点的路线，所以Ray 是不可能赢的。但<br/>
他请你帮助他确定改动时空隧道的方案，使得他能和DarkRaven 同时到达<br/>
T。<br/>
<br/>
</div>

# 输入格式


<div class="probcontent">
输入的第一行包含两个整数N 和M，代表空间站的数目和时空隧道<br/>
的数目。N &lt;= 10000; M &lt;= 100000。<br/>
接下来M 行，每行三个整数u、v 和w，代表从空间站u 到空间站<br/>
v 有一条时空隧道，它的穿越指数是w。0 &lt;= w &lt;= 2000。空间站的编号<br/>
是0 ... N - 1。<br/>
第M + 2 行包含一个整数p，代表DarkRaven 在Ray 的飞船上设定<br/>
的那条路径的空间站数。第M + 3 行包含p 个数，那条路径上的空间站的<br/>
编号，第一个数是S，最后一个数是T。<br/>
<br/>
</div>

# 输出格式


<div class="probcontent">
输出的第一行包含一个整数，表示Ray 走那条路径并且能够赢得比赛<br/>
的情况下操纵时间机器的最小次数。<br/>
接来来输出M 行，其中第i 行输出一个整数w，表示把输入中第i 条<br/>
时空隧道的穿越指数增加w， w 可以是负数。<br/>
4<br/>
如果第一问（操纵时间机器的最小次数）正确，可以得到该测试点<br/>
20% 的分数，如果在此基础上方案可行，能得到该测试点100% 的分数。<br/>
<br/>
</div>

# 样例输入


<div class="probexample">
3 3<br/>
0 1 1<br/>
1 2 2<br/>
0 2 1<br/>
3<br/>
0 1 2<br/>
<br/>
</div>

# 样例输出


<div class="probexample">
2<br/>
0<br/>
0<br/>
2<br/>
<br/>

# "ret"

");
			if (canUseFile)
			{
				newT("span", divS, "", " &nbsp; &nbsp; &nbsp; ");
				var l2 = newT("a", divS, "", "上传文件提交");
				l2.href = "###";
				l2.onclick = function() {
					setDivS2();
				};
			}
		}
		function toLangDesc(lang)
		{
			if (lang=="CPP") return "C++ (MinGW g++ 4.7.2)";
			if (lang=="C") return "C (MinGW gcc 4.7.2)";
			if (lang=="C0X") return "C++0x (MinGW g++ 4.7.2 --std=c++0x)";
			if (lang=="VC9") return "VC (Microsoft Visual C++ 2008)";
			if (lang=="PAS") return "PAS (Free Pascal Compiler 2.4.0)";
			if (lang=="CS") return "C# (Microsoft .NET 3.5)";
			if (lang=="JAVA") return "Java (Java 1.7.0_15)";
			if (lang=="RUBY") return "Ruby (Ruby 1.8.6)";
			if (lang=="PERL") return "Perl (Perl v5.16.3)";
			if (lang=="PYTHON") return "Python (Python 3.3.0)";
			if (lang=="PYTHON27") return "Python (Python 2.7.3)";
			if (lang=="PHP") return "PHP (PHP 5.4.13)";
			return lang;
		}
		function setDivS2()
		{
			if (canUsePaste && !canUseFile)
			{
				setDivS1()
				return ;
			}
			div.style.display = "none";
			fdiv.style.display = "block";
			divS.innerHTML = "";
			if (canUsePaste)
			{
				var l1 = newT("a", divS, "", "粘贴代码提交");
				l1.href = "###";
				l1.onclick = function() {
					setDivS1();
				};
				newT("span", divS, "", " &nbsp; &nbsp; &nbsp; ");
			}
			var l2 = newT("span", divS, "", "
# la


</div>
