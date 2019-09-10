# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
	<br/>
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">wikipedia上提供的一段背景资料：“集合理论是数学理沦的一个分支，它主要由德国数学家Georg cantor在19世纪末创立。集合理论已经逐渐成为现代数学的基本理论。正式的集合理论学说为数学证明的严格性提供了保障。”</span> 
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">一些古怪的理论工作者开始构造一个超级计算机，用来实现集合之间的操作，而不再是数字之间的操作。他们希望你来帮他们模拟一下集合运算的过程。</span> 
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">计算机的操作对象是一个以集合为元素的栈，一开始这个栈是空的。在每一步操作之后，栈顶集合中所含元素的个数是需要你输出的东西。计算机的操作指令有PUSH，DUP，UNION，INTERSECT，ADD。</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·PUSH操作将一个空集合{}入栈</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·DUP操作将把一个和栈顶元素相同的集合入栈</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·UNION操作进行两次出栈操作，并且把出栈的两个集合的并入栈</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·INTERSECT操作进行两次出栈操作，并且把出栈的两个集合的交入栈</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·ADD操作进行两次出栈操作，并且把第一个出栈的集合作为一个元素，放入第二个出栈的集合中，然后把这个结果入栈</span> 
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">举一个例子，假设栈顶的元素是A={{}，{{}}}，而它下面的一个元素是B={{}，{{{}}}}。</span> 
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">显然，集合A有2个元素，集弁B也是。对于这个情况：</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·UNION操作会产生集合{{}，{{}}，{{{}}}}，这个集合有3个元素，所以要输出3</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·INTERSECT操作会产生{{}}，所以要输出1</span> 
</p>
<p style="vertical-align:;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">·ADD操作会产生{{}，{{{}}}，{{}，{{}}}}，所以要输出3</span> 
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	第一行一个整数N，保证0≤N≤2000。
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	接着的N行，每行有一条指令。保证输入的指令是合法的，不会出现让你在一个空的栈中弹出元素的情况。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	对于输入中的每一条指令，输出执行指令之后栈顶集合里的元素个数。
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>9
PUSH
DUP
ADD
PUSH
ADD
DUP
ADD
DUP
UNION</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>0
0
1
0
1
1
2
2
2</pre>
