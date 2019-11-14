<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> 在幻想乡，雾雨魔理沙是住在魔法之森普通的黑魔法少女。话说最近魔理沙从香霖堂拿到了升级过后的的迷你八卦炉，她迫不及待地希望试试八卦炉的威力。在一个二维平面上有许多毛玉(一种飞行生物，可以视为点)，每个毛玉具有两个属性，分值value和倍率mul。八卦炉发射出的魔法炮是一条无限长的直线形区域，可以视为两条倾斜角为α的平行线之间的区域，平行线之间的距离可以为任意值，如下图所示：</p>
<p> </p>
<p>蓝色部分上下两条长边之间就是这次八卦炉的攻击范围，在蓝色范围内的毛玉(红点)属于该此被击中的毛玉，如果一个毛玉刚好在边界上也视为被击中。毛玉击中以后就会消失，每次发射八卦炉得到分值是该次击中毛玉的分值和乘上这些毛玉平均的倍率，设该次击中的毛玉集合为S，则分值计算公式为:</p>
<p>    Score = SUM{value[i] | i 属于 S} * SUM{mul[i] | i 属于 S} / |S|</p>
<p>其中|S|表示S的元素个数。魔理沙将会使用若干次八卦炉，直到把所有毛玉全部击中。任意两次攻击的范围均不重叠。最后得到的分值为每次攻击分值之和。现在请你计算出能够得到的最大分值。</p>

<img src="/source/codevs/codevs-1377/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMzc3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM3Ny5ibXA=.bmp" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：1个整数N，表示毛玉个数</p>
<p>第2..N+1行：每行四个整数x, y, value, mul，表示星星的坐标(x,y)，以及value和mul</p>
<p>第N+2行：1个整数α，表示倾斜角角度，0°到180°</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：1个实数，表示最大分值，保留三位小数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 3 3 1</p>
<p>2 1 2 2</p>
<p>3 4 2 1</p>
<p>45</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9.333</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于60%的数据：1 &lt;= N &lt;= 500</p>
<p>对于100%的数据：1 &lt;= N &lt;= 2,000</p>
<p>-10,000 &lt;= x,y &lt;= 10,000</p>
<p>1 &lt;= value,mul &lt;= 100</p>
<p>π = 3.1415926  </p>
</div>
</div>