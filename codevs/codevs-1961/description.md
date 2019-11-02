<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你早上起来，慢悠悠地来到学校门口，发现已经是八点整了！（这句话里有一个比较重要的条件）</p>
<p>学校共有<span style="font-family: 'Lucida Console';">N</span><span style="">个地点，编号为</span><span style="font-family: 'Lucida Console';">1~N</span><span style="">，其中</span><span style="font-family: 'Lucida Console';">1</span><span style="">号为学校门口（也就是你现在所处的位置），</span><span style="font-family: 'Lucida Console';">2</span><span style="">号为你的教室（也就是你的目的地）。这些地点之间有</span><span style="font-family: 'Lucida Console';">M</span><span style="">条双向道路，对于第</span><span style="font-family: 'Lucida Console';">i</span><span style="">条道路，为了不引起值周队老师的怀疑，你通过它的时间须恰好为</span><span style="font-family: 'Lucida Console';">T</span>i秒。这个数可能为负数，意义为时间倒流。</p>
<p>不过，即使没有引起怀疑，值周队也布下了最后一道防线：大龙会在教室处不定期出现。当然，你也了解大龙的习性：当前时间的秒数越小，大龙出现的概率就越低，例如：<span style="font-family: 'Lucida Console';">8:13:06</span><span style="">这一时刻的秒数是</span><span style="font-family: 'Lucida Console';">06</span><span style="">，就要比</span><span style="font-family: 'Lucida Console';">8:12:57</span><span style="">这个时刻更加安全。</span></p>
<p>现在的问题是，在不引起怀疑的前提下，最安全的到达时刻的秒数是多少。如果学校门口到教室没有路<span style="font-family: 'Lucida Console';">(-_-||)</span><span style="">，请输出</span><span style="font-family: 'Lucida Console';">60</span><span style="">。</span></p>
<p>注意，你可以选择在途中的任何时候经过教室，而不结束“旅程”，具体见样例。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数，<span style="font-family: 'Lucida Console';">N</span><span style="">和</span><span><span style="font-family: 'Lucida Console';">M</span></span><span style="">，意义在上面已经说过了。</span></p>
<p>第<span style="font-family: 'Lucida Console';">2</span><span style="">行</span><span style="font-family: 'Lucida Console';">~</span><span style="">第</span><span style="font-family: 'Lucida Console';">M+1</span><span style="">行，每行代表一条道路。第</span><span style="font-family: 'Lucida Console';">i+1</span><span style="">行代表第</span><span style="font-family: 'Lucida Console';">i</span><span style="">条道路，这一行有</span><span style="font-family: 'Lucida Console';">3</span><span style="">个整数，</span><span style="font-family: 'Lucida Console';">A</span>i，<span style="font-family: 'Lucida Console';">B</span>i，<span style="font-family: 'Lucida Console';">T</span>i，表示<span style="font-family: 'Lucida Console';">A</span>i号地点与<span style="font-family: 'Lucida Console';">B</span>i号地点有一条双向道路，通过它的时间必须为<span style="font-family: 'Lucida Console';">T</span>i秒。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">只有一行，为最安全的到达时刻的秒数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Input1:</p>
<p>2 1</p>
<p>2 1 54</p>
<p>Input2:</p>
<p>3 3</p>
<p>1 2 26</p>
<p>1 3 17</p>
<p>2 3 -9</p>
<p>Input3:</p>
<p>3 1</p>
<p>1 3 110</p>
<p>Input4:</p>
<p>2 2</p>
<p>1 2 7</p>
<p>2 1 9</p>
<p>Input5:</p>
<p>2 2</p>
<p>1 2 3</p>
<p>1 1 1</p>
<p>Input6:</p>
<p>2 2</p>
<p>1 2 9</p>
<p>1 2 11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Output1:</p>
<p>06</p>
<p>Output2:</p>
<p>00</p>
<p>Output3:</p>
<p>60</p>
<p>Output4:</p>
<p>01</p>
<p>Output5:</p>
<p>00</p>
<p>Output6:</p>
<p>01</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例1的说明：<span style="">一共只有两个地点（多么福利的数据啊），也只有一条道路，耗时为</span><span style="font-family: 'Lucida Console';">54</span><span style="">秒。最优方案为，经过这个道路</span><span style="font-family: 'Lucida Console';">9</span><span style="">次，耗时</span><span style="font-family: 'Lucida Console';">486</span><span style="">秒，即</span><span style="font-family: 'Lucida Console';">8</span><span style="">分</span><span style="font-family: 'Lucida Console';">06</span><span style="">秒，于</span><span style="font-family: 'Lucida Console';">8:08:06</span><span style="">到达教室。当然，最优方案不唯一。</span></p>
<p>样例2的说明：<span style="">走</span><span style="font-family: 'Lucida Console';">1-&gt;3-&gt;1-&gt;2</span><span style="">，用时</span><span style="font-family: 'Lucida Console';">17+17+26</span><span style="">，于</span><span style="font-family: 'Lucida Console';">8:01:00</span><span style="">到达；或走</span><span style="font-family: 'Lucida Console';">1-&gt;2-&gt;3-&gt;1-&gt;2</span><span style="">，用时</span><span style="font-family: 'Lucida Console';">26-9+17+26</span><span style="">，于</span><span style="font-family: 'Lucida Console';">8:01:00</span><span style="">到达。</span></p>
<p> </p>
<p>对于<span style="font-family: 'Lucida Console';">20%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">2</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">40%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">100</span><span style="">；对于</span><span style="font-family: 'Lucida Console';">70%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">；</span></p>
<p> </p>
<p>对于<span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">2</span><span style="">≤</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">7000</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">≤</span><span style="font-family: 'Lucida Console';">M</span><span style="">≤</span><span style="font-family: 'Lucida Console';">9000</span><span style="">，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">A</span>i,Bi≤<span style="font-family: 'Lucida Console';">N</span><span style="">，</span><span style="font-family: 'Lucida Console';">|T</span>i|<span style="">≤</span><span style="font-family: 'Lucida Console';">10</span>9。</p>
<p><span style=""><br></span></p>
</div>
</div>