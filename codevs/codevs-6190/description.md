<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>所谓傻瓜电梯指的是在响应用户请求时缺乏相应的“智商”， 在上升或下降的过程中不能把中途的乘客捎带入电梯，而只会严格按照用户发出请求的先后顺序依次完成任务。比如，原来电梯在1楼，首先6楼有一位乘客发出请求，要求由6楼乘坐到10楼去，此时电梯马上会上去， 但在电梯上升到3楼时，另外一位乘客请求由5楼乘坐到8楼去，傻瓜电梯却不会在上升途中把5楼的乘客捎带上去，而只会先把6楼的乘客送到10楼，然后再下来把5搂的乘客送到8楼。</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>傻瓜电梯由i楼上升到i+1楼（或下降到i-1楼）的时间都是3秒，每到达一个楼层，不管进出乘客有多少，也不管乘客只有进、只有出或者进出电梯都有，所耽搁的时间都是6秒。现在味味要根据傻瓜电梯接受到的n个用户请求，编程计算傻瓜电梯把所有乘客送到目标楼层时总共所需要的时间。</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>如果某批乘客到达目标楼层后，电梯没有马上要响应的请求，则电梯在前一批乘客的目的地等待，这个等待时间也需计入总花费时间。直到下一批乘客发出新请求，电梯才会从当前位置出发，前往下一批乘客的出发楼层。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>第一行包含两个整数 x（1&lt;=x&lt;=100）和 n（1&lt;=n&lt;=100），分别表示傻瓜电梯开始所在的楼层和总共接收到的请求数目。</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>下面有n行，每行包含3个整数，依次表示该请求发出的时间、乘客目前所在的楼层和将要去的目标楼层。其中请求发出的时间以秒为时刻单位，最大可能的值是2000。如果某两个请求的发出时间相同，则按照输入数据原始的先后顺序依次处理。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &quot;Segoe UI&quot;, &quot;Lucida Grande&quot;, Helvetica, Arial, &quot;Microsoft YaHei&quot;, FreeSans, Arimo, &quot;Droid Sans&quot;, &quot;wenquanyi micro hei&quot;, &quot;Hiragino Sans GB&quot;, &quot;Hiragino Sans GB W3&quot;, FontAwesome, sans-serif; font-size: 15px; background-color: rgba(255, 255, 255, 0.8);">只包含一行，一个整数，表示傻瓜电梯把所有乘客送到目标楼层后总共所需要的时间（从得到第一条请求时开始计算时间），单位是秒。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style='font-family: Monaco, Menlo, Consolas, "Courier New", FontAwesome, monospace;'>3 4
10 10 2
18 1 9
2 1 12
8 6 10</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style='font-family: Monaco, Menlo, Consolas, "Courier New", FontAwesome, monospace;'>162</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>【样例解释】</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>第一批乘客发出请求到离开电梯所需时间：3*2+6+3*11+6=51</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>从前一批乘客离开电梯到第二批乘客离开电梯所需时间：3*6+6+3*4+6=42</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>第三批乘客从出发地出发到离开电梯所需时间：3*8+6=30</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>（由于出发地与前一批乘客目的地相同，所以上下客时间不必再加 6）</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>从前一批乘客离开电梯到第四批乘客离开电梯所需时间：3+6+3*8+6=39</p><p style='font-family: "Segoe UI", "Lucida Grande", Helvetica, Arial, "Microsoft YaHei", FreeSans, Arimo, "Droid Sans", "wenquanyi micro hei", "Hiragino Sans GB", "Hiragino Sans GB W3", FontAwesome, sans-serif;'>总花费时间：51+42+30+39=162</p><p><br></p>
</div>
</div>