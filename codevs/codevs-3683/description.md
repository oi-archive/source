<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">给出一个</span><span style="font-family: 'Courier New';">N(1 &lt;= N &lt;= 20,000)</span><span style="">个点的图，有</span><span style="font-family: 'Courier New';">K(1 &lt;= K &lt;= 200, K &lt;= N)</span><span style="">个特殊点。这个图有</span><span style="font-family: 'Courier New';">M(1 &lt;= M &lt;= 20,000)</span><span style="">条有向边，第</span><span style="font-family: 'Courier New';">i</span><span style="">条边从</span><span style="font-family: 'Courier New';">u_i</span><span style="">指向</span><span style="font-family: 'Courier New';">v_i</span><span style="">，花费为</span><span style="font-family: 'Courier New';">d_i(1 &lt;= d_i&lt;= 10,000)</span><span style="">。每条边至少有一个点是特殊点，不存在重边和自环。现在有</span><span style="font-family: 'Courier New';">Q(1 &lt;= Q &lt;= 50,000)</span><span style="">个询问，每个询问指定两个点</span><span style="font-family: 'Courier New';">a_i</span><span style="">和</span><span style="font-family: 'Courier New';">b_i</span><span style="">，判断能不能到达以及最小的花费。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行四个数</span><span style="font-family: 'Courier New';">N</span><span style="">，</span><span style="font-family: 'Courier New';">M</span><span style="">，</span><span style="font-family: 'Courier New';">K</span><span style="">，</span><span style="font-family: 'Courier New';">Q</span><br></p><p><span style="">接下来</span><span style="font-family: 'Courier New';">M</span><span style="">行，每行三个数</span><span style="font-family: 'Courier New';">u_i</span><span style="">，</span><span style="font-family: 'Courier New';">v_i</span><span style="">，</span><span style="font-family: 'Courier New';">d_i</span></p><p><span style="">接下来</span><span style="font-family: 'Courier New';">K</span><span style="">行，每行一个数表示特殊点的编号</span></p><p><span style="">接下来</span><span style="font-family: 'Courier New';">Q</span><span style="">行，每行两个数</span><span style="font-family: 'Courier New';">a_i</span><span style="">和</span><span style="font-family: 'Courier New';">b_i</span><span style="">，表示这个询问从</span><span style="font-family: 'Courier New';">a_i</span><span style="">走到</span><span style="font-family: 'Courier New';">b_i</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体;background-color: white">输出两行，第一行一个整数表示有多少个询问可以满足，第二行一个整数表示可以满足的那些询问的最小花费的和是多少。注意：不保证答案在</span><span style="font-family: &#39;Courier New&#39;;background-color: white">32</span><span style="font-family: 宋体;background-color: white">位整数范围内。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">3 3 1 2 </span></p><p><span style="font-family: 'Courier New';">1 2 10 </span></p><p><span style="font-family: 'Courier New';">2 3 10 </span></p><p><span style="font-family: 'Courier New';">2 1 5 </span></p><p><span style="font-family: 'Courier New';">2 </span></p><p><span style="font-family: 'Courier New';">1 3 </span></p><p><span style="font-family: 'Courier New';">3 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Courier New';">1</span></p><p><span style="font-family: 'Courier New';">20</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题目。</p>
</div>
</div>