# 题目描述


<p>
	<b>【问题描述】</b><br/>
由英文字母和符号～、 *、＋、（）组成逻辑表达式，英文字母表示变量，变量有两种可能的取值，False或True；～、*、＋、括号（）可改变表达式的运算次序，且可以嵌套。
</p>
<p align="left">
	逻辑 “非”运算的公式如下表：
</p>
<div align="left">
	<table border="1" cellspacing="0" cellpadding="0" width="121">
		<tbody>
			<tr>
				<td valign="top" width="58">
					<p>
						A
					</p>
				</td>
				<td valign="top" width="57">
					<p>
						～ A
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="58">
					<p>
						TRUE
					</p>
				</td>
				<td valign="top" width="57">
					<p>
						FALSE
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="58">
					<p>
						FALSE
					</p>
				</td>
				<td valign="top" width="57">
					<p>
						TRUE
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</div>
<p align="left">
	逻辑 “与”和逻辑“或”的运算公式如下表：
</p>
<div align="left">
	<table border="1" cellspacing="0" cellpadding="0" width="252">
		<tbody>
			<tr>
				<td valign="top" width="59">
					<p>
						A
					</p>
				</td>
				<td valign="top" width="61">
					<p>
						B
					</p>
				</td>
				<td valign="top" width="62">
					<p>
						A*B
					</p>
				</td>
				<td valign="top" width="60">
					<p>
						A+B
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="59">
					<p>
						FALSE
					</p>
				</td>
				<td valign="top" width="61">
					<p>
						FALSE
					</p>
				</td>
				<td valign="top" width="62">
					<p>
						FLASE
					</p>
				</td>
				<td valign="top" width="60">
					<p>
						FLASE
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="59">
					<p>
						FALSE
					</p>
				</td>
				<td valign="top" width="61">
					<p>
						TRUE
					</p>
				</td>
				<td valign="top" width="62">
					<p>
						FLASE
					</p>
				</td>
				<td valign="top" width="60">
					<p>
						TRUE
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="59">
					<p>
						TRUE
					</p>
				</td>
				<td valign="top" width="61">
					<p>
						FALSE
					</p>
				</td>
				<td valign="top" width="62">
					<p>
						FALSE
					</p>
				</td>
				<td valign="top" width="60">
					<p>
						TRUE
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="59">
					<p>
						TRUE
					</p>
				</td>
				<td valign="top" width="61">
					<p>
						TRUE
					</p>
				</td>
				<td valign="top" width="62">
					<p>
						TRUE
					</p>
				</td>
				<td valign="top" width="60">
					<p>
						TRUE
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</div>
<p align="left">
	两个逻辑表达式等价，当且仅当两个公式中相同名字的变量取任何一种值时两个公式的值都相同。如：
</p>
<p align="left">
	A*(B+C) 与 A*B+A*C 等价 <br/>
A*(～A+B) 与 A*B 等价 <br/>
(～A+A)*B+C 与 B+C 等价 <br/>
A*B+A*～B 与 A 等价 <br/>
而：
</p>
<p align="left">
	A+B 与 A*B 不等价 <br/>
A*B+～C 与 A*E+～F 不等价
</p>
<p align="left">
	现要求你编程解决下列问题：
</p>
<p align="left">
	任务 1 :读取一个逻辑表达式，判断这个表达式的合法性；
</p>
<p>
	【输入格式1】 <br/>
    输入文件只有一行，一个字符串s,s的长度不超过255。
</p>
<p>
	【输出格式1】 <br/>
   输出文件只有一个单词，yes或no。 表达式合法时输出yes，不合法时输出no。<br/>
【输入输出样例1】 <b><br/>
</b>输入:<br/>
expressa.in<br/>
(A+B)*(A-B)
</p>
<p>
	输出:<br/>
expressa.out<br/>
no
</p>
<p>
	(注：逻辑运算中没有&#34;-&#34;运算)
</p>
<p>
	<strong>任务2：</strong>
</p>
<p align="left">
	将读入的表达式化简，化简的表达式为 <br/>
a1*a2*…*aN+b1**b2*…*bM+…+x1*x2*…*xL <br/>
其中 ai、bj、…xk(i=1,2,…n; j=1,2,…m; k=1,2,…L)表示一个变量或一个变量的逻辑非；
</p>
<p>
	【输入输出样例2】 <b><br/>
</b>输入:<br/>
expressb.in <br/>
（A+B)*C
</p>
<p>
	输出:<br/>
expressb.out<br/>
A*C+B*C
</p>
