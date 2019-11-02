# 

 
 # 题目描述 
<p>
背景 Background  <br>　　Dragon.Dai在某次学习的过程中遇到了一个难题。你能帮帮他吗？<br><br>描述 Description   <br>　　Dragon.Dai在学习后缀表达式的时候觉得后缀表达式不好看，他想写一个程序把后缀表达式转换成中缀表达式，可是他不会。怎么办呢？你能帮忙吗？<br><br>---------概念--------<br>　　通常书写的算术表达式是把运算符放在两个操作数之间（又叫运算对象或运算量）的中间。如对于2+5*6，乘法运算符"*"的两个操作符是它两边的5和6；加法运算符“+”的两个操作数，一个是它前面的2，另一个是它后面的5*6即30。我们把算术表达式的这种表示叫做中缀表示：采用中缀表示的算术表达式简称中缀表达式。<br>而后缀表达式，其定义是将运算符放在两个运算对象的后面。采用后缀表示的算术表达式简称后缀表达式。需要注意的是，后缀表达式没有括号。 <br></p> 

 
 # 输入格式 
<p>
输入格式 Input Format  <br>　　一个后缀表达式，由大写字母及”+、-、*、/“四则运算符号组组成，总长度小于等于200字符。<br></p> 

 
 # 输出格式 
<p>
输出格式 Output Format  <br>　　这个后缀表达式指定的中缀表达式，注意要有括号。<br></p> 

 
 # 提示 
<p>
注释 Hint  <br>　　注意括号……,不用加不必要的括号！！<br>来源 Source  <br>　　[CoVH]Dragon.Dai<br></p> 
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
<tr><td>样例输入 Sample Input   
   CAB+-
</td><td>样例输出 Sample Output   
   C-(A+B)</td></tr></table>
