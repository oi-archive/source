<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>其实这个“反病毒软件”（Anti-Virus SOFTware），是相关部门应对H9N7<span style="">人流感研发的。</span></p>
<p>相关部门的监控范围里只有<span style="font-family: 'Lucida Console';">N</span><span style="">个城市，从</span><span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">N</span><span style="">编号。初始时，这些城市都没有任何病例出现。由于在某一个城市出现过多的病例不太好，相关部门需要随时知道，从</span><span style="font-family: 'Lucida Console';">X</span><span style="">到</span><span style="font-family: 'Lucida Console';">Y</span><span style="">（含</span><span style="font-family: 'Lucida Console';">X</span><span style="">和</span><span style="font-family: 'Lucida Console';">Y</span><span style="">）这些城市当中，病例最多的城市与病例第二多的城市的病例数之差为多少。</span></p>
<p>一共会有<span style="font-family: 'Lucida Console';">Q</span><span style="">个事件发生，具体见【输入】。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数<span style="font-family: 'Lucida Console';">N</span><span style="">，</span><span style="font-family: 'Lucida Console';">Q</span><span style="">，以空格隔开。</span></p>
<p>接下来<span style="font-family: 'Lucida Console';">Q</span><span style="">行，每行代表一个事件。第</span><span style="font-family: 'Lucida Console';">i+1</span><span style="">行代表第</span><span style="font-family: 'Lucida Console';">i</span><span style="">个事件，这一行有三个整数</span><span style="font-family: 'Lucida Console';">C</span>i，<span style="font-family: 'Lucida Console';">X</span>i，<span style="font-family: 'Lucida Console';">Y</span>i，其中<span style="font-family: 'Lucida Console';">C</span>i为<span style="font-family: 'Lucida Console';">1</span><span style="">或</span><span style="font-family: 'Lucida Console';">2</span><span style="">。如果</span><span style="font-family: 'Lucida Console';">C</span>i为<span style="font-family: 'Lucida Console';">1</span><span style="">，表示在城市</span><span style="font-family: 'Lucida Console';">X</span>i又新发现了<span style="font-family: 'Lucida Console';">Y</span>i个病例；如果<span style="font-family: 'Lucida Console';">C</span>i为<span style="font-family: 'Lucida Console';">2</span><span style="">，表示询问从</span><span style="font-family: 'Lucida Console';">X</span>i到<span style="font-family: 'Lucida Console';">Y</span>i，病例最多的城市与病例第二多的城市的病例数之差为多少。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于输入中的每一个<span style="font-family: 'Lucida Console';">C</span>i=2<span style="font-family: 宋体;">的事件，输出一行，即询问的结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>2 1 4</p>
<p>1 2 3</p>
<p>2 2 4</p>
<p>1 3 2</p>
<p>2 1 3</p>
<p>1 2 2</p>
<p>2 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>
<p>3</p>
<p>1</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>初始时各个城市的病例数为<span style="font-family: 'Lucida Console';">{0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">。</span></p>
<p>从<span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">4</span><span style="">最多的病例数为</span><span style="font-family: 'Lucida Console';">0</span><span style="">，第二多的病例数为</span><span style="font-family: 'Lucida Console';">0</span><span style="">，差值为</span><span style="font-family: 'Lucida Console';">0</span><span style="">，输出</span><span style="font-family: 'Lucida Console';">0</span><span style="">。</span></p>
<p>城市<span style="font-family: 'Lucida Console';">2</span><span style="">发现了</span><span style="font-family: 'Lucida Console';">3</span><span style="">个新病例，病例数变为</span><span style="font-family: 'Lucida Console';">{0</span><span style="">，</span><span style="font-family: 'Lucida Console';">3</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">。</span></p>
<p>从<span style="font-family: 'Lucida Console';">2</span><span style="">到</span><span style="font-family: 'Lucida Console';">4</span><span style="">最多的病例数为</span><span style="font-family: 'Lucida Console';">3</span><span style="">，第二多的病例数为</span><span style="font-family: 'Lucida Console';">0</span><span style="">，差值为</span><span style="font-family: 'Lucida Console';">3</span><span style="">，输出</span><span style="font-family: 'Lucida Console';">3</span><span style="">。</span></p>
<p>城市<span style="font-family: 'Lucida Console';">3</span><span style="">发现了</span><span style="font-family: 'Lucida Console';">2</span><span style="">个新病例，病例数变为</span><span style="font-family: 'Lucida Console';">{0</span><span style="">，</span><span style="font-family: 'Lucida Console';">3</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">。</span></p>
<p>从<span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">3</span><span style="">最多的病例数为</span><span style="font-family: 'Lucida Console';">3</span><span style="">，第二多的病例数为</span><span style="font-family: 'Lucida Console';">2</span><span style="">，差值为</span><span style="font-family: 'Lucida Console';">1</span><span style="">，输出</span><span style="font-family: 'Lucida Console';">1</span><span style="">。</span></p>
<p>城市<span style="font-family: 'Lucida Console';">2</span><span style="">发现了</span><span style="font-family: 'Lucida Console';">2</span><span style="">个新病例，病例数变为</span><span style="font-family: 'Lucida Console';">{0</span><span style="">，</span><span style="font-family: 'Lucida Console';">5</span><span style="">，</span><span style="font-family: 'Lucida Console';">2</span><span style="">，</span><span style="font-family: 'Lucida Console';">0}</span><span style="">。</span></p>
<p>从<span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">4</span><span style="">最多的病例数为</span><span style="font-family: 'Lucida Console';">5</span><span style="">，第二多的病例数为</span><span style="font-family: 'Lucida Console';">2</span><span style="">，差值为</span><span style="font-family: 'Lucida Console';">3</span><span style="">，输出</span><span style="font-family: 'Lucida Console';">3</span><span style="">。</span></p>
<p> </p>
<p>【数据规模与约定】</p>
<p>对于40%<span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">，</span><span style="font-family: 'Lucida Console';">Q</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">。</span></p>
<p>对于<span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">2</span><span style="">≤</span><span style="font-family: 'Lucida Console';">N</span><span style="">，</span><span style="font-family: 'Lucida Console';">Q</span><span style="">≤</span><span style="font-family: 'Lucida Console';">100000</span><span style="">，且对于每一个</span><span style="font-family: 'Lucida Console';">C</span>i=2<span style="">，满足</span><span style="font-family: 'Lucida Console';">X</span>i＜<span style="font-family: 'Lucida Console';">Y</span>i。</p>
</div>
</div>