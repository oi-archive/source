# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;Livid&nbsp;最近发现了一个神奇的机器，这个机器的所有操作都是通过维护一个栈来完成的，它支持如下几个操作：</p>

<p>NUM&nbsp;X：把X这个元素放置栈顶。<br />
POP&nbsp;X：抛弃栈顶元素。<br />
INV：将栈顶元素取出，然后放入它的相反数。<br />
DUP：再放入一个和栈顶元素相同的数。<br />
SWP：交还栈顶的两个元素。<br />
ADD：将栈顶的两个元素相加然后放入栈内。<br />
SUB：取出栈顶的两个元素，第二个元素减去第一个元素，所得结果放入栈内。<br />
MUL：将栈顶的两个元素相乘然后放入栈内。<br />
DIV：取出栈顶的两个元素，第二个元素整除以第一个元素，所得结果放入栈内。<br />
MOD：取出栈顶的两个元素，第二个元素取模以第一个元素，所得结果放入栈内。<br />
END：结束这个程序。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;然后，Livid&nbsp;用上面的11种操作写了一个一元函数f(x)。x就是放入栈里面第一个初始元素。然后经过这个函数的一系列操作，当函数结束的时候，正常情况下，栈里面会有唯一的一个元素。剩下的这个元素就作为函数f(x)的返回值。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;Livid&nbsp;有N个询问，询问每个值x经过上述函数所映射出的f(x)是多少。但是这个由于机器太老了，跑起东西来太慢了T_T，&nbsp;Livid&nbsp;又是一个急性子（你们懂。。）所以请你们写一个程序，来帮助&nbsp;Livid&nbsp;计算他查询的f(x)^_^。</p> 

 
 # 输入格式 
<p>输入若干行。</p>

<p>仅包含上述11个操作，用来描述函数f(x)的操作，函数的结束保证以END结尾。</p>

<p>接下来一个整数N。</p>

<p>下面N行每行一个数字ai，代表栈里面的初始元素。</p>

<p>输入数据不保证合法（我很没有节操~</p> 

 
 # 输出格式 
<p>如果最后栈内是一个元素，输出这个元素，否则输出ERROR!</p>

<p>还有，由于这台机器太破了，所以如果运算过程中有数字的绝对值大于1e9机器也会ERROR!</p>

<p>如果输入数据不合法，导致中途退出，输出ERROR!</p> 

 
 # 提示 
<p>仔细考虑不合法的情况，避免不必要的RE和WA。</p>

<p>函数操作步数&lt;=2000</p>

<p>询问数&lt;=2000</p> 
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
<tr><td>NUM 600000000
ADD
END
3
0
600000000
1</td><td>600000000
ERROR
600000001</td></tr></table>
