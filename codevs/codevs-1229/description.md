<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<div>Lele 最近上课的时候都很无聊，所以他发明了一个数字游戏来打发时间。  这个游戏是这样的，首先，他拿出几张纸片，分别写上0到9之间的任意数字(可重复写某个数字)，然后，他叫同学随便写两个数字X和K。Lele要做的事情就是重新拼这些纸牌，组成数字 T ，并且 T + X 是 K 的正整数倍。 有时候，当纸片很多的时候，Lele经常不能在一节课之内拼出来，但是他又想知道答案，所以，他想请你帮忙写一个程序来计算答案。  </div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<ol>
<li><span>第一行包含两个整数 N和M(0&lt;N&lt;9,0&lt;M&lt;2000)，分别代表纸片的数目和询问的数目。  </span></li>
<li><span>第二行包含N个整数分别代表纸片上写的数字，每个数字可能取0～9。  </span></li>
<li><span>接下来有M行询问，每个询问给出两个整数X和K(0&lt;=x&lt;10^9,0&lt;K&lt;100)。 </span></li>
</ol>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<ol class="dp-c" start="1">
<li><span>对于每次询问，如果能够用这些纸片拼出符合答案的T，就输出结果T。如果有多个结果，就输出符合要求的最小的T。&nbsp;&nbsp;</span></li>
<li class="alt"><span>如果不能拼出，就输出<span class="string">"None"</span><span>。 &nbsp;</span></span></li>
</ol>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 3 </span></p>
<p><span>1 2 3 4 </span></p>
<p><span>5 </span>7 </p>
<p><span>33 </span>6 </p>
<p>12 8  </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1234</p>
<p>None</p>
<p>1324</p>

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