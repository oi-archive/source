<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">笨笨有一条神奇的项链，为什么说它神奇呢？因为它有两个性质：</span></p><p style=""><span style="font-family: 'Courier New';">1.  </span><span style="">神奇的项链可以拉成一条线，线上依次是</span><span style="font-family: 'Courier New';">N</span><span style="">个珠子，每个珠子有一个能量值</span><span style="font-family: 'Courier New';">E<sub>i</sub></span><span style="">；</span></p><p style=""><span style="font-family: 'Courier New';">2.  </span><span style="">除了第一个和最后一个珠子，其他珠子都满足</span><span style="font-family: 'Courier New';">E<sub>i</sub>=(E<sub>i-1</sub>+E<sub>i+1</sub>)/2+D<sub>i</sub></span><span style="">。</span></p><p style=""><span style="">由于这条项链很长，我们只能知道其两端珠子的能量值。并且我们知道每个珠子的</span><span style="font-family: 'Courier New';">D<sub>i</sub></span><span style="">是多少。请聪明的你求出这</span><span style="font-family: 'Courier New';">N</span><span style="">个珠子的能量值分别是多少。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行三个整数</span><span style="font-family: 'Courier New';">N</span><span style="">、</span><span style="font-family: 'Courier New';">E<sub>1</sub></span><span style="">、</span><span style="font-family: 'Courier New';">E<sub>N</sub></span><span style="">，表示珠子个数</span><span style="font-family: 'Courier New';">N</span><span style="">，第一个珠子和第</span><span style="font-family: 'Courier New';">N</span><span style="">个珠子的能量值。</span></p><p style=""><span style="">第二行</span><span style="font-family: 'Courier New';">N-2</span><span style="">个整数，表示第</span><span style="font-family: 'Courier New';">2</span><span style="">个珠子到第</span><span style="font-family: 'Courier New';">N-1</span><span style="">个珠子的</span><span style="font-family: 'Courier New';">D<sub>i</sub></span><span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-left:28px"><span style="font-family:宋体">输出仅一行，</span><span style="font-family:&#39;Courier New&#39;">N</span><span style="font-family: 宋体">个整数，表示</span><span style="font-family:&#39;Courier New&#39;">1</span><span style="font-family:宋体">到</span><span style="font-family: &#39;Courier New&#39;">N</span><span style="font-family:宋体">个这</span><span style="font-family:&#39;Courier New&#39;">N</span><span style="font-family: 宋体">个珠子各自的能量值</span><span style="font-family:&#39;Courier New&#39;">E<sub>i</sub></span><span style="font-family: 宋体">。每</span><span style="font-family: &#39;Courier New&#39;">2</span><span style="font-family:宋体">个整数之间用</span><span style="font-family:&#39;Courier New&#39;">1</span><span style="font-family: 宋体">个空格隔开；请放心，数据保证对于任意珠子满足</span><span style="font-family:&#39;Courier New&#39;">(E<sub>i-1</sub>+E<sub>i+1</sub>)Mod 2=0</span><span style="font-family:宋体">；</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><strong><span style="">【样例输入</span>1</strong><strong><span style="">】</span></strong></p><p style=""><span style="font-family: 'Courier New';">4 1 4</span></p><p style=""><span style="font-family: 'Courier New';">0 0</span></p><p style=""><strong><span style="">【样例输入</span>2</strong><strong><span style="">】</span></strong></p><p style=""><span style="font-family: 'Courier New';">10 1 29</span></p><p style=""><span style="font-family: 'Courier New';">0 2 -3 5 1 4 2 -1</span></p><p style=""><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【样例输出</span>1</strong><strong><span style="">】</span></strong></p><p><span style="font-family: 'Courier New';">1 2 3 4</span></p><p><strong><span style="">【样例输出</span>2</strong><strong><span style="">】</span></strong></p><p><span style="font-family: 'Courier New';">1 13 25 33 47 51 53 47 37 29</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【数据规模】</span></strong></p><p style=""><span style="">对于</span><span style="font-family: 'Courier New';">40%</span><span style="">的数据</span><span style="font-family: 'Courier New';">: 1&lt;N</span><span style="">≤</span><span style="font-family: 'Courier New';">100</span><span style="">；</span></p><p style=""><span style="">对于</span><span style="font-family: 'Courier New';">70%</span><span style="">的数据</span><span style="font-family: 'Courier New';">: 1&lt;N</span><span style="">≤</span><span style="font-family: 'Courier New';">5</span><span style="font-family: 'Cambria Math';">,</span><span style="font-family: 'Courier New';">000</span><span style="">，所有数据（包括计算中的）不超过</span><span style="font-family: 'Courier New';">10<sup>9</sup></span><span style="">；</span></p><p style=""><span style="">对于</span><span style="font-family: 'Courier New';">100%</span><span style="">的数据</span><span style="font-family: 'Courier New';">: 1&lt;N</span><span style="">≤</span><span style="font-family: 'Courier New';">500</span><span style="font-family: 'Cambria Math';">,</span><span style="font-family: 'Courier New';">000</span><span style="">；</span><span style="font-family: 'Courier New';"> |E<sub>1</sub>|</span><span style="">、</span><span style="font-family: 'Courier New';">|E<sub>N</sub>|</span><span style="">≤</span><span style="font-family: 'Courier New';">10<sup>15</sup></span><span style="">；</span><span style="font-family: 'Courier New';">|D<sub>i</sub>|</span><span style="">≤</span><span style="font-family: 'Courier New';">10<sup>4</sup></span><span style="">；</span></p><p>//其实这道题吧是一道很水的入门题目= = 就是给你们刷自豪感的呢</p><p>//读优会出错= =所以只能scanf注意用lld</p>
</div>
</div>