<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    H城是一个旅游胜地，每年都有成千上万的人前来观光。为方便游客，巴士公司在各个旅游景点及宾馆，饭店等地都设置了巴士站并开通了一些单程巴上线路。每条单程巴士线路从某个巴士站出发，依次途经若干个巴士站，最终到达终点巴士站。</p>
<p>    一名旅客最近到H城旅游，他很想去S公园游玩，但如果从他所在的饭店没有一路巴士可以直接到达S公园，则他可能要先乘某一路巴士坐几站，再下来换乘同一站台的另一路巴士, 这样换乘几次后到达S公园。</p>
<p>    现在用整数1,2,<span style="font-family: 'Courier New';">…</span>N 给H城的所有的巴士站编号，约定这名旅客所在饭店的巴士站编号为1…S公园巴士站的编号为N。</p>
<p>    写一个程序，帮助这名旅客寻找一个最优乘车方案,使他在从饭店乘车到S公园的过程中换车的次数最少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件是INPUT.TXT。文件的第一行有两个数字M和N(1&lt;=M&lt;=100 1&lt;N&lt;=500），表示开通了M条单程巴士线路，总共有N个车站。从第二行到第M刊行依次给出了第1条到第M条巴士线路的信息。其中第i+1行给出的是第i条巴士线路的信息，从左至右按运行顺序依次给出了该线路上的所有站号相邻两个站号之间用一个空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p15">&nbsp; &nbsp; 输出文件是OUTPUT.TXT，文件只有一行。如果无法乘巴士从饭店到达S公园，则输出"N0"，否则输出你的程序所找到的最少换车次数，换车次数为0表示不需换车即可到达。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 7</p>
<p>6 7</p>
<p>4 7 3 6</p>
<p>2 1 3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

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