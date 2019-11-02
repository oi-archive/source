<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在生物学中，一些生物的结构是用包含其要素的大写字母序列来表示的。生物学家对于把长的序列分解成较短的序列（即元素）很感兴趣。</p>
<p>如果一个集合 P 中的元素可以通过串联（元素可以重复使用，相当于 Pascal 中的 “+” 运算符）组成一个序列 S ，那么我们认为序列 S 可以分解为 P 中的元素。元素不一定要全部出现（如下例中BBC就没有出现）。举个例子，序列 ABABACABAAB 可以分解为下面集合中的元素：</p>
<p>{A, AB, BA, CA, BBC}</p>
<p>序列 S 的前面 K 个字符称作 S 中长度为 K 的前缀。设计一个程序，输入一个元素集合以及一个大写字母序列 S ，设S'是序列S的最长前缀，使其可以分解为给出的集合P中的元素，求S'的长度K。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入数据的开头包括 1..200 个元素（长度为 1..10 ）组成的集合，用连续的以空格分开的字符串表示。字母全部是大写，数据可能不止一行。元素集合结束的标志是一个只包含一个 “.” 的行。集合中的元素没有重复。接着是大写字母序列 S ，长度为 1..200,000 ，用一行或者多行的字符串来表示，每行不超过 76 个字符。换行符并不是序列 S 的一部分。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>只有一行，输出一个整数，表示 S 符合条件的前缀的最大长度。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>A AB BA CA BBC
.
ABABACABAABC</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>