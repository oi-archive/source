<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> </p>
<p>故事背景：</p>
<p>      传说中珠穆朗玛峰下有座古代人修建的神庙，神庙的地下室里有古代王室的遗产，但</p>
<p>  数千年来从未有人到达过……探险者小<span style="font-family: 'Times New Roman';">FF</span><span style="">一直梦想成为世界上最富有的人和最杰出的探险家并被永载史册。在证明了这个洞确实存在后，小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">做好了充足准备，来到了神庙。</span></p>
<p> </p>
<p>试题一：符文之语</p>
<p> </p>
<p> <span style="">【题目描述】</span></p>
<p> </p>
<p>      当小<span style="font-family: 'Times New Roman';">FF</span><span style="">来到神庙时，神庙已经破败不堪了。但神庙的中央有一个光亮如新的石台。小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">走近石台，发现石台上有一个数串，而数串的上方刻着一串古老的符文之语。精通古符文之语的小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">不费吹灰之力就读懂了文章的意思，其大意是：对于石台上的一串数字，你可以在适当的位置加入乘号（设加了</span><span style="font-family: 'Times New Roman';">k</span><span style="">个，当然也可不加，即分成</span><span style="font-family: 'Times New Roman';">k</span><span style="">＋</span><span style="font-family: 'Times New Roman';">1</span><span style="">个部分），设这</span><span style="font-family: 'Times New Roman';">k</span><span style="">＋</span><span style="font-family: 'Times New Roman';">1</span><span style="">个部分的乘积（如果</span><span style="font-family: 'Times New Roman';">k=0</span><span style="">，则乘积即为原数串的值）对</span><span style="font-family: 'Times New Roman';">m</span><span style="">的余数（即</span><span style="font-family: 'Times New Roman';">mod m)</span><span style="">为</span><span style="font-family: 'Times New Roman';">x</span><span style="">；现求</span><span style="font-family: 'Times New Roman';">x</span><span style="">能达到的最小值及该情况下</span><span style="font-family: 'Times New Roman';">k</span><span style="">的最小值，以及</span><span style="font-family: 'Times New Roman';">x</span><span style="">能达到的最大值及该情况下的</span><span style="font-family: 'Times New Roman';">k</span><span style="">的最小值（可以存在</span><span style="font-family: 'Times New Roman';">x</span><span style="">的最小值与最大值相同的情况）。小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">还知道，如果他找到了正确的答案，那么就可以通往神庙的下层了。但这个问题似乎不太好解决，小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">就找到了你，并答应找到财宝以后和你二八分（当然你拿二……）。</span></p>
<p><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为数串，且数串中不存在<span style="font-family: 'Times New Roman';">0;</span></p>
<p>第二行为<span style="font-family: 'Times New Roman';">m</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">四个数，分别为<span style="font-family: 'Times New Roman';">x</span><span style="font-family: 宋体;">的最小值和该情况下的</span><span style="font-family: 'Times New Roman';">k</span><span style="font-family: 宋体;">，以及</span><span style="font-family: 'Times New Roman';">x</span><span style="font-family: 宋体;">的最大值和该情况下的</span><span style="font-family: 'Times New Roman';">k</span><span style="font-family: 宋体;">，相邻两个数之间用一个空格隔开。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>44211 </p>
<p>22</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0 1 21 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p>
<p>对于<span style="font-family: 'Times New Roman';">30</span><span style="">％的数据</span><span style="font-family: 'Times New Roman';">:2</span><span style="">≤字符串长度</span><span style="font-family: 'Times New Roman';">L</span><span style="">≤</span><span style="font-family: 'Times New Roman';">50</span><span style="">。对于</span><span style="font-family: 'Times New Roman';">100%</span><span style="">的数据：</span><span style="font-family: 'Times New Roman';">2</span><span style="">≤字符串长度</span><span style="font-family: 'Times New Roman';">L</span><span style="">≤</span><span style="font-family: 'Times New Roman';">1000; 2</span><span style="">≤</span><span style="font-family: 'Times New Roman';">m</span><span style="">≤</span><span style="font-family: 'Times New Roman';">50</span><span style="">。</span></p>
</div>
</div>