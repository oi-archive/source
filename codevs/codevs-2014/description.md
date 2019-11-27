<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>电阻是构成电子线路的基本元件（图一）。电阻有一定的阻值<span>R</span>（单位<span>0</span>），当在其两端加上一定的电压<span>U</span>（单位<span>V</span>）时，会有一定的电流<span>1</span>（单位<span>A</span>）从高电位流向低电位。根据电阻的欧姆定律，有<span>U</span>＝<span>IR</span>。</p>
<p>电阻的两种基本连接方式是串联和并联。从两端来看，串、并联电阻可以被视作个等效电阻。串联是指两个电<span>till</span>首尾相接（图二）满足<span>U</span>＝<span>Ui</span>＋<span>U2</span>，<span>1=11</span>＝<span>12</span>；并联是指两个电阻的两端分别共同连接到电路中（图三），满足<span>U</span>＝<span>U1=U2</span>，<span>I=I1</span>＋<span>I2</span>。以上<span>U1</span>、<span>U2</span>、<span>I1</span>、<span>I2</span>分别是两个电阻止的电压和电流，<span>U</span>、<span>I</span>分别是等效电阻上的电压和电流。</p>
<p>等效电阻可以继续与其他电阻或等效电阻串、并联以构成电阻网络。当在电阻网络的的端加以一定的电压时，电阻网络中每一个电阻上的电压和电流都司”以根据欧姆定律和串并联公式解出。图四是一个电阻网络的例子。</p>
<p>写一个程序以求解电阻网络。</p>

<img src="/source/codevs/codevs-2014/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMDE0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NjcxMzA3MC4zMzAuNjY0Mzk0MDE3MDA0LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行是电阻的个数<span>N</span>（<span>N</span>＜<span>100</span>）。接下来的<span>N</span>行每行给出了一个电阻的信息。首先是一个整数，表示该电阻的阻值，其后是与该电阻一端相连的所有电阻的编号，之后有一个<span>0</span>，表示一端连接情况描述完；接着是与该电阻另一端相连的所有电阻的编号。其后再放一个<span>0</span>，结束这一行。输入文件的最后一行给出了所加电压信息。首先是所加电压的值，其后先是若干个电阻的编号，接着用一个<span>0</span>结束高电位端的描述；再其后用同样的结构给出了低电位端接电阻的情况。输入文件同叫于中各数据之间均用一个空格隔<span>1</span>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件有<span lang="EN-US">N</span>行，依电阻编号顺序，每行给出了一个电阻上的电压和电流的信息。中间用一个空格隔开。结果精确到小数点后<span lang="EN-US">2</span>位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6</span></p>
<p><span>4 2 4 0 2 3 0</span></p>
<p><span>4 1 4 0 1 3 0</span></p>
<p><span>2 1 2 0 4 0</span></p>
<p><span>4 1 2 0 3 0</span></p>
<p><span>4 1 2 4 0 3 4 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>2</span>．<span>00 0</span>．<span>50</span></p>
<p><span>2</span>．<span>OO 0</span>．<span>50</span></p>
<p><span>2</span>．<span>OO 1</span>．<span>OO</span></p>
<p><span>4</span>．<span>OO 1</span>．<span>0O</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围好小</p>
</div>
</div>