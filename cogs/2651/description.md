# 题目描述


<p>
<span style="color:#E53333;font-size:32px;">题目解释：</span> 
</p>
<p>
<span style="color:#E53333;font-size:32px;">所有整数都是正整数</span> 
</p>
<p>
<span style="color:#E53333;font-size:32px;">新添一组大样例</span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">题目最下面的咒语使用似乎会ce，请勿使用</span></span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">已添加一句话题意</span></span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">第i个时刻开始的时候会继承第i-1个时刻的状态</span></span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">为了使题意更加容易理解，样例已更新</span></span> 
</p>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
慧音也想要退治妖怪！
</p>
<p>
在某次异变中，慧音要退治排成一列的n个妖怪，作为&#34;吞食历史的半兽&#34;，慧音会使用符卡&#34;新史「新幻想史 -现代史-」&#34;修改过去的历史来让一段区间内的妖怪力量减少，同时因为历史被改变了，所以会有另一段区间的妖怪力量增强（一个妖怪的力量改变后，这个效果会一直持续到后面的时刻）。为了让修改历史的效果最稳定，慧音还想知道在过去的某个时刻一段区间中所有妖怪的妖力和是多少，每个时刻慧音只会发出一条指令。
</p>
<p>
战斗持续了m个时刻，由于慧音还要集中精力发射<del>头槌</del>弹幕，所以她请你来帮忙解决她的询问。
</p>
<p>
（没有进行任何操作的时刻为0时刻
</p>
<p>
关于时间线的说明：
</p>
<p>
如果有以下操作：询问1-&gt;修改-&gt;询问2，询问的目标时刻相等，修改的目标时刻小于等于询问的目标时刻，则询问1不会受到修改的影响，而询问2会
</p>
<p>
如果有以下操作：询问1-&gt;修改-&gt;询问2，询问的目标时刻相等，修改的目标时刻大于询问的目标时刻，则两个询问都不会受到修改的影响
</p>
<p>
特别提醒：
</p>
<p>
比赛进行中请尽量不要进行有关时间线或世界线的伦理思考
</p>
<p>
一句话题意：
</p>
<p>
有一个长度为n的整数序列，共m个时刻，在每个时刻都有一个操作，如果是询问操作则询问指定时刻一段区间的和，如果是修改操作则使修改指定时刻到当前时刻的所有时刻一段区间全部增加一个数，另一段区间全部减少一个数
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行两个整数n,m，意义如上
</p>
<p>
接下来一行n个整数，第i个整数ai表示第i个妖怪的妖力
</p>
<p>
接下来m行，第i行表示第i个时刻的指令，首先一个字符c，如果c为&#39;Q&#39;，接下来三个用空格隔开的整数x,y,z，表示询问第z个时刻区间[x,y]中所有妖怪的妖力和，如果c为&#39;M&#39;，接下来七个整数x,y,z,l,r,v,t，表示在第t个时刻，区间[x,y]中所有妖怪的妖力减少了z，区间[l,r]中所有妖怪妖力增加了v
</p>
<p>
输入数据中一行中的所有整数和字符用空格隔开
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
对于每个M操作，输出一行一个值表示查询的结果
</p>
<p>
<br/>
</p>
<h3>
【样例输入1】
</h3>
<p>
<br/>
</p>
<p>
5 5
</p>
<p>
1 2 3 4 5
</p>
<p>
Q 1 3 0
</p>
<p>
M 1 2 1 2 3 2 1
</p>
<p>
Q 1 3 0
</p>
<p>
Q 1 3 1
</p>
<p>
Q 1 3 3
</p>
<p>
<br/>
</p>
<h3>
【样例输出1】
</h3>
<p>
<br/>
</p>
<p>
6
</p>
<p>
6
</p>
<p>
8
</p>
<p>
8
</p>
<p>
<br/>
</p>
<h3>
【样例输入2】
</h3>
<p>
<br/>
</p>
<p>
12 12
</p>
<p>
20755 32646 15599 16925 29509 29411 31544 19290 25477 30085 4973 21417
</p>
<p>
M 8 11 32373 4 7 2615 1
</p>
<p>
Q 7 7 0
</p>
<p>
M 8 10 32317 12 12 1710 3
</p>
<p>
M 4 5 28846 2 7 6548 4
</p>
<p>
Q 9 11 4
</p>
<p>
Q 12 12 4
</p>
<p>
Q 5 11 2
</p>
<p>
M 6 10 32331 6 7 1272 8
</p>
<p>
M 2 11 17117 4 9 19679 9
</p>
<p>
M 4 5 21667 4 5 13394 5
</p>
<p>
M 8 10 11508 9 11 30783 11
</p>
<p>
Q 8 9 6
</p>
<p>
<br/>
</p>
<h3>
【样例输出2】
</h3>
<p>
<br/>
</p>
<p>
31544
</p>
<p>
-101218
</p>
<p>
23127
</p>
<p>
48642
</p>
<p>
-84613
</p>
<p>
<br/>
</p>
<h3>
【样例解释】
</h3>
<p>
<br/>
</p>
<p>
第1个时刻，慧音询问第0个时刻[1,3]这个区间的妖力和，显然答案为6
</p>
<p>
第2个时刻，慧音使第1个时刻[1,2]的妖力减少1，[2,3]的妖力增加2
</p>
<p>
现在第1个时刻和第2个时刻的妖力序列都是0 3 5 4 5，而第0个时刻的妖力序列依旧是1 2 3 4 5
</p>
<p>
之后的两次询问就是在第0个时刻[1,3]的妖力和和第1个时刻[1,3]的妖力和，显然答案分别为6和8
</p>
<p>
<br/>
</p>
<h3>
【数据范围】
</h3>
<p>
<br/>
</p>
<p style="font-family:serif;font-size:16px;">
<br/>
</p>
<table class="ke-zeroborder" style="border-collapse:collapse;width:235pt;" width="313" cellspacing="0" cellpadding="0" border="0">
<tbody>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" width="72" height="24">
数据标号
</td>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" width="72">
n,m
</td>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" width="72">
ai,v,z
</td>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" width="97">
ex
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
1
</td>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
&lt;=50
</td>
<td rowspan="20" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
&lt;=10^5
</td>
<td rowspan="6" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
<br/>
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
2
</td>
<td rowspan="5" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
&lt;=500
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
3
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
4
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
5
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
6
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
7
</td>
<td rowspan="8" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
&lt;=5000
</td>
<td rowspan="2" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
只有Q操作
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
8
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
9
</td>
<td rowspan="6" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
<br/>
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
10
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
11
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
12
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
13
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
14
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
15
</td>
<td rowspan="6" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
&lt;=50000
</td>
<td rowspan="2" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
只有Q操作
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
16
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
17
</td>
<td rowspan="4" class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;">
<br/>
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
18
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
19
</td>
</tr>
<tr>
<td class="xl63" style="font-family:&#34;border:1px dotted #AAAAAA;" height="24">
20
</td>
</tr>
<tr>
<td colspan="4" class="xl64" style="font-family:&#34;border:1px dotted #AAAAAA;" width="313" height="42">
对于所有数据，保证查询和修改的目标时刻在进行操作的时刻或进行操作的时刻之前；数据有梯度
</td>
</tr>
</tbody>
</table>
<p>
<br/>
</p>
<h3>
【ex】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
