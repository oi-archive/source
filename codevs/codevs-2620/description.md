<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Smart和Sarah正在玩一个即时战略游戏。</p>
<p>Smart在他的基地附近建立了n个战壕，每个战壕都是一个独立的作战单位，射程可以达到无限，但是，战壕有一个弱点：就是只能攻击它的左下方，说白了就是横、纵坐标都不大于它的点。这样，Sarah就可以从别的地方进攻摧毁战壕，从而消灭Smart的部队。</p>
<p>战壕都有一个保护范围，同它的攻击范围一样，它可以保护处在它左下方的战壕。所有处于它保护范围的战壕都叫做它的保护对象。这样，Sarah就必须找到Smart的战壕中保护对象最多的战壕，从而优先消灭它。</p>
<p>现在，由于Sarah没有时间来计算，所以拜托你来完成这个任务：给出这n个战壕的坐标(xi、yi)，要你求出保护对象个数为0，1，2……n-1的战壕的个数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个正整数n（1≤n≤5000）</p>
<p>接下来n行，每行两个数xi,yi，代表第i个点的坐标（1≤xi,yi≤32767）注意：可能包含多重战壕的情况（即有数个点在同一坐标）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出n行，分别代表保护对象有0，1，2&hellip;&hellip;n-1个的战壕个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>1 1</p>
<p>5 1</p>
<p>7 1</p>
<p>3 3</p>
<p>5 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>2</p>
<p>1</p>
<p>1</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>时间限制</p>
<p>1s</p>
</div>
</div>