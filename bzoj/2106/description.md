
# Description

<div class="content">我们都知道，后缀表达式（也称为逆波兰式）是一种不需要括号就能描述算术表达式的方法。对于一个单独的变量，它的后缀表达式就是本身；而对于一个表达式A#B（这里A和B都是表达式而#是最后一次计算的运算符），它的后缀表达式是由A的后缀表达式，B的后缀表达式和#连接而成的。举例来说，((a+f)*b)*(c*d)的后缀表达式为af+b*cd**。
	
给定一个仅有变量和运算符组成的后缀表达式。在本题中，所有的变量均由一个小写字母表示；所有的运算符都是二元的，并且均满足结合律与交换律，也就是说，对于任何一个运算符#，表达式A、B和C，下面的两条性质始终成立：
	结合律：A#(B#C)=(A#B)#C。
	交换律：A#B=B#A。

你可以根据结合律与交换律调整操作数的顺序，举例来说，对于上面提到过的表达式：
	将表达式((a+f)*b)*(c*d)调整为d*((a+f)*(b*c))。
	同时，后缀表达式从af+b*cd**变为daf+bc***。

你的任务就是寻找一个最有的调整方案，使得调整后的后缀表达式的RLE长度最小。一个字符串的RLE长度是这个字符串中连续相同字符块的个数（也就是说，字符串xx+yy+zz+**的RLE长度为7）。

数据规模：
输入表达式的长度不超过2500。
</div>

# Input

<div class="content">一个合法的后缀表达式</div>

# Output

<div class="content">最短的RLE长度</div>

# Sample Input

<div class="content"><span class="sampledata">af+b*cd**</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=SRM 327">SRM 327</a></p></div>

