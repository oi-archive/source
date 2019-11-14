<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡夜晚的迷途竹林中，正如其名，十分迷乱，于是博丽灵梦决定在迷途竹林的小径上修筑火灯。已知路长n个单位，从1到n，每一个单位上都有一个火灯。今晚是她负责点燃火灯，作为她的好“机油”，你能帮她吗？</p>
<p>魔理沙给了她一张点火单，上面有m个数，这意味着，她要去m次，例如在第s次的时候，她每走到一个单位就要判断：假如所处单位好能被m[s]整除，便改变火灯的点燃状态，详看提示</p>
<p>created by Izayoi Sakuya</p>

<img src="/source/codevs/codevs-2874/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yODc0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8yODc0LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>n,m 下面m行,为m[s]</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>暗的火灯数目</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 2</p>
<p>2</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>s=1 open:2 4 6 8 10</p>
<p>s=2 open:3 9; close:6</p>
<p>n&lt;=100000 m&lt;=10000 m[s]&lt;=5000</p>
</div>
</div>