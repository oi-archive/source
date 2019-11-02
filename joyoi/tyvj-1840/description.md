# 

 
 # 题目背景 
JSOI2009第三轮二试 

 
 # 题目描述 
&nbsp;&nbsp;Luna进了中学之后，学到了代数表达式，但是表达式中总是会出现很多让人烦恼的括号，而实际上，有很多括号是可以去除掉的。比如说a+(b+c)-d就可以把括号去除，变为a+b+c-d。而a-(b+a)+d可以去除括号后变为a-b-a+d。Luna对计算机编程很感兴趣，所以她想是不是可以用计算机来解决这个问题。你能帮助她完成这个任务吗？&nbsp;<BR>&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入的第一行有一个整数N。表示总共有N个表达式需要处理。接下来N行，每一行一个待处理的表达式，长度不超过255,&nbsp;并且不含空格字符。表达式中的所有变量都是单个小写的英文字母,&nbsp;运算符只有加+减-乘*除/。也就是说，在表达式中可能出现的字符为：a-z，+，-，*，/，()。数据保证表达式合法。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;另外不考虑'+'&nbsp;'-'用作正负号的情况，即输入表达式不会出现(+a)或(-a)的情形。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;对于每个表达式输出去除括号后的表达式。&nbsp; 

 
 # 提示 
N&lt;=10<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;不需要对表达式进行化简：如果表达式为a-a，答案同表达式。不需要为了消去括号进行展开：如表达式为(a+b)*(c+d)，答案同表达式。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;更具体的，若表达式原先出现了m次变量，则输出时仍应保持m次变量，且不应改<BR>变这些变量的顺序。见样例。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;另外，保证不会出现空串的情形，既不会出现()。保证表达式均合法。&nbsp; 
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
<tr><td>9 
(a-a) 
a+(b+c)-d 
a-(b+a)+d 
(a+b)*(c+d) 
(a*b)+c/d 
((a+b)*f)-(i/j) 
a*(b/c) 
a-(b+c+(d*a)) 
a*b*c*d*e*f*g*h*i*j*k*l*m*n*o*(p-q)+r*(s*t)*(u-(v+(w*x))*y)+z </td><td>a-a 
a+b+c-d 
a-b-a+d 
(a+b)*(c+d) 
a*b+c/d 
(a+b)*f-i/j 
a*b/c 
a-b-c-d*a  
a*b*c*d*e*f*g*h*i*j*k*l*m*n*o*(p-q)+r*s*t*(u-(v+w*x)*y)+z
</td></tr></table>
