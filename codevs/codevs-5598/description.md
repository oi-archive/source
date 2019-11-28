<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">C</span><span style="">J<span style="">R</span></span><span style="">把<span style="">这</span>些<span style="">木</span>棍<span style="">竖直</span>放<span style="">置</span><span style="">，</span>打算建造一座高塔<span style="">。</span>为了保证高塔的稳定性<span style="">，</span>在建造高塔的</span></p><p style=""><span style="">时候，上方木棍的直径必须小于等于下方木棍的直径。</span></p><p style=""><span style="">CJ<span style="">R</span></span><span style="">给出如下定义：</span></p><p style=""><span style="">d</span><span style="">表示高塔的最大直径；</span></p><p style=""><span style="">h</span><span style="">表示高塔的高度；</span> </p><table cellpadding="0" cellspacing="0"><tbody><tr><td height="60" style="" width="9"><span style="">   d</span> </td></tr></tbody></table><p style=""><span style="">稳定系<span style="">数</span></span><span style="">a=</span><span style="text-decoration: underline;"><span style="font-family: 'Cambria Math','serif';">h</span></span><span style="">-1</span><span style="">，可以发现，</span><span style="">a</span><span style="">越大，塔越稳定，并且<span style="">在</span></span><span style="">a&gt;<span style="">0</span></span><span style="">时，<span style="">有</span></span><span style="">d&gt;h</span><span style="">；</span></p><p><span style="">高</span><span style="">度系<span style="">数</span></span><span style="font-family: 'Times New Roman','serif';">b</span><span style="font-family: 'Times New Roman','serif';">=</span><span style="font-family: 'Cambria Math','serif';">h</span><span style="font-family: 'Cambria Math','serif';">d</span><span style="font-family: 'Times New Roman','serif';">-</span><span style="font-family: 'Times New Roman','serif';">1</span><span style="">，可以发现，</span><span style="font-family: 'Times New Roman','serif';">b</span><span style="">越小，塔越稳定，并且<span style="">在</span></span><span style="font-family: 'Times New Roman','serif';">b</span><span style="font-family: 'Times New Roman','serif';">&gt;<span style="">0</span></span><span style="">时，<span style="">有</span></span><span style="font-family: 'Times New Roman','serif';">d</span><span style="font-family: 'Times New Roman','serif';">&lt;h</span><span style="">。</span><span style="font-family: 'Times New Roman','serif';">CJ<span style="">R</span></span><span style="">希望建成高塔<span style="">的</span></span><span style="font-family: 'Times New Roman','serif';">a+<span style="">b</span></span><span style="">的值最小，并想要知道在这种情况<span style="">下</span></span><span style="font-family: 'Times New Roman','serif';">h+<span style="">d</span></span><span style="">的最大值。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">//输入文件<span style="">为</span></span><span style="">construct.in</span><span style="">。</span></p><p style=""><span style="">第一行包含一个正整<span style="">数</span></span><span style="">N</span><span style="">，表示<span style="">有</span></span><span style="">N</span><span style="">根木棍。</span></p><p style=""><span style="">接下来<span style="">的</span></span><span style="">N</span><span style="">行，每行两个正整<span style="">数</span></span><span style="">D </span><span style="">和</span><span style="">H</span><span style="">，表示该木棍的直径<span style="">为</span></span><span style="">D</span><span style="">，高度<span style="">为</span></span><span style="">H</span><span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>//<span style="line-height: 18px; font-size: 14px; font-family: 宋体;">输出文件<span style="letter-spacing:2px">为</span></span><span style="line-height: 18px; font-size: 14px;">construct.out</span><span style="line-height: 18px; font-size: 14px; font-family: 宋体;">。</span></p><p style="margin: 3px 0 0 28px;line-height: 18px"><span style="font-size:14px;font-family:宋体">输出只有一行，包含一个正整数，表示建成高塔<span style="letter-spacing:2px">的</span></span><span style="font-size: 14px">a+<span style="letter-spacing:3px">b</span></span><span style="font-size:14px;font-family:宋体">的值最小时，</span><span style="font-size:14px">h+<span style="letter-spacing:4px">d</span></span><span style="font-size:14px;font-family:宋体">的最大值。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">6</span></p><p style=""><span style="font-family: 'Courier New';">1<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">5</span></p><p style=""><span style="font-family: 'Courier New';">2<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">3</span></p><p style=""><span style="font-family: 'Courier New';">5 2</span></p><p style=""><span style="font-family: 'Courier New';">3<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">4</span></p><p style=""><span style="font-family: 'Courier New';">2 4</span></p><p><span style="font-family: 'Courier New';"> 4 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【输入输出样例说明】</span><span style=""><img height="184" src="/source/codevs/codevs-5598/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NTk4L2h0dHA6Ly83eGs1OGwuY29tMS56MC5nbGIuY2xvdWRkbi5jb20vYWNjb3VudC91ZWRpdG9yL3RoZW1lcy9kZWZhdWx0L2ltYWdlcy9zcGFjZXIuZ2lm.gif" style="" width="238"></span></p><p style=""><span style="">选择<span style="">第</span></span><span style="">2</span><span style="">、</span><span style="">3</span><span style="">根木棍，</span><span style="">h=5</span><span style="">，</span><span style="">d=5</span><span style="">，</span><span style="">a+b=0</span><span style="">，</span><span style="">h+d=10</span><span style="">。</span></p><p style=""><span style="">【数据范围】</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">30%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>10</span><span style="">。对<span style="">于</span></span><span style="">100%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>22</span><span style="">。</span></p><p><br></p>
</div>
</div>