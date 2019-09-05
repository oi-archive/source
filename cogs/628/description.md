# 题目描述


<div>
	【问题描述】
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	小云和小吉很喜欢玩数学游戏，特别是运算符游戏。小云负责写一条等式，该式子由整数组成，还有“+”、“-”、“*”三个运算符，还有一个“=”，该式子遵守先乘除后加减的方式进行运算。然后他把式子里面的运算符去掉，只剩下一列数字。然后，他告诉小吉从左到右拿走了什么运算符（包括“=”），让小吉填上去。
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	一开始，小云给了一条简单的式子， 123*2-51=195，去掉运算符后数列为 123251195，然后他告诉小吉去掉的运算符是：*-= ，小吉很快就做出来了。然后，小云写了一个几十位数字的式子，这次小吉犯难了，你能帮助他吗？
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 
</div>
<div>
	【输入格式】
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	输入有两行
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	第一行为由0-9组成的数字序列，长度不超过50位
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	第二行为运算符序列，长度不超过6个运算符。
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	注意：
</div>
<div style="margin:0cm 0cm 0pt 60pt;">
	<span>1、 </span>运算符序列里面，有且只有一个“=”，其余的符号为“+”、“-”、“*”中的一个；
</div>
<div style="margin:0cm 0cm 0pt 60pt;">
	<span>2、 </span>输入的数据保证有解。
</div>
<div style="margin:0cm 0cm 0pt 42pt;">
	 
</div>
<div>
	【输出格式】
</div>
<div>
	<span>              </span>输出只有一行，就是原来的等式。
</div>
<div>
	<span>              </span>
</div>
<div>
	<span>              </span>注意：
</div>
<div style="margin:0cm 0cm 0pt 60pt;">
	<span>1、 </span>输入的数据保证至少有一个解，如果存在多个解，只需要输出一个即可；
</div>
<div style="margin:0cm 0cm 0pt 60pt;">
	<span>2、 </span>输出的式子中，运算符均为二元运算符，就是说“+”、“-”不会作为正数、负数的标记；
</div>
<div style="margin:0cm 0cm 0pt 60pt;">
	<span>3、 </span>输出的式子中的各个整数，前面不会有多余的“0”
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 
</div>
<div>
	【输入样例】
</div>
<div>
	<span>              123251195</span>
</div>
<div>
	<span>              *-= </span>
</div>
<div>
	【输出样例】
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	  123*2-51=195
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
	 
</div>
