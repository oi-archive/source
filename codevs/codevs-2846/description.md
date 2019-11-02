<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有N个人(编号为1-N)正在玩扳手腕游戏，每个人都有一个力量值K<sub>i</sub>，游戏进行了M轮，每轮为A<sub>i</sub>和A<sub>j</sub>打，请输出谁会赢，(力量不同则力量大的赢，力量相同则编号小的赢)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行N,M；</p>
<p>第二行N个整数，为力量值；</p>
<p>接下来M行每行两个整数，Ai，Aj。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>M行，每行为&ldquo; ** win! &rdquo;(&ldquo;**&rdquo;为胜利者编号) &nbsp;详见样例</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p>
<p>6 4 2 4</p>
<p>2 4</p>
<p>1 1</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 win!</p>
<p>1 win!</p>
<p>4 win! </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据  N≤10,M≤50</p>
<p>对于60%的数据  N≤500,M≤100,000</p>
<p>对于100%的数据 N≤2000,M≤500,000  Ki≤2*10^9</p>
<p>自己和自己打一定是自己赢</p>
</div>
</div>