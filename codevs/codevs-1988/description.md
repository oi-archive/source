<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>数列<span style="font-family: 'Lucida Console';">a</span><span style="">可由以下递推式得到：</span><span style="font-family: 'Lucida Console';">a</span>1=1<span style="">，</span><span style="font-family: 'Lucida Console';">a</span>i=ai-1+D<span style="">，其中</span><span style="font-family: 'Lucida Console';">i</span><span style="">＞</span><span style="font-family: 'Lucida Console';">1</span><span style="">，</span><span style="font-family: 'Lucida Console';">D</span><span style="">为给定的正整数常数。</span></p>
<p>数列<span style="font-family: 'Lucida Console';">b</span><span style="">可由下式得到：</span><span style="font-family: 'Lucida Console';">b</span>i=ai÷<span style="font-family: 'Lucida Console';">a</span>i+1，其中<span style="font-family: 'Lucida Console';">i</span><span style="">为正整数。</span></p>
<p>现在有<span style="font-family: 'Lucida Console';">Q</span><span style="">次询问，第</span><span style="font-family: 'Lucida Console';">i</span><span style="">次询问要求知道数列</span><span style="font-family: 'Lucida Console';">b</span><span style="">的第</span><span style="font-family: 'Lucida Console';">L</span>i项和与<span style="font-family: 'Lucida Console';">R</span>i项之间（含）的和<span style="font-family: 'Lucida Console';">S</span>i，用假分数的形式表示。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含<span style="font-family: 'Lucida Console';">2</span><span style="">个整数</span><span style="font-family: 'Lucida Console';">D</span><span style="">，</span><span style="font-family: 'Lucida Console';">Q</span><span style="">。</span></p>
<p>接下来的<span style="font-family: 'Lucida Console';">Q</span><span style="">行，每行包含</span><span style="font-family: 'Lucida Console';">2</span><span style="">个整数</span><span style="font-family: 'Lucida Console';">L</span>i和<span style="font-family: 'Lucida Console';">R</span>i。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件共有<span style="font-family: 'Lucida Console';">Q</span><span style="font-family: 宋体;">行，第</span><span style="font-family: 'Lucida Console';">i</span><span style="font-family: 宋体;">行包含</span><span style="font-family: 'Lucida Console';">2</span><span style="font-family: 宋体;">个整数，代表第</span><span style="font-family: 'Lucida Console';">i</span><span style="font-family: 宋体;">次询问得到的结果，其中假分数的分子在前，分母在后。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>1 7</p>
<p>2 16</p>
<p>4 12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>223261 45045</p>
<p>58076397835081 4512611027925</p>
<p>13090546283 1673196525</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>说明： a={1,3,5,7,<span style="">…</span><span style="font-family: 'Lucida Console';">}</span><span style="">，</span><span style="font-family: 'Lucida Console';">b={1/3+3/5+5/7+</span><span style="">…</span><span style="font-family: 'Lucida Console';">}</span><span style="">。</span></p>
<p><span style="">对于第一次询问，需要求的是</span> 1/3+3/5+5/7+<span style="">…</span><span style="font-family: 'Lucida Console';">+13/15=</span>223261/45045<span style="">，其余同理。</span></p>
<p> </p>
<div>
<p>【数据说明】</p>
<p>对于任意的<span style="font-family: 'Lucida Console';">R</span>i，<span style="font-family: 'Lucida Console';">b</span>1+b2+<span style="">…</span><span style="font-family: 'Lucida Console';">+b</span>r的分子与分母具有以下性质：对于<span style="font-family: 'Lucida Console';">10%</span><span style="">的数据，均≤</span><span style="font-family: 'Lucida Console';">10000</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">30%</span><span style="">的数据，均≤</span><span style="font-family: 'Lucida Console';">1</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>9；对于<span style="font-family: 'Lucida Console';">60%</span><span style="">的数据，均≤</span><span style="font-family: 'Lucida Console';">1</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>14；对于<span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，均≤</span><span style="font-family: 'Lucida Console';">1</span><span style="">×</span><span style="font-family: 'Lucida Console';">10^</span>19。</p>
<p>对于<span style="font-family: 'Lucida Console';">10%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">Q=1</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">30%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">Q</span><span style="">≤</span><span style="font-family: 'Lucida Console';">100</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">60%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">Q</span><span style="">≤</span><span style="font-family: 'Lucida Console';">10000；</span><span style="">对于</span><span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">Q</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000000</span><span style="">。</span></p>
</div>
<p><span style=""><br></span></p>
</div>
</div>