# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小Q以前玩过一个益智游戏。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这个益智游戏不是很难。给出一段程序，把这段程序分配到若干台（足够多）用电缆连接的PC上做并行执行。每台PC执行其中的某几个语句，并可随时通过电缆与其他PC通讯，交换一些中间结果。假设每台PC每单位时间可以执行一个语句，且通讯花费的时间不计。<BR>&nbsp;&nbsp;&nbsp;&nbsp;（注意：任意中间结果只有在某台PC上已经得到，才可以被其他PC引用。）<BR>&nbsp;&nbsp;&nbsp;&nbsp;这段程序里的语句都是赋值语句，里面的变量都由一个字母小写构成，不会有同一个字母被赋值多次。运算符号只有+、-、*、/。无需判断语句是否正确（如a:=x/0等）。a:=x*0也算要调用x的值。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这个游戏要求你要合适分配运算，使得时间最少。（必须按照序号执行程序，也就是说，第i句程序必须在第i-1句程序执行之后执行或者和第i-1句程序同时执行）<BR>&nbsp;&nbsp;&nbsp;&nbsp;小Q想考考你，让你告诉他在时间最少的时候，每一单位时间执行哪些语句。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行一个数N，表示有多少句语句。（1≤N≤26）<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行一个程序语句，每行不超过26个字符。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;如果无法逐行执行，输出“Oh!&nbsp;No!”<BR>对于第i单位时间，第一行输出“Step&nbsp;i:”。接下来输出在这个单位时间里执行的语句，每行一个，按照读入顺序先后输出。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在每两个单位时间之间输出26个“-”来分隔。<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;样例2里a从未被赋值，不可调用。<BR> 
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
<tr><td>【样例输入1】
7
a:=1;
b:=a;
d:=-a;
e:=a+d;
c:=2*d;
f:=b+e-d;
g:=a*f+c;
【样例输入2】
1
b:=a;
</td><td>【样例输出1】
Step 1:
a:=1;
--------------------------
Step 2:
b:=a;
d:=-a;
--------------------------
Step 3:
e:=a+d;
c:=2*d;
--------------------------
Step 4:
f:=b+e-d;
--------------------------
Step 5:
g:=a*f+c;
【样例输出2】
Oh! No!
</td></tr></table>
