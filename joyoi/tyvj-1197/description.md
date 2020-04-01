# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;计算机使用的是二进制，和十进制不同的是：二进制运算“逢二进一”。下面举几个二进制加法的运算实例:<BR>例1（整数）：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;例2（含小数）：<BR>&nbsp;11101&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11101.1011<BR>+&nbsp;&nbsp;110&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+&nbsp;&nbsp;110.11<BR>------&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-----------<BR>100011&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100100.0111<BR>1所在的位置：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1所在的位置：<BR>6、2、1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6、3、-2、-3、-4<BR><BR>你的任务是：对于任意的两个正的二进制数，求它们和中“1”所在的位置（其中小数点后面的位置用负数表示）。 

 
 # 输入格式 
输入文件共两行：<BR>第一行：二进制的加数A，总长度&lt;=200<BR>第二行：二进制的加数B，总长度&lt;=200 

 
 # 输出格式 
输出文件输出二进制数A+B中“1”所在的位置，位置排序为：整数部分从左到右：N、N-1、N-2...1，小数部分从左到右：-1、-2、......、-N，数据之间用空格分隔，行末没有多余的空格，有空行。 

 
 # 提示 
数据范围：<BR>40%的数据：A、B均为正整数，总长度&lt;=31<BR>70%的数据：A、B含小数，小数位数相等，总长度&lt;=200<BR>100%的数据：A、B可能含小数，小数位数可能不相等，总长度&lt;=200 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>样例输入1：
11101
110

样例输入2：
11101.1011
110.11
</td><td>样例输出1：
6 2 1

样例输出2：
6 3 -2 -3 -4
</td></tr></table>
