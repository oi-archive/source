<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>你有一条由N个红色的，白色的，或蓝色的珠子组成的项链(3&lt;=N&lt;=350)。 这里是 n=29 的二个例子:</span></p>
<pre><br>
1 2                               1 2
r b b r                           b r r b
r         b                       b         b
r           r                     b            r
r             r                   w              r
b               r                 w               w
b                 b               r                  r
b                 b               b                 b
b                 b               r                  b
r               r                 b                r
b             r                   r              r
b           r                     r            r
r       r                         r         b
r b r                             r r w
图片 A                             图片  B

r 代表 红色的珠子
b 代表 蓝色的珠子
w 代表 白色的珠子</pre>
<p><span><br></span></p>
<p><span><span>第一和第二个珠子在图片中已经被作记号。</span><br><span>图片 A 中的项链可以用下面的字符串表示：</span></span></p>
<pre>brbrrrbbbrrrrrbrrbbrbbbbrrrrb</pre>
<p><span><span><span>假如你要在一些点打破项链,展开成一条直线，然后从一端开始收集同颜色的珠子直到你遇到一个不同的颜色珠子，在另一端做同样的事(颜色可能与在这之前收集的不同)。 确定应该在哪里打破项链来收集到最大数目的珠子。</span><br><span>例如，在图片 A 中的项链中，在珠子 9 和珠子 10 或珠子 24 和珠子 25 之间打断项链可以收集到8个珠子。</span></span></span></p>
<p><span><span><span>白色的珠子（w）可以被当成任意颜色使用</span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>*第一行 一个整数N</p>
<p>*第二行 一个长度为N的字符串，每个字符为b、r或w</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>*第一行 最大可能取得的珠子数</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>29
wwwbbrwrbrbrrbrbrwrwwrbwrwrrb</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>11</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>转自 &lt;a href="http://www.nocow.cn/index.php/Translate:USACO/beads"&gt;http://www.nocow.cn/index.php/Translate:USACO/beads&lt;/a&gt;</p>
</div>
</div>