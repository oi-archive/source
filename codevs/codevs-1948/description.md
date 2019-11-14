<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>NOI2011 在吉林大学开始啦！为了迎接来自全国各地最优秀的信息学选手， 吉林大学决定举办两场盛大的 NOI 嘉年华活动，分在两个不同的地点举办。每 个嘉年华可能包含很多个活动，而每个活动只能在一个嘉年华中举办。 现在嘉年华活动的组织者小安一共收到了 n 个活动的举办申请，其中第 i 个 活动的起始时间为 Si，活动的持续时间为 Ti。这些活动都可以安排到任意一个嘉 年华的会场，也可以不安排。 小安通过广泛的调查发现，如果某个时刻，两个嘉年华会场同时有活动在进 行（不包括活动的开始瞬间和结束瞬间），那么有的选手就会纠结于到底去哪个 会场，从而变得不开心。所以，为了避免这样不开心的事情发生，小安要求不能 有两个活动在两个会场同时进行（同一会场内的活动可以任意进行）。 另外，可以想象，如果某一个嘉年华会场的活动太少，那么这个嘉年华的吸 引力就会不足，容易导致场面冷清。所以小安希望通过合理的安排，使得活动相 对较少的嘉年华的活动数量最大。 此外，有一些活动非常有意义，小安希望能举办，他希望知道，如果第 i 个 活动必须举办（可以安排在两场嘉年华中的任何一个），活动相对较少的嘉年华 的活动数量的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个整数 n，表示申请的活动个数。 接下来 n 行描述所有活动，其中第 i 行包含两个整数 Si、Ti，表示第 i 个活 动从时刻 Si开始，持续 Ti的时间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出的第一行包含一个整数，表示在没有任何限制的情况下，活动较少的嘉 年华的活动数的最大值。 接下来 n 行每行一个整数，其中第 i 行的整数表示在必须选择第 i 个活动的 前提下，活动较少的嘉年华的活动数的最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>8 2</p>
<p>1 5</p>
<p>5 3</p>
<p>3 2</p>
<p>5 3</p>

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
<p>2</p>
<p>1</p>
<p>2</p>
<p><span style="">2</span></p>
<p><span style=""> 2 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】 <br>在没有任何限制的情况下，最优安排可以在一个嘉年华安排活动 1, 4，而在 另一个嘉年华安排活动 3, 5，活动 2 不安排。</p>
<p><br>【数据规模与约定】 <br>1≤n≤200<br>0≤Si≤10<sup>9</sup></p>
<p>1≤Ti≤ 10<sup>9</sup></p>
</div>
</div>