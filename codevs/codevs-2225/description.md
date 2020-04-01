<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一架人类的航天飞机将人类基地建在了一个荒芜的星球上。面对紧缺的能源，他们只能在最短的时间内用SCV（一种智能机器人）采集必须的矿藏。对于这个艰巨的任务，他们希望得到编程高手们的帮助。</p>
<p>在这个星球上，有着两种不同的矿。一种被称为“冰矿”，是一种类似H<sub>2</sub>O的凝固物的蓝色高能矿藏。另一种被称为“气矿”，是四氯化碳的一种异态形式。人类通过这两种矿的提炼，获得可供生存的能源。</p>
<p>SCV是一种唯一可以采集这两种矿的智能机器人。他们每采集一次冰矿需要花费t<sub>1</sub>的时间，每采集一次气矿需要花费t<sub>2</sub>的时间。采集结束后，将得到8个冰矿或者８个气矿单位。每一次SCV只能采集冰矿或者是气矿中的一种。</p>
<p>SCV可以通过主基地制造。每制造一个SCV，主基地将花费50单位的冰矿。而主基地由于制造能力有限，在同一时间只能制造一个SCV。制造一个SCV需要t<sub>3</sub>的时间。</p>
<p>在开始时，人类拥有50个单位的冰矿和4个SCV。在最短的时间之内，他们需要至少采集到p<sub>1</sub>单位的冰矿和p<sub>2</sub>单位的气矿。请计算出他们需要的最短时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件只有一行，依次为t<sub>1</sub>,t<sub>2</sub>,t<sub>3</sub>,p<sub>1</sub>,p<sub>2</sub>，每两个数字之间有一个空格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只包含一个数字，表示可以达到目标的最少时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 9 18 150 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=t<sub>1</sub>,t<sub>2</sub>,t<sub>3</sub>&lt;=100,0&lt;=p<sub>1</sub>,p<sub>2</sub>&lt;=10000</p>
</div>
</div>