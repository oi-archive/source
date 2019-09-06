# 题目描述


<h3>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">【问题描述】</span>
</h3>
<p>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">用链表实现的可合并堆一个可合并堆支持这样几种操作：MAKEHEAP(创建一个空的可合并堆)，INSERT,MINIMUM,EXTRACTMIN和UNION。说明在下列每一情况中，如何用链表实现可合并堆.尽量使每种操作高效. 为使输入输出方便,作如下指令编号约定: 1号操作:MAKEHEAP 创建一个空的可合并堆 1 4 表示执行1号建堆指令,创建一个堆,该堆编号为4,即4号堆 2号操作:INSERT 堆插入操作 2 4 56 表示执行2号插入指令,向4号堆插入整数56(如果4号堆不存在则输出&#34;insert error!&#34;) 3号操作:EXTRACTMIN 删除堆最小值,并输出 3 4 表示执行3号删除指令,删除4号堆最小值,并输出(如果4号堆不存在或4号堆为空则输出&#34;extract error!&#34;) 4号操作:UNION 合并堆 4 2 4 表示执行2号合并指令将2号堆,4号堆合并,该合并将两个堆合并至2号堆,合并4号堆为空堆(若2号堆或4号堆不存在则输出&#34;union error!&#34;) </span>
</p>
<h3>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span>
</h3>
<p>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">输入文件第一行，一个整数n,表示指令的条数；下面第2--n+1行,每行一条指令,每行若干个用一个空格隔开的整数,第1个整数表示指令编号,其余参数含义如题描述. </span>
</p>
<h3>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span>
</h3>
<p>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;"> 输出有n行，每行表示一个指令的执行结果,如果该指令没有任何输出则显示0,如果有则按指令要求输出信息。 </span>
</p>
<h3>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">【输入输出样例】</span>
</h3>
<p>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">输入文件名：uheap.in 9 1 1 1 2 1 3 2 1 6 2 1 5 2 1 4 2 3 3 4 1 3 3 1 </span>
</p>
<p>
	<span style="font-size:small;font-family:&#39;Microsoft YaHei&#39;;">输出文件名：uheap.out 0 0 0 0 0 0 0 0 3</span>
</p>
