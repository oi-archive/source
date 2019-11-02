<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""></span>小J的幼儿园在星期三被小X炸掉了，因为隔壁的幼儿园还有很多空的班级，小J幼儿园的校长紧急联系了隔壁的幼儿园，请求带小朋友们去避(shang)难(ke)。众所周知，每个小朋友到了一个新的环境都会对这个环境产生好奇。小J隔壁的幼儿园充满了滑梯。可惜滑梯之间没有接通。</p><p><span style=""></span>这个幼儿园的地上有很多滑梯，小J可以使得滑梯i和滑梯j连通。首先我们把牛顿的棺材板盖紧，接着我们放心假设我们可以由任何一个滑梯的起点滑向它的重点（哪怕滑向自己），但我们不能沿着同一个通道反过来走（即这是一条有向边）。由于滑梯只有一个出口(不然小J无法控制自己滑向哪边)，所以每个滑梯只能连接向另一个滑梯。小J观察到这是一个图结构，小J觉得只是简单地拼装太没意思了，回想到自己平时吃的棒棒糖，小J发明了一种滑梯结构：先由i向j滑(i,j可相同)，再从j滑一次又滑回j。小J称这种结构为棒棒糖结构。小J想知道对于n个滑梯，共由多少个图，使得图中有n个棒棒糖结构。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅一个整数n表示滑梯数量</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个整数表示图的数量，由于答案很大，请将答案mod10^9+7后输出</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：2</p><p>样例输入2：4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><br></p><p>样例输出1：3</p><p>样例输出2：41</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>提示：</p><p><span style=""></span>样例1的三种情况分别为：如图 </p><p>数据范围</p><p>    对于40%的数据，n&lt;=8</p><p>    对于100%的数据，n&lt;=2000000</p><p><br></p>
</div>
</div>