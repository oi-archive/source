<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【Shadow 1】第一题</p>
<p>WJMZBMR买了很多糖果，分成了N堆，排成一列。WJMZBMR说，如果Shadow能迅速求出第L堆到第R堆一共有多少糖果，就把这些糖果都给他。</p>
<p>现在给出每堆糖果的数量，以及每次询问的L和R，你需要帮助Shadow，把每次询问的结果求出来。注意，你不需要考虑糖果被Shadow取走的情况。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行，2的整数N,M，分别表示堆数和询问数量；</p>
<p>第2行，N个整数Ai，表示第i堆糖果的数量；</p>
<p>第3-(M+2)行，每行2个整数Li, Ri，表示第i个询问是[Li, Ri]。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>M行，对于每个询问，输出对应的和。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>5 5</div>
<div>1 2 3 4 5</div>
<div>1 5</div>
<div>2 4</div>
<div>3 3</div>
<div>1 3</div>
<div>3 5</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>15</div>
<div>9</div>
<div>3</div>
<div>6</div>
<div>12</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于50%的数据，1≤N,M≤100；</span><br><span>对于100%的数据，1≤N,M≤100000，0≤Ai≤1000，1≤Li≤Ri≤N。</span></p>
</div>
</div>