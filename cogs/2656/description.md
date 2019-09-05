# 题目描述


<h3>
【题目描述】
</h3>
<p>
经过长时间一轮复习的洗礼，Mike早已心力憔悴，各项营养物质极大不足，甚至低于体检表下线。
</p>
<p>
人体的营养物质一共分为n种，第i种营养物质有一个正常范围[li,ri]毫克，而Mike身体情况有波动，但经过长期的观察，Mike体内第i中营养物质的含量总是在[Li,Ri]毫克之间（Ri&lt;li）。为了补充营养，Mike找到了营养师，营养师给出了m种食物，其中每千克第i种食物中第j中营养物质含量为kij毫克，并且Mike能全部吸收。
</p>
<p>
Mike很懒，于是想要配出一份完美的食物配方，使得无论Mike的各项营养物质含量是多少，吃了这份配方后总能够恢复到正常范围。于是Mike找到了你，希望你能告诉Mike，Mike最少需要吃多少毫克食物。如果无论如何Mike的心愿也不能实现，请输出&#34;FoolMike&#34;（不带引号）。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行有一个整数n。
</p>
<p>
接下来n行，每行有四个整数li，ri，Li，Ri。
</p>
<p>
接下来一个整数m。
</p>
<p>
接下来m行，每行n个整数，对应ki1到kin。
</p>
<p>
保证读入数据均是非负整数。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行，如果有解，请四舍五入取整后输出；否则请输出&#34;FoolMike&#34;。在COGS标程使用了double，分赛场同学请一定使用long double，校内OJ精度有点问题，还望见谅。
</p>
<h3>
【样例输入】
</h3>
<pre>2
5 8 1 3
7 11 0 0
3
1 2
2 3
3 4
</pre>
<h3>
【样例输出】
</h3>
<pre>2000000
</pre>
<h3>
【提示】
</h3>
<p>
对于所有数据，满足n,m&lt;=100，其他非负整数都不超过int范围
</p>
<p>
数据绝对不是随机生成的，暴力骗分请自觉弃疗。
</p>
<p>
最后还有10组无任何特殊条件的数据。
</p>
<p>
具体数据特征如下：
</p>
<p>
</p><table class="MsoNormalTable" style="width:100.0%;border:outset black 1.0pt;" border="1" cellpadding="0" cellspacing="0" width="100%">
<tbody>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">数据编号<span></span></span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m</span><span style="font-size:12.0pt;font-family:宋体;">范围<span></span></span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">特殊条件<span></span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">1</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=3</span><span style="font-size:12.0pt;font-family:宋体;">，<span>li,ri&lt;=1e7</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">2</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=10</span><span style="font-size:12.0pt;font-family:宋体;">，<span>li,ri&lt;=1e6</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">3</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=10</span><span style="font-size:12.0pt;font-family:宋体;">，<span>li,ri&lt;=1e6</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">4</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=10</span><span style="font-size:12.0pt;font-family:宋体;">，<span>li,ri&lt;=1e6</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">5</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=10</span><span style="font-size:12.0pt;font-family:宋体;">，<span>li,ri&lt;=1e6</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">6</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=10</span><span style="font-size:12.0pt;font-family:宋体;">，<span>li,ri&lt;=1e6</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">7</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n,m&lt;=30</span><span style="font-size:12.0pt;font-family:宋体;">且<span>n=m</span></span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">对于每一个<span>i</span>，至多存在一个<span>j</span>，使得<span>kij!=0</span>，且<span>li=ri</span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">8</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n=2</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=100<span></span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">9</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n=2</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=100<span></span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">10</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">n=2</span> 
</p>
</td>
<td style="border:inset black 1.0pt;">
<p class="MsoNormal" style="text-align:left;" align="left">
<span style="font-size:12.0pt;font-family:宋体;">kij&lt;=100</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p></p>
<h3>
【来源】
</h3>
<p>
Mike
</p>
