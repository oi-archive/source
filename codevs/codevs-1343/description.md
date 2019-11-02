<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有N个蚱蜢排成一排，它们按下列两种方式移动：</p>
<p>位置A上的蚱蜢向左跳过B个蚱蜢 （表示为A L B）</p>
<p>位置A上的蚱蜢向右跳过B个蚱蜢（表示为A D B）</p>
<p>所有蚱蜢的高度不一定相同，当一个蚱蜢跳跃时，不能碰到其它蚱蜢的腿，也就是说跳跃的高度不低于最高的一个蚱蜢。给出跳跃的顺序，输出它们跳跃的高度。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数N和J (2 ≤ N ≤ 100 000, 1 ≤ J ≤ 100 000), 表示有N个蚱蜢排成一排，有J个蚱蜢跳跃。</p>
<p>第二行有N个整数（N&lt;100000），表示蚱蜢高度。</p>
<p>后面有J行，每行为一个蚱蜢跳跃的信息，每行三个数，第一个是整数A表示跳跃蚱蜢的位置（相对位置，最左边的蚱蜢位置为1，最右边的蚱蜢位置为N）。第二个数为跳跃的方向( 'L' 向左， 'D' 向右)，第三个是整数B表示跳跃的蚱蜢所跃过的蚱蜢数，每个跳跃都是有效的（即B少于或等于蚱蜢A相应边的蚱蜢数）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">输出共J行，每行一个数，表示蚱蜢跳跃的最少高度</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 3</p>
<p>5 3 8 4 9 3 7 4 2</p>
<p>2 D 3</p>
<p>8 L 2</p>
<p>5 D 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>
<p>7</p>
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
<p><span>第一个蚱蜢跳过的高度为</span><span>8, 4 </span><span>和</span><span> 9</span><span>的蚱蜢。</span><span>下一个蚱蜢跳过高度为</span><span> 3 </span><span>和</span><span> 7</span><span>的蚱蜢，最后一个蚱蜢跳过高度为</span><span> 3 </span><span>和</span><span> 4</span><span>的蚱蜢</span><span>.</span></p>
</div>
</div>