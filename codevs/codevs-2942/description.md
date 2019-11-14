<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　某人写了一个使用P++编译的IDE，很可惜他的IDE仅支持带加或减的赋值语句，并没有写完就被李华拿去玩了。</p>
<p>　　李华很快就把这个IDE玩坏了...IDE编出的程序被P++允许至多两个程序<strong>共用变量</strong>同时运行(好神奇他是怎么做到的)。比较幸运地是，两个程序的寄存器并没有出现共用的情况。</p>
<p>　　而处理器接受两个程序后，每次会随机选择一个程序，并执行它的下一条机器指令。这给李华Debug带来了很大的困难，因为处理器的执行顺序不唯一，最后各个变量的值也是不唯一的。</p>
<p>　　李华希望你能帮他求出每个变量最终的期望值。</p>
<p>　　某人的IDE支持的语句为<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PyUzQ1ZhcmlhYmxlJTNFXDsmYW1wO3NwYWNlOzo9XDsmYW1wO3NwYWNlOyUzQ09wZXJhbmQlM0VcOyZhbXA7c3BhY2U7JTNDT3BlcmF0b3IlM0VcOyZhbXA7c3BhY2U7JTNDT3BlcmFuZCUzRQ==.latex">，忽略多余空格。</p>
<p>　　其中<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P1ZhcmlhYmxl.latex">表示变量(变量名由<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0EuLi5aLGEuLi56LGFuZFw7JmFtcDtzcGFjZTswLi4uOQ==.9">组成，不区分大小写，不超过20个字符，第一位不为数字)；<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P09wZXJhbmQ=.latex">表示操作数，可以是一个变量或者一个常量(不超过100的正整数)；<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P09wZXJhdG9y.latex">表示运算符，可以是加号"<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4Pys=.latex">"或者减号"<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4Py0=.latex">"。</p>
<p>　　P++由猪国一名伟大的Pig编写而成，它可以将上述语句<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0E6PUIrQw==.latex">翻译为四条机器指令：</p>
<ol>
<li>　　<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0FTU1w7JmFtcDtzcGFjZTtSX3sxfSxC.latex"></li>
<li>　　<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0FTU1w7JmFtcDtzcGFjZTtSX3syfSxD.latex"></li>
<li>　　若<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P09wZXJhdG9yPQ==.latex"+'">则会执行<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0FERFw7JmFtcDtzcGFjZTtSX3sxfSxSX3syfQ==.latex">，否则<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P09wZXJhdG9yPQ==.latex"-'">，会执行<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P1NVQlw7JmFtcDtzcGFjZTtSX3sxfSxSX3syfQ==.latex"></li>
<li>　　<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0FERFw7JmFtcDtzcGFjZTtBLFJfezF9.latex"></li>
</ol>
<p>　　其中<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0FTUw==.latex">指令会把第二个操作数赋值到第一个操作数中去，<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0FERChTVUIp.latex">操作进行加法(减法)，并将结果保存在第一个操作数中，<img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P1JfezF9LFJfezJ9.latex">为两个寄存器。<strong>注意，赋值会覆盖原来的值，以上操作没有涉及到清零。</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入为两个程序的代码，每条语句占一行，每份程序以</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0VORA==.latex"><span>结尾，文末有换行符。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　按照字典序输出每个变量的期望终值，强制保留</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PzQ=.latex" alt="4" /><span>位小数，注意，对于大于</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4Py0xMF57LTR9.latex" alt="-10^{-4}" /><span>的负数，你的程序不应输出"</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4Py0wLjAwMDA=.0000" alt="-0.0000" /><span>"，而是输出"</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PzAuMDAwMA==.0000" alt="0.0000" /><span>"。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>S := 1 + 3
END
S := S + S
END

</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>3.0000

</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于100%的数据:每份程序最多有</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PzEwMA==.latex"><span>条语句(不含</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4P0VORA==.latex"><span>)，两份程序最多共用</span><img src="/source/codevs/codevs-2942/img/aHR0cHM6Ly9sYXRleC5jb2RlY29ncy5jb20vZ2lmLmxhdGV4PzEwMA==.latex"><span>个变量。</span></p>
<p><span><br></span></p>
<p>　　ACM/ICPC 2001德黑兰赛区G题改编</p>
</div>
</div>