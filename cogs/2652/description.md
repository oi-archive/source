# 题目描述


<p>
<br/>
</p>
<p>
<span style="color:#E53333;font-size:32px;">题目说明：</span> 
</p>
<p>
<span style="color:#E53333;font-size:32px;">路径的长度是点数</span> 
</p>
<p>
<span style="color:#E53333;font-size:32px;">所有整数都是正整数</span> 
</p>
<p>
<span style="color:#E53333;font-size:32px;">已添加一句话题意</span> 
</p>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
永琳需要协助紫解决异变！
</p>
<p>
在某个满月的夜晚，幻想乡的结界出现了异常，虽然目前还没有找到原因，不过有一点可以肯定的是，这次异变一定和满月有关。间隙妖怪紫在试图修复结界时需要永琳帮她排除满月产生的干扰，为了保护辉夜公主，永琳必须协助紫解决这次异变，所以她打算再次使用符卡&#34;秘术「天文密葬法」&#34;来用虚假的月亮替换真实的满月，但是她在使用符卡的时候出现了一些问题。
</p>
<p>
&#34;秘术「天文密葬法」&#34;由n个使魔组成，每个使魔都有一个能值和一个波值，同时存在n-1条能量通道将这n个使魔连接起来，并且每个使魔都能通过能量通道和其它所有使魔相连。
</p>
<p>
完成天文密葬法的关键步骤是在这n个使魔中找到一条用能量通道连接起来的路径，将大部分能量集中于这条路径来展开法术，然而路径上的使魔在法术张开时会产生共振，产生一个干扰值，干扰值等于路径上所有使魔能值的和除以波值的和。
</p>
<p>
为了确保计划顺利进行，永琳需要选择一条长度为m且干扰值最小的路径，虽然作为月之头脑，但此时永琳需要集中精力展开法术，所以她向你求助。
</p>
<p>
永琳在知道一个干扰值后就能快速找到这个干扰值对应的路径，你只需要告诉她所有路径中干扰值最小的路径干扰值是多少
</p>
<p>
答案四舍五入到小数点后两位
</p>
<p>
一句话题意：
</p>
<p>
给个树，第i个点有两个权值ai和bi，现在求一条长度为m的路径，使得Σai/Σbi最小
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
第一行一个整数n,m，意义如上
</p>
<p>
如果m为-1则表示对长度没有限制（但路径不能为空
</p>
<p>
第二行n个整数，第i个整数ai表示第i个使魔的能值
</p>
<p>
第三行n个整数，第i个整数bi表示第i个使魔的波值
</p>
<p>
接下来n-1行，每行两个整数l,r，表示有一条能量路径连接第l个使魔和第r个使魔
</p>
<p>
一行中的所有整数均用空格隔开
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
如果不存在长度为m的链，请输出-1
</p>
<p>
否则一行一个浮点数，表示干扰值最小的路径干扰值是多少
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
3 2
</p>
<p>
2 3 3
</p>
<p>
6 6 6
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
<br/>
</p>
<h3>
【样例输出1】
</h3>
<p>
0.42
</p>
<h3>
【样例输入2】
</h3>
<p>
<br/>
</p>
<p>
9 3
</p>
<p>
9 4 4 1 6 5 1 9 5
</p>
<p>
8 3 3 1 5 4 1 8 4
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
3 4
</p>
<p>
3 5
</p>
<p>
1 6
</p>
<p>
6 7
</p>
<p>
7 8
</p>
<p>
6 9
</p>
<p>
<br/>
</p>
<h3>
【样例输出2】
</h3>
<p>
1.15
</p>
<h3>
【数据范围】
</h3>
<p>
</p><table style="border-collapse:collapse;width:235pt;" class="ke-zeroborder" border="0" cellpadding="0" cellspacing="0" width="313">
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
ai,bi
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
1
</td>
<td rowspan="2" class="xl67" width="72">
&lt;=10
</td>
<td rowspan="2" class="xl65" align="right" width="72">
=1
</td>
<td rowspan="20" class="xl67" width="97">
&lt;=200000
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
2
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
3
</td>
<td rowspan="4" class="xl67" width="72">
&lt;=1000
</td>
<td rowspan="14" class="xl67" width="72">
&lt;=n
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
4
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
5
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
6
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
7
</td>
<td rowspan="10" class="xl67" width="72">
&lt;=30000
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
8
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
9
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
10
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
11
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
12
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
13
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
14
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
15
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
16
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
17
</td>
<td rowspan="4" class="xl67" width="72">
&lt;=200000
</td>
<td rowspan="4" class="xl67" width="72">
=-1
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
18
</td>
</tr>
<tr>
<td class="xl64" align="right" height="26" width="72">
19
</td>
</tr>
<tr>
<td class="xl63" align="right" height="26" width="72">
20
</td>
</tr>
</tbody>
</table>
<p></p>
