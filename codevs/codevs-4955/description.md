<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">现在六年级，下半年就要上初中了，文化课学业和信息学竞赛使他的精力消耗很大。他的父母为了保持他的健康，每天为他准备了</span><span style=""><span style="font-family: Times New Roman;">G</span></span><span style="">种食物，他们知道每种食物中所包含的小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">每天所需要的</span><span style=""><span style="font-family: Times New Roman;">V</span></span><span style="">种维他命的量各是多少。</span></p><p style=""><span style="">给出小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">每天所需的各种维他命的最低量，请你帮助小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">来选择食物，以保证每天他需要的各种维他命的最小量。由于小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">不想吃得太多（为了保持良好身材），他想选择的食物的种数越少越好。</span><span style=""> </span></p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行一个整数</span><span style=""><span style="font-family: Times New Roman;">V</span></span><span style="">，表示小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">每天需要的维他命的种类数。</span></p><p style=""><span style="">第二行</span><span style=""><span style="font-family: Times New Roman;">V</span></span><span style="">个整数，第</span><span style=""><span style="font-family: Times New Roman;">i</span></span><span style="">个整数</span><span style=""><span style="font-family: Times New Roman;">A<sub>i</sub></span></span><span style="">，表示小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">每天需要的第</span><span style=""><span style="font-family: Times New Roman;">i</span></span><span style="">种维他命的最小量。</span></p><p style=""><span style="">第三行一个整数</span><span style=""><span style="font-family: Times New Roman;">G</span></span><span style="">，表示爸妈每天为他准备了</span><span style=""><span style="font-family: Times New Roman;">G</span></span><span style="">种食物。</span></p><p style=""><span style="">接下来</span><span style=""><span style="font-family: Times New Roman;">G</span></span><span style="">行，每行</span><span style=""><span style="font-family: Times New Roman;">V</span></span><span style="">个数，第</span><span style=""><span style="font-family: Times New Roman;">i</span></span><span style="">行第</span><span style=""><span style="font-family: Times New Roman;">j</span></span><span style="">个数</span><span style=""><span style="font-family: Times New Roman;">B<sub>ij</sub></span></span><span style="">表示编号为</span><span style=""><span style="font-family: Times New Roman;">i</span></span><span style="">的食物包含的第</span><span style=""><span style="font-family: Times New Roman;">j</span></span><span style="">种维他命的量是多少。</span></p><p style=""><span style="">注意：每种食物最多只能使用一次，数据保证存在解。</span></p><p></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="line-height: 150%; text-indent: 32px;"><span style="line-height: 150%; font-family: 宋体; font-size: 16px;">输出只有一行，包含一个整数</span><span style="line-height: 150%; font-size: 16px;"><span style="font-family: Times New Roman;">P</span></span><span style="line-height: 150%; font-family: 宋体; font-size: 16px;">，表示你为小</span><span style="line-height: 150%; font-size: 16px;"><span style="font-family: Times New Roman;">L</span></span><span style="line-height: 150%; font-family: 宋体; font-size: 16px;">选择了最少的食物种数</span><span style="line-height: 150%; font-size: 16px;"><span style="font-family: Times New Roman;">P</span></span><span style="line-height: 150%; font-family: 宋体; font-size: 16px;">以满足要求。</span><span style="line-height: 150%; font-size: 16px;"> </span></p><p></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="font-family: Times New Roman;">4</span></span></p><p style=""><span style=""><span style="font-family: Times New Roman;">100 200 300 400</span></span></p><p style=""><span style=""><span style="font-family: Times New Roman;">3</span></span></p><p style=""><span style=""><span style="font-family: Times New Roman;">50 50 50 50</span></span></p><p style=""><span style=""><span style="font-family: Times New Roman;">40 87 200 300</span></span></p><p><span style="">55 150 289 399</span></p><p></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例说明：<span style="">选择</span><span style=""><span style="font-family: Times New Roman;">2</span></span><span style="">种食物</span><span style=""><span style="font-family: Times New Roman;">1</span></span><span style="">和</span><span style=""><span style="font-family: Times New Roman;">3</span></span><span style="">，四种维他命含量分别为</span><span style=""><span style="font-family: Times New Roman;">50+55=105</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">50+150=200</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">50+289=339</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">50+399=449</span></span><span style="">，分别大于等于小</span><span style=""><span style="font-family: Times New Roman;">L</span></span><span style="">一天需要的四种维他命需求</span><span style=""><span style="font-family: Times New Roman;">100</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">200</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">300</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">400</span></span><span style="">。</span></p><p><span style="">数据范围：</span><span style=""><span style="font-family: Times New Roman;">50%</span></span><span style="">的数据：</span><span style=""><span style="font-family: Times New Roman;">1≤V≤5</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">1≤G≤5</span></span><span style="">；</span></p><p><span style=""><span style="font-family: Times New Roman;">100%</span></span><span style="">的数据：</span><span style=""><span style="font-family: Times New Roman;">1≤V≤25</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">1≤G≤15</span></span><span style="">，</span><span style=""><span style="font-family: Times New Roman;">0≤A<sub>i</sub></span></span><span style="">、</span><span style=""><span style="font-family: Times New Roman;">B<sub>ij</sub>≤1000</span></span><span style="">。</span></p><p><span style=""><br></span></p><p></p>
</div>
</div>