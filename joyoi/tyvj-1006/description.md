# 

 
 # 题目背景 
NOIP2008年普及组第一题<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;每一本正式出版的图书都有一个ISBN号码与之对应，ISBN码包括9位数字、1位识别码和3位分隔符，其规定格式如“x-xxx-xxxxx-x”，其中符号“-”就是分隔符（键盘上的减号），最后一位是识别码，例如0-670-82162-4就是一个标准的ISBN码。ISBN码的首位数字表示书籍的出版语言，例如0代表英语；第一个分隔符“-”之后的三位数字代表出版社，例如670代表维京出版社；第二个分隔符后的五位数字代表该书在该出版社的编号；最后一位为识别码。&nbsp;<BR>识别码的计算方法如下：&nbsp;<BR>&nbsp;&nbsp;&nbsp;首位数字乘以1加上次位数字乘以2……以此类推，用所得的结果mod&nbsp;11，所得的余数即为识别码，如果余数为10，则识别码为大写字母X。例如ISBN号码0-670-82162-4中的识别码4是这样得到的：对067082162这9个数字，从左至右，分别乘以1，2，...,9,再求和，即0×1+6×2+……+2×9=158，然后取158&nbsp;mod&nbsp;11的结果4作为识别码。&nbsp;<BR>&nbsp;&nbsp;&nbsp;你的任务是编写程序判断输入的ISBN号码中识别码是否正确，如果正确，则仅输出“Right”；如果错误，则输出你认为是正确的ISBN号码。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;输入只有一行，是一个字符序列，表示一本书的ISBN号码（保证输入符合ISBN号码的格式要求）。&nbsp; 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;输出共一行，假如输入的ISBN号码的识别码正确，那么输出“Right”，否则，按照规定的格式，输出正确的ISBN号码（包括分隔符“-”）。 

 
 # 提示 
各个测试点1s<BR> 
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
<tr><td>【样例1】
0-670-82162-4
【样例2】
0-670-82162-0
</td><td>【样例1】
Right
【样例2】
0-670-82162-4
</td></tr></table>
