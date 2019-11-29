<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><strong>打豆豆是一款很有意思的flash小游戏，游戏规则很简单。</strong></p><p style=""><span style="">一个N*M的方阵，每个格子都可能有0到1个豆豆。豆豆有颜色的区别。</span></p><p style=""><span style="">游戏者每次必须点击一个空格(点击★处,四个方向的豆豆分别为 紫紫棕蓝)</span></p><p style=""><span style="">此时在四条十字线的延时方向上最先遇到的豆子中，如果有同色的，那么就可以把这些同色的打掉。</span></p><p style=""><span style="">注意：往上下左右4个方向走到的第一颗豆子。有可能走不到豆子。</span></p><p style="">图里面，两个紫色的豆子就会被打掉。</p><p style="">小Y眼疾手快。玩了几次以后就可以接近全部打完了。</p><p style="">小X思维反应比较慢。。小Z觉得玩游戏是浪费时间浪费生命，所以决定找你们这帮搞OI的帮他写一个。不料这帮搞OI其实恨死XYZ三人组了。</p><p style="">值得庆幸的是，purpleslz神牛已经负责把在线仙人球嵌套动态网络路径剖分优化的分支定界贪心剪枝启发式迭代加深人工智能搜索决策算法给写了，所以你的任务比较简单。</p><p style="">对于输入的状态，你只需要计算有多少个地方现在点击是可以打掉豆豆的。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行正整数N和M表示行列数</span><br style=""><span style="">接下来N×M个数字，每个数字都是0到S的整数</span><br style=""><span style="">（1到S表示不同颜色的豆豆 0表示空的格子）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="FONT-SIZE: 12px; FONT-FAMILY: 宋体; LINE-HEIGHT: 20px; BACKGROUND-COLOR: rgb(255,255,255)">一个整数，表示多少个格子是可以打豆豆的。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 5</span><br style=""><span style="">0 1 2 0 0</span><br style=""><span style="">0 3 0 3 0</span><br style=""><span style="">2 0 0 4 2</span><br style=""><span style="">0 5 5 6 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">前30%的数据  N,M≤10</span><br style=""><span style="">中30%的数据  N,M≤100</span><br style=""><span style="">后40%的数据  N,M≤1000</span><br style=""><span style="">对于每个部分，都会有一个点S=1，一个点S≤5，其余的点S≤1000</span></p>
</div>
</div>