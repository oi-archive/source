<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>hjw是偏远小渔村初一OI群里的神犇。</p><p>由于hjw越来越神,而且还装蒟，其他初一的蒟蒻开始羡慕嫉妒他了。。。</p><p>于是，初一蒟蒻们打算坑一下hjw</p><p><span style="text-decoration: line-through;">Ps：蒟蒻怎么可以坑神犇呢？</span><span style="text-decoration: none;"></span></p><p>于是，蒟蒻们想出了一个绝妙的坑人计划：</p><p>他们把hjw放进了一个神奇的数字矩阵。。。</p><p>这个矩阵很神奇：</p><p>它有n行n列...</p><p>每个格子都是1至9里的数字，代表hjw要在这里颓废几秒才能出发去下一个格子。</p><p>目前hjw在格子（1,1）他已经颓废了几秒，他要尽快赶到（n，n）走出这个矩阵。</p><p>但是，hjw看到这些数字傻了眼，一时想不出走出去的最快路径。。。</p><p>于是，他找到了你，请你帮他走出去，并告诉他走出去需要多久，他才可以去学习...</p><p>因为数据可能比较大，所以输出答案%10000007</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：n</p><p>接下来是这个矩阵。。。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>hjw需要多少秒才能走出迷宫。。。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>5 1 5 </p><p>6 1 1 </p><p>2 9 7 </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1500</p><p>hjw在第一格也要颓废</p><p>样例解释：</p><p>hjw走出迷宫的路径：</p><p><img src="/source/codevs/codevs-6025/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy02MDI1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE3MDQyMjEwNDUxM18yMTQucG5n.png" title=""></p><p>hjw总共颓废了5+1+1+7=15秒。。。</p><p><span style="text-decoration: line-through;">大家最好用深搜写。。</span><span style=""><sub>你信</sub></span></p>
</div>
</div>