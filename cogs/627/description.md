# 题目描述


<div>
	【问题描述】
</div>
<div>
	相信大家都用过计算器，一般来说，计算机都可以计算简单的 加、减、乘、除这几种运算。简易计算器的功能和一般的计算器一样，只是它更加简单，只能处理整数运算，也就是说，它没有小数点按钮，并且它的除法运算是整除运算。
</div>
<div>
	现在，我们给出简易计算器上的按钮序列，请你编程序，模拟简易计算器的功能，输出最终的结果。
</div>
<div>
</div>
<div>
	【计算器组成】
</div>
<div>
	简易计算器由以下按钮组成：
</div>
<div>
	数字按钮： 0 1 2 3 4 5 6 7 8 9
</div>
<div>
	运算按钮： + - * /
</div>
<div>
	等于号按钮：=
</div>
<div>
	正负转换按钮：+/-
</div>
<div>
	为了表述方便，+/- 按钮用 F 表示 ，
</div>
<div>
</div>
<div>
	【计算器逻辑处理】
</div>
<div>
	计算器内存有3个值，M1，M2，OP，ST
</div>
<div>
	M1为计算器的左运算值，初始值为0
</div>
<div>
	M2为计算器的右运算值，初始值0
</div>
<div>
	OP为计算器的当前运算符，初始值为空
</div>
<div>
	ST为状态标记，初始值为0
</div>
<div>
</div>
<div>
	状态装换逻辑如下：
</div>
<div>
</div>
<div>
	ST=0(M1/OP输入态)：
</div>
<div>
	显示值：M1
</div>
<div>
	输入数字N ：
</div>
<div>
	M1=N ，转 ST=1状态
</div>
<div>
	输入F ：
</div>
<div>
	M1=-M1，转 ST=0状态
</div>
<div>
	输入运算符：
</div>
<div>
	OP=运算符，转ST=2状态
</div>
<div>
	输入“=”：
</div>
<div>
	转 ST=0状态
</div>
<div>
</div>
<div>
	ST=1(M1+/OP输入态)：
</div>
<div>
	显示值：M1
</div>
<div>
	输入数字N ：
</div>
<div>
	如果M1&gt;=0则 M1=M1*10+N 否则M1=M1*10-N;
</div>
<div>
	转 ST=1状态；
</div>
<div>
	输入F ：
</div>
<div>
	M1=-M1，转 ST=1状态；
</div>
<div>
	输入运算符：
</div>
<div>
	OP=运算符，转ST=2状态
</div>
<div>
	输入“=”：
</div>
<div>
	转 ST=0状态
</div>
<div>
</div>
<div>
	ST=2(OP/M2输入态)：
</div>
<div>
	显示值：M1
</div>
<div>
	输入数字N：
</div>
<div>
	M2=N，转ST=3状态;
</div>
<div>
	输入F：
</div>
<div>
	M2=0，转 ST=3状态；
</div>
<div>
	输入运算符：
</div>
<div>
	OP=运算符，转ST=2状态
</div>
<div>
	输入“=”：
</div>
<div>
	转 ST=0状态
</div>
<div>
</div>
<div>
	ST=3(M2+/OP输入态)：
</div>
<div>
	显示值：M2
</div>
<div>
	输入数字N：
</div>
<div>
	如果M2&gt;=0则 M2=M2*10+N 否则M2=M2*10-N；
</div>
<div>
	转ST=3状态；
</div>
<div>
	输入F：
</div>
<div>
	M2=-M2，转 ST=3状态；
</div>
<div>
	输入运算符：
</div>
<div>
	M1=[M1][OP][M2] 的值
</div>
<div>
	OP=运算符；
</div>
<div>
	转ST=2状态
</div>
<div>
	输入“=”： 转 ST=0状态
</div>
<div>
	M1=[M1][OP][M2] 的值
</div>
<div>
	转ST=0状态
</div>
<div>
</div>
<div>
	【输入格式】
</div>
<div>
	输入只有一行，表示在计算器输入的按钮，长度&lt;=100，里面只包含如下字符 :
</div>
<div>
	0123456789+-*/=F
</div>
<div>
	输入数据保证不会出现除以0的 情况，运算过程中各个内存的值的范围在
</div>
<div>
	[-10000000, 10000000] 以内
</div>
<div>
</div>
<div>
</div>
<div>
	【输出格式】
</div>
<div>
	输出包含一行整数，表示最后在计算器显示的结果
</div>
<div>
</div>
<div>
	【输入样例】
</div>
<div>
	123=*2F-+/3+-=
</div>
<div>
</div>
<div>
	【输出样例】
</div>
<div>
	-82
</div>
<div>
</div>
