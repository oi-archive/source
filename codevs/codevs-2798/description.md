<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>魔法阵是一个<span style="font-family: Times New Roman;">n</span>×m<span style="">的格子（高</span><span style="font-family: Times New Roman;">n</span><span style="">，宽</span><span style="font-family: Times New Roman;">m</span><span style="">），</span><span style="font-family: Times New Roman;">n</span>×m<span style="">为偶数。</span>Smart手中有<span style="font-family: Times New Roman;">n</span>×m<span style="">个宝石（以</span><span style="font-family: Times New Roman;">1~n</span>×m<span style="">编号）。</span>Smart从最右上角的格子开始走，从一个格子可以走到上、下、左、右<span style="font-family: Times New Roman;">4</span><span style="">个相邻的格子，但不能走出边界。每个格子必须且仅能到过</span><span style="font-family: Times New Roman;">1</span><span style="">次，这样</span>Smart一共走了<span style="font-family: Times New Roman;">n</span>×m<span style="">个格子停止（随便停哪里）。</span>Smart每进入一个格子，就在该格子里放入一颗宝石。他是按顺序放的，也就是说<span style="font-family: Times New Roman;">——</span><span style="">第</span><span style="font-family: Times New Roman;">i</span><span style="">个进入的格子放入</span><span style="font-family: Times New Roman;">i</span><span style="">号宝石。</span></p>
<p>如果两颗宝石的编号对<span style="font-family: Times New Roman;">n</span>×m÷2<span style="">取模的值相同，则认为这两颗宝石相互之间有微妙的影响。也就是说，我们按照宝石的编号对</span><span style="font-family: Times New Roman;">n</span>×m÷2<span style="">取模的值，将宝石分成</span><span style="font-family: Times New Roman;">n</span>×m÷2<span style="">对，其中每对都恰有两颗宝石。对于每一对宝石，设第一颗宝石在第</span><span style="font-family: Times New Roman;">a</span><span style="">行第</span><span style="font-family: Times New Roman;">b</span><span style="">列，另一颗宝石在第</span><span style="font-family: Times New Roman;">c</span><span style="">行第</span><span style="font-family: Times New Roman;">d</span><span style="">列，那么定义这</span><span style="font-family: Times New Roman;">2</span><span style="">个宝石的魔力影响值为 </span><span style="font-family: Times New Roman;">k</span>1×|a-c|+k2×|b-d|<span style="">。</span></p>
<p>需要你求出的是，在所有合乎题意的宝石摆放方案中，所有成对的宝石间的最大魔力影响值的最小值为多少。换句话说，如果我们定义对<span style="font-family: Times New Roman;">n</span>×m÷2<span style="">取模的值为</span><span style="font-family: Times New Roman;">i</span><span style="">的一对宝石的魔力影响值为</span><span style="font-family: Times New Roman;">a[i]</span><span style="">。你需要求出的就是</span><span style="font-family: Times New Roman;">max{a[i]|i=0,1,2...}</span><span style="">的最小值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>只有一行用空格隔开的<span style="font-family: Times New Roman;">4</span><span style="">个整数，分别是</span><span style="font-family: Times New Roman;">n</span><span style="">、</span><span style="font-family: Times New Roman;">m</span><span style="">、</span><span style="font-family: Times New Roman;">k</span>1、<span style="font-family: Times New Roman;">k</span>2。（<span style="font-family: Times New Roman;">n×m≤50</span><span style="">，</span><span style="font-family: Times New Roman;">0&lt;k</span>1,k2≤32767<span style="">）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">只需输出一个整数，即题目所要求的<span style="font-family: Times New Roman;">&ldquo;</span><span style="font-family: 宋体;">所有成对的宝石间的最大魔力影响值的最小值</span><span style="font-family: Times New Roman;">&rdquo;</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2 2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n×m≤50<span style="">，</span><span style="font-family: Times New Roman;">0&lt;k</span>1,k2≤32767</p>
</div>
</div>