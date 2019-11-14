<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">石头剪刀布是常见的猜拳游戏：石头胜剪刀，剪刀胜布，布胜石头。如果两个人出拳一样，则不分胜负。在《生活大爆炸》第二季第8集中出现了一种石头剪刀布的升级版游戏。升级版游戏在传统的石头剪刀布游戏的基础上，增加了两个新手势： </p><p style="">斯波克：《星际迷航》主角之一。 蜥蜴人：《星际迷航》中的反面角色。  </p><p style="">这五种手势的胜负关系如表一所示，表中列出的是甲对乙的游戏结果。</p><p style=""><img src="/source/codevs/codevs-3716/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNzE2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDQzMDIzMDg1NV80NDQucG5n.png" title=""></p><p><br style=""></p><p style="">现在，小A和小B尝试玩这种升级版的猜拳游戏。已知他们的出拳都是有周期性规律的，但周期长度不一定相等。例如：如果小A以“石头-布-石头-剪刀-蜥蜴人-斯波克”长度为6的周期出拳，那么他的出拳序列就是“石头-布-石头-剪刀-蜥蜴人-斯波克-石头-布-石头-剪刀-蜥蜴人-斯波克-„„”，而如果小B以“剪刀-石头-布-斯波克-蜥蜴人”长度为5的周期出拳，那么他出拳的序列就是“剪刀-石头-布-斯波克-蜥蜴人-剪刀-石头-布-斯波克-蜥蜴人-„„” </p><p> </p><p style="">已知小A和小B一共进行N次猜拳。每一次赢的人得1分，输的得0分；平局两人都得0分。现请你统计N次猜拳结束之后两人的得分。</p><p><br style=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件名为rps.in。 </p><p>第一行包含三个整数：N，NA，NB，分 别 表 示 共 进 行N次猜拳、小A出拳的周期长度，小B出拳的周期长度。数与数之间以一个空格分隔。 </p><p>第二行包含NA个整数，表示小A出拳的规律，第三行包含NB个整数，表示小B出拳的规律。其中，0表示“剪刀”，1表示“石头”，2表示“布”，3表示“蜥蜴人”，  4表示“斯波克”。数与数之间以一个空格分隔。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件名为rps.out。&nbsp;</p><p>输出一行， &nbsp;包含两个整数，以一个空格分隔，分别表示小A、小B的得分。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><img src="/source/codevs/codevs-3716/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNzE2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDQzMDIzMDgxN181NjgucG5n.png" title=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><img src="/source/codevs/codevs-3716/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNzE2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDQzMDIzMDgzM18zODMucG5n.png" title=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，0 &lt; N ≤  200，0 &lt; NA  ≤  200，  0 &lt; NB  ≤  200。</p>
</div>
</div>