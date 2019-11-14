<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>MM的幸运数字是4和7，MM特别喜欢这两个数字，因此，所有有4和7组成的数字，MM都认为是幸运的，比如4477，4，777，但是44877就不是幸运数了，因为，MM不喜欢8，她只喜欢4和7。MM看到类似44877这样的非幸运数字就会很不开心，MM觉得自己要不幸运了。Will当然希望MM能开心起来啦，因此他决定帮助MM，他想把一个不幸运的数写成一些幸运数的和，这样，MM就又能高兴起来啦。但是Will的作业好多耶，做也做不完，所以他就来找你啦J。考虑到Will很懒，所以，你需要提供一个所用幸运数最少的分解。顺便告诉你个小秘密，MM喜欢字典序靠前的东西，因此，如果在所用数字的最少的前提下，你能找到字典序最先的拆分方法，MM会更开心的。MM越开心，你的奖励就越多哦！</span></p>
<p><span>问题：</span></p>
<p><span>给定一个数N，将其分解为一些幸运数的和，要求所用数字最少，如果有多组解要求字典序最小。</span></p>
<p><span>无解则输出 No solution</span></p>
<p><span>对于字典序的解释</span></p>
<p><span>对于数列 a[1..n] &lt;&gt; b[1..n] 我们寻找第一位子 i 使得 a[i] != b[i] ，如果 a[i] &lt; b[i] 则 a 字典序小， 否则 b[i] 字典序小</span></p>
<p><span><br></span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>一行，一个整数 N</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>一行，N的幸运分解，两个数之间用空格隔开</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>数据规模：</span></p>
<p><span>对于30%的数据 1 ≤ N ≤ 100</span></p>
<p><span>对于40%的数据 1 ≤ N ≤ 10000</span></p>
<p><span>对于70%的数据 1 ≤ N ≤ 100000</span></p>
<p><span>对于10%的数据 N = 774099</span></p>
<p><span>对于10%的数据 N = 987654321</span></p>
<p><span>对于100%的数据 1 ≤ N ≤ 1000,000,000</span></p>
</div>
</div>