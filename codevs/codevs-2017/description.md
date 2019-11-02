<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这是一种奇葩的音乐游戏（Yin Yue GAME）。</p>
<p>初始时，你的序列为“1234567”（7<span style="">个音符</span>）。每秒钟，你可以将其中两个相邻元素交换。</p>
<p>每秒钟，系统也会给你一个音符。在你交换完毕之后，系统会比对你的序列的首位与该音符是否相同。如果相同，你得到<span style="font-family: 'Lucida Console';">1</span><span style="">分。</span></p>
<p>求你的最大得分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个正整数<span style="font-family: 'Lucida Console';">T</span><span style="">，代表游戏的总时间。</span></p>
<p>第二行为一个长度为<span style="font-family: 'Lucida Console';">T</span><span style="">的序列，其中只包含</span><span style="font-family: 'Lucida Console';">1</span><span style="">到</span><span style="font-family: 'Lucida Console';">7</span><span style="">的数字。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共一行，为一个整数，即最大得分。</p>

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
<p>1273</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
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
<p>初始时，序列为<span style="font-family: 'Lucida Console';">1234567</span><span style="">。</span></p>
<p>第<span style="font-family: 'Lucida Console';">1</span><span style="">秒钟，不进行交换。序列首位为</span><span style="font-family: 'Lucida Console';">1</span><span style="">，与这一秒的音符</span><span style="font-family: 'Lucida Console';">1</span><span style="">相同，得</span><span style="font-family: 'Lucida Console';">1</span><span style="">分。</span></p>
<p>第<span style="font-family: 'Lucida Console';">2</span><span style="">秒钟，将</span><span style="font-family: 'Lucida Console';">1</span><span style="">与</span><span style="font-family: 'Lucida Console';">2</span><span style="">交换，序列变为</span><span style="font-family: 'Lucida Console';">2134567</span><span style="">。首位与给定音符</span><span style="font-family: 'Lucida Console';">2</span><span style="">相同，得</span><span style="font-family: 'Lucida Console';">1</span><span style="">分。</span></p>
<p>第<span style="font-family: 'Lucida Console';">3</span><span style="">秒钟，将</span><span style="font-family: 'Lucida Console';">1</span><span style="">与</span><span style="font-family: 'Lucida Console';">3</span><span style="">交换，序列变为</span><span style="font-family: 'Lucida Console';">2314567</span><span style="">。首位与给定音符</span><span style="font-family: 'Lucida Console';">7</span><span style="">不同。</span></p>
<p>第<span style="font-family: 'Lucida Console';">4</span><span style="">秒钟，将</span><span style="font-family: 'Lucida Console';">2</span><span style="">与</span><span style="font-family: 'Lucida Console';">3</span><span style="">交换，序列变为</span><span style="font-family: 'Lucida Console';">3214567</span><span style="">。首位与给定音符</span><span style="font-family: 'Lucida Console';">3</span><span style="">相同，得</span><span style="font-family: 'Lucida Console';">1</span><span style="">分。</span></p>
<p>总得分<span style="font-family: 'Lucida Console';">3</span><span style="">分。可以证明，没有得分更高的方案。</span></p>
<p> </p>
<p>【数据规模与约定】</p>
<p>对于20%<span style="">的数据，</span><span style="font-family: 'Lucida Console';">T</span><span style="">≤</span><span style="font-family: 'Lucida Console';">2</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">60%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">T</span><span style="">≤</span><span style="font-family: 'Lucida Console';">20</span><span style="">；</span>对于100%<span style="">的数据，</span><span style="font-family: 'Lucida Console';">T</span><span style="">≤</span><span style="font-family: 'Lucida Console';">200</span><span style="">。</span></p>
</div>
</div>