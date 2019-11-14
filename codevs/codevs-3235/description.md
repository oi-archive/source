<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<pre>2050年，人类与外星人之间的战争已趋于白热化。就在这时，人类发明出
一种超级武器，这种武器能够同时对相邻的多个目标进行攻击。凡是防御力小于或
等于这种武器攻击力的外星人遭到它的攻击，就会被消灭。然而，拥有超级武器是
远远不够的，人们还需要一个战地统计系统时刻反馈外星人部队的信息。这个艰巨
的任务落在你的身上。请你尽快设计出这样一套系统。

这套系统需要具备能够处理如下2类信息的能力：

1.外星人向[x1，x2]内的每个位置增援一支防御力为v的部队。
2.人类使用超级武器对[x1，x2]内的所有位置进行一次攻击力为v的打击。系统需
要返回在这次攻击中被消灭的外星人个数。

注：防御力为i的外星人部队由i个外星人组成，其中第j个外星人的防御力为j。</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<pre>    第一行读入n，m。其中n表示有n个位置，m表示有m条信息。
以下有m行，每行有4个整数k，x1，x2，v用来描述一条信息 。k表示这条信息属
于第k类。x1，x2，v为相应信息的参数。k=1 or 2。
注：你可以认为最初的所有位置都没有外星人存在。
规模：0&lt;n&lt;=1000；0&lt;x1&lt;=x2&lt;=n；0&lt;v&lt;=1000；0&lt;m&lt;=2000</pre>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<pre>结果输出。按顺序输出需要返回的信息。</pre>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3 5
1 1 3 4
2 1 2 3
1 1 2 2
1 2 3 1
2 2 3 5
</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>详见试题</p>
</div>
</div>