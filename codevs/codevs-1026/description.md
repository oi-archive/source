<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>年轻的拉尔夫开玩笑地从一个小镇上偷走了一辆车，但他没想到的是那辆车属于警察局，并且车上装有用于发射车子移动路线的装置。</p>
<p>那个装置太旧了，以至于只能发射关于那辆车的移动路线的方向信息。</p>
<p>编写程序，通过使用一张小镇的地图帮助警察局找到那辆车。程序必须能表示出该车最终所有可能的位置。</p>
<p>小镇的地图是矩形的，上面的符号用来标明哪儿可以行车哪儿不行。“.”表示小镇上那块地方是可以行车的，而符号“X”表示此处不能行车。拉尔夫所开小车的初始位置用字符的“*”表示，且汽车能从初始位置通过。</p>
<p>汽车能向四个方向移动：向北(向上)，向南(向下)，向西(向左)，向东(向右)。</p>
<p>拉尔夫所开小车的行动路线是通过一组给定的方向来描述的。在每个给定的方向，拉尔夫驾驶小车通过小镇上一个或更多的可行车地点。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含两个用空格隔开的自然数R和C，1≤R≤50，1≤C≤50，分别表示小镇地图中的行数和列数。</p>
<p>以下的R行中每行都包含一组C个符号(“.”或“X”或“*”)用来描述地图上相应的部位。</p>
<p>接下来的第R+2行包含一个自然数N，1≤N≤1000，表示一组方向的长度。</p>
<p>接下来的N行幅行包含下述单词中的任一个：NORTH(北)、SOUTH(南)、WEST(西)和EAST(东)，表示汽车移动的方向，任何两个连续的方向都不相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件应包含用R行表示的小镇的地图(象输入文件中一样)，字符&ldquo;*&rdquo;应该仅用来表示汽车最终可能出现的位置。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 5</span></p>
<p>.....</p>
<p>.X...</p>
<p>...*X</p>
<p>X.X..</p>
<p>3</p>
<p>NORTH</p>
<p>WEST</p>
<p>SOUTH</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">.....</span></p>
<p>*X*..</p>
<p>*.*.X</p>
<p>X.X..</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>