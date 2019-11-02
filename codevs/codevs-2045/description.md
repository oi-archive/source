<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一类书的序言是以罗马数字标页码的。传统罗马数字用单个字母表示特定的数值，以下是标准数字表:</p>
<pre>I 1  V 5  X 10  L 50  C 100  D 500  M 1000
</pre>
<p>最多3个同样的可以表示为10<sup>n</sup>的数字(I,X,C,M)可以连续放在一起，表示它们的和:</p>
<pre>III=3
CCC=300
</pre>
<p>可表示为5x10<sup>n</sup>的字符(V,L,D)从不连续出现。</p>
<p>除了下一个规则，一般来说，字符以递减的顺序接连出现:</p>
<pre>CCLXVIII = 100+100+50+10+5+1+1+1 = 268
</pre>
<p>有时，一个可表示为10<sup>n</sup>的数出现在一个比它大1级或2级的数前(I在V或X前面，X在L或C前面，等等)。在这种情况下，数值等于后面的那个数减去前面的那个数:</p>
<pre>IV = 4
IX = 9
XL = 40
</pre>
<p><br>一个数 用罗马数字来表示 有且仅有一种 而且不能复合嵌套使用（比如I是1 X是10 有人可能要说 IXL就能表示50-10-1 但是IXL绝对不能用来表达39 ） （那么39用什么来表示呢 XXXIX是唯一 而且正确的选择- -）</p>
<p><br>像XD, IC, 和XM这样的表达是非法的，因为前面的数比后面的数小太多。对于XD(490的错误表达)，可以写成 CDXC; 对于IC(99的错误表达)，可以写成XCIX; 对于XM(990的错误表达)，可以写成CMXC。 90 写成 XC 而不是 LXL, 因为 L 后面的 X 意味着后继标记是 X 或者更小 (不管怎样，可能吧)（等同于阿拉伯数字 每位 数字分别表示）。</p>
<p><br>给定N(1 &lt;= N &lt; 3,500)， 序言的页码数，请统计在第1页到第N页中，有几个I出现，几个V出现，等等 (从小到大的顺序)。不要输出没有出现过的字符。</p>
<p>比如N = 5, 那么页码数为: I, II, III, IV, V. 总共有7个I出现，2个V出现。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一个整数N。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>每行一个字符和一个数字k，表示这个字符出现了k次。字符必须按数字表中的递增顺序输出。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>I 7
V 2</pre>

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