# 题目描述


<p>
<span style="color:#E53333;font-size:32px;">题目更新： </span> 
</p>
<p>
<span style="color:#E53333;font-size:32px;">现在第13,14,15,16组数据满足m=n-1</span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">所有整数都是正整数</span></span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">第7,8,9,10,11,12组数据的范围更改为：n,t&lt;=40, m&lt;=50</span></span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">已添加一句话题意</span></span> 
</p>
<p>
<span style="color:#e53333;"><span style="font-size:32px;">已将样例2更换为更强的样例</span></span> 
</p>
<p>
<span style="color:#E53333;font-size:18px;"><span style="color:#000000;font-size:24px;"><br/>
</span></span> 
</p>
<p>
<span style="color:#E53333;font-size:18px;"><span style="color:#000000;font-size:24px;">请不要在代码或评论中添加任何可能引起时间以</span><span style="color:#E53333;font-size:24px;"><strong>秒</strong></span><span style="color:#000000;font-size:24px;">为单位变化的内容</span></span> 
</p>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
诹访子和神奈子需要合力帮助早苗！
</p>
<p>
早苗作为神社的风祝，有时也需要解决异变，但在一次异变中早苗遇到了非常强大的敌人，需要诹访子和神奈子的援助。诹访子打算使用符卡&#34;源符「厌川的翡翠」&#34;来帮助早苗，同时神奈子会使用藤蔓来增加诹访子符卡的威力。
</p>
<p>
符卡&#34;源符「厌川的翡翠」&#34;会放出n个翡翠，神奈子则会操纵m条藤蔓连接这些翡翠，一些翡翠可能会被藤蔓连接成一个环，但是没有两个翡翠连成的环中有相同的藤蔓，所有的翡翠都能通过藤蔓连接到其它翡翠。在战斗中诹访子可以任意将翡翠的硬度调节为[1,t]中的整数，如果第i个翡翠的硬度为j，则整个符卡会获得v[i][j]的不稳定系数，而且符卡的威力和用藤蔓连接的两个翡翠硬度的差值有关。
</p>
<p>
由于诹访子并不擅长数学，早苗又要与敌人交战，所以她请你来帮她找到一个最小的整数c，满足存在一种给翡翠设置硬度的方案，使得没有两个被藤蔓连接的翡翠硬度的差值大于c且所有翡翠的不稳定系数之和不大于w。
</p>
<p>
一句话题意：
</p>
<p>
给个仙人掌，仙人掌上每个点都能填入[1,t]中的整数，第i个点填j会获得收益v[i][j]，求一个最小的c，使得存在一种填数的方案，满足没有两个用边相邻的点填的数差值超过c且所有点的收益和不超过w
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
第一行四个整数n,m,w,t，意义如上
</p>
<p>
接下来m行，每行三个整数l和r，表示第l个铁轮和第r个翡翠用藤蔓连接在一起
</p>
<p>
接下来一个n行t列的整数矩阵，第i行第j列的数表示第i个翡翠硬度为j所获得的不稳定系数
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
如果敌人太强了诹访子和神奈子联手都无法战胜，输出-1
</p>
<p>
否则一行一个整数c，意义如上
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
5 5 5 2
</p>
<p>
1 2
</p>
<p>
1 4
</p>
<p>
3 4
</p>
<p>
4 5
</p>
<p>
3 5
</p>
<p>
1 2
</p>
<p>
2 1
</p>
<p>
1 2
</p>
<p>
2 1
</p>
<p>
1 2
</p>
<p>
<br/>
</p>
<h3>
【样例输出1】
</h3>
<p>
1
</p>
<h3>
【样例输入2】
</h3>
<p>
<br/>
</p>
<p>
10 11 20 10
</p>
<p>
1 2
</p>
<p>
1 3
</p>
<p>
3 4
</p>
<p>
2 5
</p>
<p>
3 6
</p>
<p>
6 7
</p>
<p>
3 8
</p>
<p>
1 9
</p>
<p>
1 10
</p>
<p>
1 8
</p>
<p>
1 5
</p>
<p>
7 2 3 9 9 10 10 4 4 7
</p>
<p>
1 7 1 9 3 1 1 2 4 6
</p>
<p>
1 2 10 3 5 10 3 5 5 4
</p>
<p>
1 9 3 8 4 4 2 2 3 2
</p>
<p>
2 4 1 10 7 7 8 3 8 7
</p>
<p>
9 3 8 3 2 10 7 3 10 1
</p>
<p>
3 3 7 7 4 9 3 7 10 5
</p>
<p>
9 5 8 7 1 3 2 10 5 8
</p>
<p>
9 10 10 10 4 6 2 9 4 9
</p>
<p>
7 10 8 10 2 1 4 3 9 10 
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
3
</p>
<p>
<br/>
</p>
<h3>
【数据范围】
</h3>
<p>
</p><table style="border-collapse:collapse;width:450pt;" class="ke-zeroborder" border="0" cellpadding="0" cellspacing="0" width="600">
<tbody>
<tr>
<td class="xl63" height="26" width="72">
数据标号
</td>
<td class="xl63" width="72">
n
</td>
<td class="xl63" width="72">
m
</td>
<td class="xl63" width="97">
t
</td>
<td class="xl63" width="143">
w
</td>
<td class="xl63" width="72">
v
</td>
<td class="xl81" width="72">
ex
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
1
</td>
<td colspan="3" rowspan="2" class="xl66" style="border:1.0pt solid darkgray;" width="241">
 
                   &lt;=5
</td>
<td rowspan="20" class="xl72" style="border:1.0pt solid darkgray;" width="143">
&lt;=100000
</td>
<td rowspan="20" class="xl75" width="72">
&lt;=5000000
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
2
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
3
</td>
<td colspan="3" rowspan="4" class="xl66" style="border:1.0pt solid darkgray;" width="241">
&lt;=10
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
4
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
5
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
6
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
7
</td>
<td colspan="3" rowspan="6" class="xl66" style="border:1.0pt solid darkgray;" width="241">
n,t&lt;=40, m&lt;=50
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
8
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
9
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
10
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
11
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
12
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
13
</td>
<td rowspan="8" class="xl72" style="border:1.0pt solid darkgray;" width="72">
&lt;=150
</td>
<td rowspan="8" class="xl72" style="border:1.0pt solid darkgray;" width="72">
&lt;=200
</td>
<td rowspan="8" class="xl72" style="border:1.0pt solid darkgray;" width="97">
&lt;=150
</td>
<td rowspan="4" class="xl82">
m=n-1
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
14
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
15
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
16
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
17
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
18
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl64" height="26" width="72">
19
</td>
<td>
<br/>
</td>
</tr>
<tr>
<td class="xl65" height="26" width="72">
20
</td>
<td>
<br/>
</td>
</tr>
</tbody>
</table>
<p></p>
<h3>
【ex】
</h3>
<p>
还有诹访子和神奈子联合起来都打不过的人(妖怪/神……)？
</p>
<p>
正邪啊，谁自机谁最强<img src="/upload/image/20170409/20170409070522_23627.jpg" alt=""/> 
</p>
<p>
<br/>
</p>
<p>
吓得我都去玩  <span style="font-size:32px;"><strong>弹幕天邪鬼</strong></span>  了↓↓↓
</p>
<p>
<img src="/upload/image/20170409/20170409074038_61496.jpg" alt=""/> 
</p>
