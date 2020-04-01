<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">你有一条由N个红色的，白色的，或蓝色的珠子组成的项链(3&lt;=N&lt;=350)，珠子是随意安排的<span style="">。 这里是 n=29 的二个例子:</span></span></p><p><span style="">            1 2                               1 2</span></p><p><span style="">            r b b r                           b r r b</span></p><p><span style="">          r         b                       b         b</span></p><p><span style="">         r           r                     b           r</span></p><p><span style="">        r             r                   w             r</span></p><p><span style="">       b               r                 w               w</span></p><p><span style="">      b                 b               r                 r</span></p><p><span style="">      b                 b               b                 b</span></p><p><span style="">      b                 b               r                 b</span></p><p><span style="">       r               r                 b               r</span></p><p><span style="">        b             r                   r             r</span></p><p><span style="">         b           r                     r           r</span></p><p><span style="">           r       r                         r       b</span></p><p><span style="">             r b r                             r r w</span></p><p><span style="">             </span><span style="">图 A                              图  B</span></p><p style=""><span style="">r </span><span style="">代表 红色的珠子   b 代表 蓝色的珠子  w 代表 白色的珠子</span></p><p><span style="">说明：第一和第二个珠子在图片中已经被作记号。</span></p><p style=""><span style="">图A中的项链可以用下面的字符串表示：brbrrrbbbrrrrrbrrbbrbbbbrrrrb . </span></p><p style=""><span style="">请选择一些点剪断项链,展开成一条直线，然后从一端开始收集同颜色的珠子直到你遇到一个不同的颜色珠子，在另一端做同样的事。(颜色可能与在这之前收集的不同) 确定应该在哪里剪断项链来收集到珠子的个数最多。</span></p><p style=""><span style="">例：图A中项链，可以收集到8个珠子,在珠子10和珠子11或珠子25和珠子26之间打断项链。</span></p><p style=""><span style="">注意：如果项链中包括有白色的珠子（如图B）。当收集珠子的时候，遇到的白色珠子可以被当做红色也可以被当做蓝色。表示项链的字符串将会包括三种符号r、b和w。</span></p><p style=""><span style="">请你写一个程序来确定从一条给定的项链最大可以被收集珠子数目。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">有二行，第 1 行:  N，为珠子的数目</span></p><p><span style=""><span style=""></span><span style="">第 2 行:  一串长度为N的字符串, 每个字符是r、b或w，中间没有空格。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:14px;font-family:宋体">收集珠子数目的最大值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">29</span></p><p><span style=""><span style="">wwwbbrwrbrbrrbrbrwrwwrbwrwrrb</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">11</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如上</p>
</div>
</div>