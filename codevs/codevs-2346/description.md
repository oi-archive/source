<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有 n 个连续函数 fi (x)，其中 1 ≤ i ≤ n。对于任何两个函数 fi (x) 和<br>fj (x),(i = j)，恰好存在一个 x 使得 fi (x) = fj (x)，并且存在无穷多的 x 使<br>得 fi (x) &lt; fj (x)。对于任何 i; j; k，满足 1 ≤ i &lt; j &lt; k ≤ n，则不存在 x 使得<br>fi (x) = fj (x) = fk (x)。</p>
<p>如上左图就是 3 个满足条件的函数，最左边从下往上依次为 f1; f2; f3。右图中红色部分是这整个函数图像的最低层，我们称它为第一层。同理绿色部分称为第二层，蓝色部分称为第三层。注意到，右图中第一层左边一段属于 f1，中间属于 f2，最后属于 f3。而第二层左边属于 f2，接下来一段属于 f1，再接下来一段属于 f3，最后属于 f2。因此，我们称第一层分为了三段，第二层分为了四段。同理第三层只分为了两段。求满足前面条件的 n 个函数，第 k 层最少能由多少段组成。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行两个整数 n; k。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数，表示 n 个函数第 k 层最少能由多少段组成。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 100% 的数据满足 1 ≤ k ≤ n ≤ 100。</p>
</div>
</div>