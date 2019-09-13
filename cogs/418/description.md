# 题目描述


<p>
	<strong>试题描述 </strong>
</p>
<p>
	所谓回文串，就是对于给定的字符串，正着读和反着读都一样，比如 ABCBA 就是一个回文串， ABCAB 则不是。我们的目标是对于任意输入的字符串，不断将第 i 个字符和第 i+1 个字符交换，使得该串最终变为回文串。求最少交换次数。
</p>
<p>
	<strong>数据输入 </strong>
</p>
<p>
	在文本文件 string!.in 中包含一个由大写字母字母组成的字符串。
</p>
<p>
	<strong>数据输出 </strong>
</p>
<p>
	在文本文件 string!.out 中写入一个整数。若能经过有限次操作能将原串变为回文串，则输出最少操作次数；否则输出 -1 。
</p>
<p>
	<strong>样例输入 </strong>
</p>
<p>
	SHLLZSHZS
</p>
<p>
	<strong>样例输出 </strong>
</p>
<p>
	4
</p>
<p>
	<strong>样例说明 </strong>
</p>
<p>
	1 ．交换 L 和 Z 变成 SHL ZL SHZS
</p>
<p>
	2 ．交换 L 和 Z 变成 SH ZL LSHZS
</p>
<p>
	3 ．交换 L 和 S 变成 SHZL SL HZS
</p>
<p>
	4 ．交换 H 和 Z 变成 SHZLSL ZH S
</p>
<p>
	<br/>
</p>
<p>
	<strong>测试数据范围 </strong>
</p>
<p>
	40% 的数据， N ≤ 50000
</p>
<p>
	100% 的数据， N ≤ 10^6
</p>
