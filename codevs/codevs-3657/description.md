<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">我们用以下规则定义一个合法的括号序列：</span></p><p style=""><span style="">（1）空序列是合法的</span></p><p style=""><span style="">（2）假如S是一个合法的序列，则 (S) 和[S]都是合法的</span></p><p style=""><span style="">（3）假如A 和 B 都是合法的，那么AB和BA也是合法的</span></p><p style=""><span style="">例如以下是合法的括号序列：</span></p><p style=""><tt><span style="">()</span></tt><span style="">, </span><tt><span style="">[]</span></tt><span style="">, </span><tt><span style="">(())</span></tt><span style="">, </span><tt><span style="">([])</span></tt><span style="">, </span><tt><span style="">()[]</span></tt><span style="">, </span><tt><span style="">()[()]</span></tt></p><p style=""><span style="">以下是不合法括号序列的：</span></p><p style=""><tt><span style="">(</span></tt><span style="">, </span><tt><span style="">[</span></tt><span style="">, </span><tt><span style="">]</span></tt><span style="">, </span><tt><span style="">)(</span></tt><span style="">, </span><tt><span style="">([])</span></tt><span style="">, </span><tt><span style="">([()</span></tt></p><p style=""><span style=""> </span><span style="">现在给定一些由'(', ')', '[', ，']'构成的序列 ，请添加尽量少的括号，得到一个合法的括号序列。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入包括号序列S。含最多100个字符（四种字符： '(', ')', '[' and ']') ，都放在一行，中间没有其他多余字符。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style=";margin-bottom:0;text-indent:28px"><span style="font-size:14px">使括号序列S成为合法序列需要添加最少的括号数量。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">([()</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">2</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">【样例说明】
最少添加2个括号可以得到合法的序列：()[()]或([()])
【数据范围】
S的长度&lt;=100 (最多100个字符)。</pre><p><br></p><p><br></p>
</div>
</div>