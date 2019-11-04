# 

 
 # 题目描述 
<p>所谓虫食算，就是原先的算式中有一部分被虫子啃掉了，需要我们根据剩下的数字来判定被啃掉的字母。来看一个简单的例子：<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;43#9865#045<br />
&nbsp;&nbsp;&nbsp;&nbsp;+&nbsp;&nbsp;&nbsp;&nbsp;8468#6633<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;44445506978<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;其中#号代表被虫子啃掉的数字。根据算式，我们很容易判断：第一行的两个数字分别是5和3，第二行的数字是5。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;现在，我们对问题做两个限制：<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;首先，我们只考虑加法的虫食算。这里的加法是N进制加法，算式中三个数都有N位，允许有前导的0。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;其次，虫子把所有的数都啃光了，我们只知道哪些数字是相同的，我们将相同的数字用相同的字母表示，不同的数字用不同的字母表示。如果这个算式是N进制的，我们就取英文字母表午的前N个大写字母来表示这个算式中的0到N-1这N个不同的数字：但是这N个字母并不一定顺序地代表0到N-1)。输入数据保证N个字母分别至少出现一次。<br />
<br />
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BADC<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CRDA<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DCCC<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;上面的算式是一个4进制的算式。很显然，我们只要让ABCD分别代表0123，便可以让这个式子成立了。你的任务是，对于给定的N进制加法算式，求出N个不同的字母分别代表的数字，使得该加法算式成立。输入数据保证有且仅有一组解，</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;输入文件alpha.in包含4行。第一行有一个正整数N(N&lt;=26)，后面的3行每行有一个由大写字母组成的字符串，分别代表两个加数以及和。这3个字符串左右两端都没有空格，从高位到低位，并且恰好有N位。</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;输出文件alpha.out包含一行。在这一行中，应当包含唯一的那组解。解是这样表示的：输出N个数字，分别表示A，B，C&hellip;&hellip;所代表的数字，相邻的两个数字用一个空格隔开，不能有多余的空格。</p> 
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
<tr><td>5
ABCED
BDACE
EBBAA</td><td>1 0 3 4 2</td></tr></table>