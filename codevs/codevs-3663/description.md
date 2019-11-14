<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">Smart</span><span style="">想要带着</span><span style="">Sarah</span><span style="">一起</span><span style="">到</span><span style="">科罗拉多州一起滑雪。很不幸，</span><span style="">Sarah</span><span style="">滑雪技术并不精湛。</span></p><p style=""><span style="">S</span><span style="">arah</span><span style="">了解到，在滑雪场里，每天会提供<span style="font-family: Times New Roman;">S(0&lt;=S&lt;=100)</span><span style="">门滑雪课。第</span><span style="font-family: Times New Roman;">i</span><span style="">节课</span></span><span style="">开</span><span style="">始于</span><span style="">时刻</span><span style="">M_i(1&lt;=M_i&lt;=10000)</span><span style="">，</span><span style="">上的时间为<span style="font-family: Times New Roman;">L_i(1&lt;=L_i&lt;=10000)</span><span style="">。上完第</span><span style="font-family: Times New Roman;">i</span><span style="">节课后，</span></span><span style="">Sarah</span><span style="">的滑雪能力会变成<span style="font-family: Times New Roman;">A_i(1&lt;=A_i&lt;=100)</span></span><span style="">。</span><span style="">注意：这个能力是绝对的，不是能力的增长值。</span></p><p style=""><span style="">Sarah</span><span style="">买了一张地图，地图上显示了<span style="font-family: Times New Roman;">N(1 &lt;= N &lt;= 10,000)</span><span style="">个可供滑雪的斜坡，从第</span><span style="font-family: Times New Roman;">i</span><span style="">个斜坡的顶端滑至底部所需的时长</span><span style="font-family: Times New Roman;">D_i(1&lt;=D_i&lt;=10000)</span></span><span style="">，</span><span style="">以及每个斜坡所需要的滑雪能力<span style="font-family: Times New Roman;">C_i(1&lt;=C_i&lt;=100)</span></span><span style="">，</span><span style="">以保证滑雪的安全性</span><span style="">。<span style="font-family: Times New Roman;">Sarah</span></span><span style="">的能力必须大于等于这个等级，</span><span style="">才能保证</span><span style="">她能够安全滑下。</span></p><p style=""><span style="">Sarah</span><span style="">可以用她的时间来滑雪，上课，或者美美地喝上一杯可可汁，但是她必须在<span style="font-family: Times New Roman;">T(1&lt;=T&lt;=10000)</span><span style="">时刻离开滑雪场。这意味着她必须在</span><span style="font-family: Times New Roman;">T</span><span style="">时刻之前完成最后一次滑雪。 求</span></span><span style="">Sarah</span><span style="">在</span><span style="">时间限制</span><span style="">内最多可以完成多少次滑雪。这一天开始的时</span><span style="">刻</span><span style="">，她的滑雪能力为<span style="font-family: Times New Roman;">1</span></span><span style="">。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第<span style="font-family: Times New Roman;">1</span><span style="">行：</span><span style="font-family: Times New Roman;">3</span><span style="">个用空格隔开的整数：</span><span style="font-family: Times New Roman;">T, S, N</span><span style="">。</span></span></p><p style=""><span style="">第<span style="font-family: Times New Roman;">2~S+1</span><span style="">行</span></span><span style="">：</span><span style="">第<span style="font-family: Times New Roman;">i+1</span><span style="">行用</span><span style="font-family: Times New Roman;">3</span><span style="">个空格隔开的整数来描述编号为</span><span style="font-family: Times New Roman;">i</span><span style="">的滑雪课：</span><span style="font-family: Times New Roman;">M_i</span></span><span style="">，</span><span style="">L_i</span><span style="">，</span><span style="">A_i<span style="">。</span></span></p><p style=""><span style="">第<span style="font-family: Times New Roman;">S+2~S+N+1</span><span style="">行：第</span><span style="font-family: Times New Roman;">S+i+1</span><span style="">行用</span><span style="font-family: Times New Roman;">2</span><span style="">个空格隔开的整数来描述第</span><span style="font-family: Times New Roman;">i</span><span style="">个滑雪坡：</span><span style="font-family: Times New Roman;">C_i</span></span><span style="">，</span><span style="">D_i<span style="">。 </span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:37px"><span style=";font-family:&#39;Times New Roman&#39;;font-size:19px">一个整数，表示</span><span style=";font-family:宋体;font-size:19px">Sarah</span><span style=";font-family:&#39;Times New Roman&#39;;font-size:19px">在时间限制内最多可以完成多少次滑雪。&nbsp;</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Times New Roman';">10 1 2</span></p><p style=""><span style="font-family: 'Times New Roman';">3 2 5</span></p><p style=""><span style="font-family: 'Times New Roman';">4 1</span></p><p style=""><span style="font-family: 'Times New Roman';">1 3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题目描述</p><p>样例说明：</p><p style=""><span style="">滑第二个滑雪坡<span style="font-family: Times New Roman;">1</span><span style="">次，然后上课，接着滑</span><span style="font-family: Times New Roman;">5</span><span style="">次第一个滑雪坡。</span></span></p><p><br></p>
</div>
</div>