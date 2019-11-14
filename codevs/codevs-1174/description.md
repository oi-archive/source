<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小城和小华都是热爱数学的好学生，最近，他们不约而同地迷上了数独游戏，好胜的他<br>们想用数独来一比高低。但普通的数独对他们来说都过于简单了，于是他们向Z 博士请教，<br>Z 博士拿出了他最近发明的“靶形数独”，作为这两个孩子比试的题目。<br>靶形数独的方格同普通数独一样，在 9 格宽×9 格高的大九宫格中有9 个3 格宽×3 格<br>高的小九宫格（用粗黑色线隔开的）。在这个大九宫格中，有一些数字是已知的，根据这些</p>
<p>数字，利用逻辑推理，在其他的空格上填入1 到9 的数字。每个数字在每个小九宫格内不能<br>重复出现，每个数字在每行、每列也不能重复出现。但靶形数独有一点和普通数独不同，即<br>每一个方格都有一个分值，而且如同一个靶子一样，离中心越近则分值越高。</p>
<p> </p>
<p>上图具体的分值分布是：最里面一格（黄色区域）为 10 分，黄色区域外面的一圈（红<br>色区域）每个格子为9 分，再外面一圈（蓝色区域）每个格子为8 分，蓝色区域外面一圈（棕<br>色区域）每个格子为7 分，最外面一圈（白色区域）每个格子为6 分，如上图所示。比赛的<br>要求是：每个人必须完成一个给定的数独（每个给定数独可能有不同的填法），而且要争取<br>更高的总分数。而这个总分数即每个方格上的分值和完成这个数独时填在相应格上的数字<br>的乘积的总和。如图，在以下的这个已经填完数字的靶形数独游戏中，总分数为2829。游<br>戏规定，将以总分数的高低决出胜负。</p>
<p>由于求胜心切，小城找到了善于编程的你，让你帮他求出，对于给定的靶形数独，能<br>够得到的最高分数。</p>

<img src="/source/codevs/codevs-1174/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMTc0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMTc0LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一共 9 行。每行9 个整数（每个数都在0—9 的范围内），表示一个尚未填满的数独方<br>格，未填的空格用“0”表示。每两个数字之间用一个空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出可以得到的靶形数独的最高分数。如果这个数独无解，则输出整数-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例 1】</p>
<p>7 0 0 9 0 0 0 0 1<br>1 0 0 0 0 5 9 0 0<br>0 0 0 2 0 0 0 8 0<br>0 0 5 0 2 0 0 0 3<br>0 0 0 0 0 0 6 4 8<br>4 1 3 0 0 0 0 0 0<br>0 0 7 0 0 2 0 9 0<br>2 0 1 0 6 0 8 0 4<br>0 8 0 5 0 4 0 1 2</p>
<p>【输入输出样例 2】</p>
<p>0 0 0 7 0 2 4 5 3<br>9 0 0 0 0 8 0 0 0<br>7 4 0 0 0 5 0 1 0<br>1 9 5 0 8 0 0 0 0<br>0 7 0 0 0 0 0 2 5<br>0 3 0 5 7 9 1 0 8<br>0 0 0 6 0 1 0 0 0<br>0 6 0 9 0 0 0 0 1<br>0 0 0 0 0 0 0 0 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例 1】</p>
<p>2829</p>
<p>【输入输出样例 1】</p>
<p>2852</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】<br>40%的数据，数独中非0 数的个数不少于30。<br>80%的数据，数独中非0 数的个数不少于26。<br>100%的数据，数独中非0 数的个数不少于24。</p>
</div>
</div>