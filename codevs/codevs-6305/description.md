<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><span style="">sqrt_-1 和 zzh 之间的战役终于打响了！！！</span></span></p><p><span style=""><span style=""><span style="">他们两个决定用编程一决高下，而他们俩用来决斗的这道题是这样的：</span></span></span></p><p><span style=""><span style=""><span style="">输出 (3 + sqrt(5))<sup>n </sup>整数部分的末三位，如果结果不超过两位那么补上前导 0。<br></span></span></span></p><p><span style=""><span style=""><span style=""><span style="">sqrt_-1 大佬推崇使用高精度算法，</span></span></span></span></p><p><span style=""><span style=""><span style=""><span style=""><span style="">但冷静沉着的 zzh 则想使用玄学无敌<strong>矩阵乘法幂运算</strong>来求解这道题。</span></span></span></span></span></p><p><span style=""><span style=""><span style=""><span style=""><span style=""><span style="">现在他们两个的决斗内容是，sqrt_-1 使用高精度解决这道题的答案是否是错误的，若是那么输出 "Oh no!"，否则输出 "Very good!"。</span></span></span></span></span></span></p><p><span style="">※sqrt_-1 的高精度似乎哪里写错了，不仅答案有可能<strong>错</strong>，而且还会 <strong>TLE</strong>，但是 zzh 的程序却 <strong>0.1 秒不到</strong>就返回了<strong>正确结果</strong>。（尽管如此我还是设了 2 秒，希望你的程序能比 zzh 的程序更快 </span><span style="">╮(╯▽╰)╭ </span><span style="">）</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包括两个数 n 和 ans，其中 n 描述如上，ans 表示 sqrt_-1 算出的答案。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅包括一个字符串，若 sqrt_-1 的答案是正确的则输出 &quot;Oh no!&quot;，否则输出 &quot;Very good!&quot;，并换行输出答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>input1:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">2 027</pre><p>---------------------</p><p>input2:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">5 934</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>output1:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">Oh no!</pre><p>---------------------</p><p>output2:</p><pre style="font-family: Consolas, 'Lucida Console', 'Andale Mono', 'Bitstream Vera Sans Mono', 'Courier New', Courier;">Very good!
935</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围：</p><p>对于 30% 的数据，1 &lt;= n &lt;= 50。 (Small)</p><p>对于 100% 的数据，1 &lt;= n &lt;= 2 * 10<sup>9</sup>。（Large）</p><p>提示：</p><p>本题为 Google Code Jam 原题 （数据当然是我出的），欢迎找题解和抄题解，正确思路题目里有（矩阵）。</p><p><span style="">注：</span></p><p><span style="">本题为了增加趣味性，所以参考了 p6274 的描述，<strong>copyleft all lefts reserved</strong>。</span></p>
</div>
</div>