<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>萧芸斓是 Z国的公主，平时的一大爱好是采花。 <br>今天天气晴朗，阳光明媚，公主清晨便去了皇宫中新建的花园采花。花园足够大，容纳了 n 朵花，花有 c 种颜色（用整数 1-c 表示） ，且花是排成一排的，以便于公主采花。 <br>公主每次采花后会统计采到的花的颜色数， 颜色数越多她会越高兴！ 同时， 她有一癖好，她不允许最后自己采到的花中，某一颜色的花只有一朵。为此，公主每采一朵花，要么此前已采到此颜色的花，要么有相当正确的直觉告诉她，她必能再次采到此颜色的花。 由于时间关系，公主只能走过花园连续的一段进行采花，便让女仆福涵洁安排行程。福涵洁综合各种因素拟定了 m 个行程，然后一一向你询问公主能采到多少朵花（她知道你是编程高手，定能快速给出答案！ ） ，最后会选择令公主最高兴的行程（为了拿到更多奖金！ ） 。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行四个空格隔开的整数 n、c 以及 m。 <br>接下来一行 n 个空格隔开的整数，每个数在[1, c]间，第i 个数表示第 i 朵花的颜色。 <br>接下来 m 行每行两个空格隔开的整数 l 和 r（l ≤ r） ，表示女仆安排的行程为公主经过第 l 到第r 朵花进行采花。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共m行， 每行一个整数， 第i个数表示公主在女仆的第i个行程中能采到的花的颜色数。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3 5 <br>1 2 2 3 1<br>1 5 <br>1 2 <br>2 2 <br>2 3 <br>3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br>0 <br>0 <br>1 <br>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，1 ≤ n ≤10<sup>6</sup>，c ≤ n，m ≤ 10<sup>6</sup>。</p>
</div>
</div>