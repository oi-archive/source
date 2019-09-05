# 题目描述


<h3>
【题目描述】
</h3>
<p>
给定一个只包含加法和乘法的算术表达式，请你编程计算表达式的值。
</p>
<h3>
【输入格式】
</h3>
<p>
输入仅有一行，为需要你计算的表达式，表达式中只包含数字、加法运算符“+”和乘法运算符“*”，且没有括号，所有参与运算的数字均为0到2^31-1之间的整数。输入数据保证这一行只有0~9、+、*这12种字符。
</p>
<h3>
【输出格式】
</h3>
<p>
输出只有一行，包含一个整数，表示这个表达式的值。注意：当答案长度多于4位时，请只输出最后4位，前导0不输出。
</p>
<h3>
【样例输入1】
</h3>
<pre>1+1*3+4
</pre>
<h3>
【样例输出1】
</h3>
<pre>8</pre>
<h3>
【样例输入2】
</h3>
<pre>1+1234567890*1
</pre>
<h3>
【样例输出2】
</h3>
<pre>7891</pre>
<h3>
【样例输入3】
</h3>
<pre>1+1000000003*1
</pre>
<h3>
【样例输出3】
</h3>
<pre>4</pre>
<h3>
【样例解释】
</h3>
<p>
    样例1计算的结果为8，直接输出8。
</p>
<p>
    样例2计算的结果为1234567891，输出后4位，即7891。
</p>
<p>
    样例3计算的结果为1000000004，输出后4位，即4。
</p>
<h3>
【数据规模】
</h3>
<p>
对于30%的数据，0≤表达式中加法运算符和乘法运算符的总数≤100；
</p>
<p>
对于80%的数据，0≤表达式中加法运算符和乘法运算符的总数≤1000；
</p>
<p>
对于100%的数据，0≤表达式中加法运算符和乘法运算符的总数≤100000。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
NOIP2013普及组第二题
</p>