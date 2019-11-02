<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun;">给你一个长度为N的数组，一个长为K的滑动的窗体从最左移至最右端，你<span style="">只能见到窗口的K个数，每次窗体向右移动一位，如下表：</span></span></p><table><tbody><tr><td style="" valign="top" width="179"><strong style="font-family: SimSun;">Window position</strong></td><td valign="top" width="78"><span style="font-family: SimSun;">Min value</span><br></td><td valign="top" width="86"><span style="font-family: SimSun;"> Max value</span><br></td></tr><tr><td style="" valign="top" width="179"><span style="font-family: SimSun;">[ 1 3 -1 ] -3 5 3 6 7 </span><br></td><td style="" valign="top" width="78">    -1</td><td style="" valign="top" width="86">     3</td></tr><tr><td style="" valign="top" width="179"><span style="font-family: SimSun;"><span style="font-family: SimSun;">1 [ 3 -1 -3 ] 5 3 6 7 </span></span></td><td style="" valign="top" width="78">    -3</td><td style="" valign="top" width="86">     3<br></td></tr><tr><td style="" valign="top" width="179"><span style="font-family: SimSun;">1 3 [ -1 -3 5 ] 3 6 7 </span></td><td style="" valign="top" width="78">    -3</td><td style="" valign="top" width="86">     5</td></tr><tr><td style="" valign="top" width="179"><span style="font-family: SimSun;">1 3 -1 [ -3 5 3 ] 6 7 </span></td><td style="" valign="top" width="78">    -3</td><td style="" valign="top" width="86">     5</td></tr><tr><td style="" valign="top" width="179"><span style="font-family: SimSun;">1 3 -1 -3 [ 5 3 6 ] 7</span></td><td style="" valign="top" width="78">    3</td><td style="" valign="top" width="86">     6</td></tr><tr><td style="" valign="top" width="179"><span style="font-family: SimSun;">1 3 -1 -3 5 [ 3 6 7 ]</span></td><td style="" valign="top" width="78">    3</td><td style="" valign="top" width="86">     7</td></tr></tbody></table><p><span style="font-family: SimSun;"><span style=""><span style="font-family: SimSun;"><span style=""><span style=""><span style=""><span style=""><span style=""><span style=""><span style=""><span style=""><span style=""></span></span></span></span></span></span></span></span></span></span></span></span><span style="font-family: SimSun;">你的任务是找出窗口在各位置时的max value, min value.</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: SimSun;"><span style="font-family: SimSun;">第1行n,k,第2行为长度为n的数组</span></span></p><p style=""><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="white-space: normal;"><span style="font-family: SimSun; font-size: 12pt;">2行</span></p><p style="white-space: normal;"><span style="font-family: SimSun; font-size: 12pt;">第1行每个位置的min value</span></p><p style="white-space: normal;"><span style="font-family: SimSun; font-size: 12pt;">第2行每个位置的max value</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: SimSun;">8 3</span></p><p style=""><span style="font-family: SimSun;">1 3 -1 -3 5 3 6 7</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: SimSun;">-1 -3 -3 -3 3 3</span></p><p style=""><span style="font-family: SimSun;">3  3  5  5  6 7</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">数据范围：</span><span style="font-family: SimSun;">20%： n&lt;=500; 50%: n&lt;=100000;<span style="">100%: n&lt;=1000000;</span></span></p>
</div>
</div>