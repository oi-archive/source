<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在二维平面坐标轴里面，有N只蚂蚁，第i只蚂蚁所在的点的坐标是(x</span><sub><span style="">i</span></sub><span style="">, y</span><sub><span style="">i</span></sub><span style="">)</span><span style="">，坐标都是整数。所有蚂蚁的移动速度都相等，都是每秒移动1个单位。每只蚂蚁都有一个固定的移动方向，是如下4种方向之一，都是平行于坐标轴的：</span></p><p style=""><span style="font-family: Wingdings;">l<span style="font-family: 'Times New Roman';">  </span></span><span style="">N</span><span style="">表示向北（即朝上）， 则y坐标正方向。</span></p><p style=""><span style="font-family: Wingdings;">l<span style="font-family: 'Times New Roman';">  </span></span><span style="">E</span><span style="">表示向东（即朝右）， 则x坐标正方向。</span></p><p style=""><span style="font-family: Wingdings;">l<span style="font-family: 'Times New Roman';">  </span></span><span style="">S</span><span style="">表示向南（即向下）， 则y坐标负方向。</span></p><p style=""><span style="font-family: Wingdings;">l<span style="font-family: 'Times New Roman';">  </span></span><span style="">W</span><span style="">表示向西（即向左）， 则x坐标负方向。</span></p><p style=""><span style="">当2只或多只蚂蚁在某个时刻碰（不一定是整数时刻）撞到一起，那么这些蚂蚁都会立即消失。 例如蚂蚁A的初始位置是(0, 0)且方向是向东，蚂蚁B的初始位置是(1, 0)且方向是向西，那么0.5秒后，两只蚂蚁会在点（0.5, 0）处碰撞，两只蚂蚁瞬间都消失。当所有的碰撞结束后，还有多少只蚂蚁存在？不管蚂蚁最终移动到哪里，只要没有消失，都算是存在。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行，一个整数N（1 </span><span style="">≤</span><span style=""> N </span><span style="">≤</span><span style=""> 50</span><span style="">）。</span></p><p style=""><span style="">第二行，一个长度是N的字符串，第i个字符表示第i只蚂蚁的移动方向。</span></p><p style=""><span style="">接下来有N行，每行两个整数，表示蚂蚁的横坐标x和纵坐标y。</span></p><p style=""><span style="">-1000 </span><span style="">≤</span><span style=""> x,y </span><span style="">≤</span><span style=""> 1000</span><span style="">。输入数据保证，一开始没有两只蚂蚁具有相同的位置。</span></p><p><strong><span style="">对于50%的<span style="">数据</span>， 蚂蚁的坐标范围【-100，100】。</span></strong></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px;font-family:宋体">一个整数，表示当所有的碰撞结束后，存在的蚂蚁的数量。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">4</span></p><p style=""><span style="">NWNE</span></p><p style=""><span style="">0 0</span></p><p style=""><span style="">10 10</span></p><p style=""><span style="">20 20</span></p><p style=""><span style="">30 30</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">N</span><span style="">（1 </span><span style="">≤</span><span style=""> N </span><span style="">≤</span><span style=""> 50</span><span style="">）</span></p><p><span style=""><span style="">-1000 </span><span style="">≤</span><span style=""> x,y </span><span style="">≤</span><span style=""> 1000</span></span></p>
</div>
</div>