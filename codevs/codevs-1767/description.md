<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>工匠小K最近有n个零件需要加工。每个零件都需要ti天的时间来完成，每个零件每延迟一天加工都要缴纳一定的罚金si。延迟的天数为从今天算起到该工作开始的那天，第一个零件加工没有罚金。现在小K想知道怎样安排加工顺序可以使他要交的罚金最少，最少是多少。 这个数可能会很大，请输出这个数对m取模后的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为一个整数<em>n</em>，表示需要加工的零件总数。</p>
<p>第二行为一个整数<em>m</em>，表示答案要对<em>m</em>取模。</p>
<p>第3~<em>n</em>+2行，每行两个整数<em>t<sub>i</sub></em>和<em>s<sub>i</sub></em>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行，一个整数，表示小K最少要缴纳的罚金对<em>m</em>取模的结果</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>100</p>
<p>3 3</p>
<p>6 4</p>
<p>2 2</p>
<p>8 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>81</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如果按照1→2→3→4的顺序进行加工，需要缴纳的罚金为0×3+3×4+(3+6)×2+</p>
<p>(3+6+2)×5=85；</p>
<p>最佳方案是3→1→2→4，此时需要缴纳的罚金为0×2+2×3+(2+3)×4+(2+3+6)×5=81。</p>
<p> </p>
<p>【数据范围】</p>
<p>对于40%的数据，0&lt;<em>n</em>≤10,000，0&lt;<em>t<sub>i</sub></em>,<em>s<sub>i</sub></em>≤10,000；</p>
<p>对于80%的数据，0&lt;<em>n</em>≤100,000，0&lt;<em>t<sub>i</sub></em>,<em>s<sub>i</sub></em>≤2×10<sup>9</sup>，0&lt;<em>m</em>≤10<sup>8</sup>；</p>
<p>对于100%的数据，0&lt;<em>n</em>≤100,000，0&lt;<em>t<sub>i</sub></em>,<em>s<sub>i</sub></em>≤2×10<sup>9</sup>，0&lt;<em>m</em>≤10<sup>18</sup>。</p>
</div>
</div>