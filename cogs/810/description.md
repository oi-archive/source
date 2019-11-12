# 题目描述


<p align="center" style="text-align:center;">
	<b><span style="font-size:14.0pt;font-family:华文中宋;">题目<span>3  </span>老师的工资<span></span></span></b> 
</p>
<p>
	<span> </span> 
</p>
<p>
	<b><span style="font-family:宋体;">【问题描述】</span></b><span></span> 
</p>
<p>
	<span>    </span><span style="font-family:宋体;">不只是学生会在功课上偷懒，有时候老师也是一样的。对部分老师来说，如果不能够拿到足够的工资，他们的工作便不如被期望的那样努力。</span><span>Fengzee</span><span style="font-family:宋体;">给学校的校长提了一个建议，就是用合理的工资分配来使老师们工作的积极性达到最高。校长作为决策者，要考虑整个学校的</span><span>m</span><span style="font-family:宋体;">个老师，同时还要明白每年他只能在老师的工资上总共付出</span><span>n</span><span style="font-family:宋体;">万元钱（满足</span><span>m,n</span><span style="font-family:宋体;">为整数，且</span><span>m<n< span=""><span style="font-family:宋体;">）。每个老师一年得到的钱都是整万元，如果认为给某个老师发工资比较亏本，校长可以决定辞退这名老师，同时不必支付任何金钱。在某些极端情况下，甚至可以把</span><span>n</span><span style="font-family:宋体;">万元钱全部给</span><span>1</span><span style="font-family:宋体;">名老师。经过一段时间的观察，校长发现，每一个老师在每一种工资数额下，工作的积极性是不同的。现在校长要求这个建议的提出者</span><span>Fengzee</span><span style="font-family:宋体;">写一个程序，来求出在一年中校长全部利用且只利用这</span><span>n</span><span style="font-family:宋体;">万元钱的情况下，老师们最佳的总积极性。总积极性被认为是每个老师的工作积极性的和。</span><span></span> </n<></span> 
</p>
<p>
	<span>   
Fengzee</span><span style="font-family:宋体;">当然会写这个简单的程序，可是为了帮助你参加信息学竞赛，他想让你来练习一下。你的输入文件由两部分组成：第一部分有一行，用空格分隔，依次提供</span><span>m</span><span style="font-family:宋体;">和</span><span>n</span><span style="font-family:宋体;">这两个整数；第二部分是一个</span><span>m*n</span><span style="font-family:宋体;">的矩阵，假设用</span><span>a</span><span style="font-family:宋体;">表示，那么矩阵中的元素</span><span>a[i][j]</span><span style="font-family:宋体;">的值是第</span><span>i</span><span style="font-family:宋体;">个老师在拿到</span><span>j</span><span style="font-family:宋体;">万元的年薪时的工作积极性，用一个整数表示，整数的规模不会很大。值得注意的是，对有些老师来说，拿过多的钱会增长惰性，使他们的工作积极性反而不如低工资的时候高。输出文件只有一行，包含一个整数</span><span>p</span><span style="font-family:宋体;">，表示最佳分配方案下的总积极性。答案正确并不超过时限是获得测试数据全部得分的充分必要条件。</span><span></span> 
</p>
<p>
	<span> </span> 
</p>
<p>
	<b><span style="font-family:宋体;">【数据规模】</span></b><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span>1&lt;=m&lt;=15, 2&lt;=n&lt;=30</span> 
</p>
<p>
	<span> </span> 
</p>
<p>
	<b><span style="font-family:宋体;">【输入样例】</span></b><b><span style="font-family:宋体;">teacher.in</span></b><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span>5 10</span> 
</p>
<p style="text-indent:21.0pt;">
	<span>30 40 60 80 100 110 120 100 90 80</span> 
</p>
<p style="text-indent:21.0pt;">
	<span>20 50 80 100 120 130 133 134 135 136</span> 
</p>
<p style="text-indent:21.0pt;">
	<span>20 60 70 90 140 160 180 190 210 220</span> 
</p>
<p style="text-indent:21.0pt;">
	<span>30 50 70 90 110 130 150 170 190 210</span> 
</p>
<p style="text-indent:21.0pt;">
	<span>40 55 100 130 135 140 145 150 155 160</span> 
</p>
<p>
	<span> </span> 
</p>
<p>
	<b><span style="font-family:宋体;">【输出样例】</span><span>teacher.out</span></b><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span>300</span> 
</p>
<span style="font-size:10.5pt;font-family:;"><br/>
</span>
