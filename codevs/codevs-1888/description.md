<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>要求在平面直角坐标系下维护两个操作：<br>1. 在平面上加入一条线段。记第i 条被插入的线段的标号为i。<br>2. 给定一个数k,询问与直线x = k 相交的线段中，交点最靠上的线段的编号。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行一个整数n，表示共n 个操作。<br>    接下来n 行，每行第一个数为0 或1。<br>    若该数为0，则后面跟着一个正整数k，表示询问与直线x = ((k + lastans – 1)%39989+1)相交的线段中交点（包括在端点相交的情形）最靠上的线段的编号，其中%表示取余。若某条线段为直线的一部分，则视作直线与线段交于该线段y 坐标最大处。若有多条线段符合要求，输出编号最小的线段的编号。<br>    若该数为1，则后面跟着四个正整数x0, y0, x1, y1，表示插入一条两个端点为((x0+lastans-1)%39989+1,(y0+lastans-1)%109+1)和((x1+lastans-1)%39989+1,(y1+lastans-1)%109+1) 的线段。<br>    其中lastans 为上一次询问的答案。初始时lastans=0。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个0 操作，输出一行，包含一个正整数，表示交点最靠上的线段的编号。若不存在与直线相交的线段，答案为0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6<br>1 8 5 10 8<br>1 6 7 2 6<br>0 2<br>0 9<br>1 4 7 6 7<br>0 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br> 0 <br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于30%的数据，n ≤ 1000</span><br>对于100%的数据，1 ≤ n ≤ 10<sup>5</sup>, 1 ≤ k, x0, x1 ≤ 39989, 1 ≤ y0 ≤ y1 ≤ 10<sup>9</sup>。</p>
</div>
</div>