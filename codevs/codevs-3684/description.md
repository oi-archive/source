<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">有</span><span style="font-family: 'Courier New';">N(1 &lt;= N &lt;= 40,000)</span><span style="">台机器放在一排，第</span><span style="font-family: 'Courier New';">i</span><span style="">台机器的日产量为</span><span style="font-family: 'Courier New';">M[i]</span><span style="">，如果第</span><span style="font-family: 'Courier New';">i</span><span style="">台机器被选用，那么与之相邻的两台</span><span style="font-family: 'Courier New';">(</span><span style="">端点只有一台相邻</span><span style="font-family: 'Courier New';">)</span><span style="">就不能在这一天被选用，现在有</span><span style="font-family: 'Courier New';">D</span><span style="">天，每一天开始之前会把第某一台机器升级，使其日产量改变，现在问</span><span style="font-family: 'Courier New';">D(1 &lt;= D &lt;= 50,000)</span><span style="">天过去之后最大的总参量是多少。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行两个数</span><span style="font-family: 'Courier New';">N</span><span style="">，</span><span style="font-family: 'Courier New';">D</span><span style="">。</span></p><p style=""><span style="font-family: 'Courier New';">    </span><span style="">接下来</span><span style="font-family: 'Courier New';">N</span><span style="">行，每行一个整数</span><span style="font-family: 'Courier New';">M[i]</span><span style="">。</span></p><p style=""><span style="font-family: 'Courier New';">    </span><span style="">接下来</span><span style="font-family: 'Courier New';">D</span><span style="">行，每行两个整数</span><span style="font-family: 'Courier New';">i</span><span style="">，</span><span style="font-family: 'Courier New';">M[i]</span><span style="">，表示这一天把第</span><span style="font-family: 'Courier New';">i</span><span style="">台机器的日产量改变为</span><span style="font-family: 'Courier New';">M[i]</span><span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体; background-color: rgb(255, 255, 255);">一行一个整数表示答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">5 3</span></p><p style=""><span style="font-family: 'Courier New';">1</span></p><p style=""><span style="font-family: 'Courier New';">2</span></p><p style=""><span style="font-family: 'Courier New';">3</span></p><p style=""><span style="font-family: 'Courier New';">4</span></p><p style=""><span style="font-family: 'Courier New';">5</span></p><p style=""><span style="font-family: 'Courier New';">5 2</span></p><p style=""><span style="font-family: 'Courier New';">2 7</span></p><p style=""><span style="font-family: 'Courier New';">1 10</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">32</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题目描述</p><p>方法：线段树，dp，分块</p><p>题目水水的……</p><p><span style="font-family: arial, helvetica, sans-serif;">注意：不保证答案在32位整数范围内。</span></p><p><span style="font-family: arial, helvetica, sans-serif;">pascal请用int64，C++请用long long</span></p>
</div>
</div>