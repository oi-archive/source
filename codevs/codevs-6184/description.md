<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>GBY所在的神犇中学又开始练习广播操了，GBY受不了炎炎烈日，趁集合时偷偷逃到机房刷题，GBY所在学校的班级和机房间的路线神奇的在一个神奇的校园网络上，该神奇的网络有n个班，这些教室门前有m个通道，每个通道只能过一定数量的人，μ老师听说GBY居然逃操（可他不知道GBY去哪了），于是生气的派出q队人马，分别从不同的教室出发前往不同的教室（他们只经过路途中的通道，不会进入途中的教室），Gary即在指挥这些人马，他希望使每队的人马人数最大化，这样好在抓到GBY后暴揍他一顿，可是Gary暂时没有头绪，他想请你帮助他求出各组人数的最大值</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入n，m分别表示教室数，通道数</p><p>之后m行输入a,b，c三个数表示a，b两教室间有通道，最多过c个人（可能会有很多条路呢-.-）</p><p>第m+2行输入q，表示派出的队伍数</p><p>接下来q行分别输入两个数 a，b 表示这队人马从a教室出发去b教室抓GBY</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>q行 分别对每个询问输出最大人马数</p><p>特别的如果不能a教室根本到达不了b教室 输出-1</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 3 </span><br style=""><span style="">1 2 10 </span><br style=""><span style="">2 3 5</span><br style=""><span style="">3 1 1 </span><br style=""><span style="">2</span><br style=""><span style="">1 4 </span><br></p><p><span style="">1 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p><p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于 30%的数据，0 &lt; n &lt; 1,000，0 &lt; m &lt; 10,000，0 &lt; q &lt; 1,000； </span><br style=""><span style="">对于 100%的数据，0 &lt; n &lt; 10,000，0 &lt; m &lt; 50,000，0 &lt; q &lt; 30,000，0 ≤ z ≤ 100,000。</span></p>
</div>
</div>