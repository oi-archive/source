<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>试题二：最接近神的人</p>
<p> </p>
<p>【题目描述】</p>
<p>破解了符文之语，小<span style="font-family: 'Times New Roman';">FF</span><span style="">开启了通往地下的道路。当他走到最底层时，发现正前方有一</span></p>
<p>扇巨石门，门上雕刻着一幅古代人进行某种活动的图案。而石门上方用古代文写着“神的殿堂”。小<span style="font-family: 'Times New Roman';">FF</span><span style="">猜想里面应该就有王室的遗产了。但现在的问题是如何打开这扇门……仔细研究后，他发现门上的图案大概是说：古代人认为只有智者才是最容易接近神明的。而最聪明的人往往通过一种仪式选拔出来。仪式大概是指，即将隐退的智者为他的候选人写下一串无序的数字，并让他们进行一种操作，即交换序列中相邻的两个元素。而用最少的交换次数使原序列变成不下降序列的人即是下一任智者。小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">发现门上同样有着</span><span style="font-family: 'Times New Roman';">n</span><span style="">个数字。于是他认为打开这扇门的秘诀就是找到让这个序列变成不下降序列所需要的最小次数。但小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">不会……只好又找到了你，并答应事成之后与你三七分……</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个整数<span style="font-family: 'Times New Roman';">n,</span><span style="">表示序列长度</span></p>
<p>第二行为<span style="font-family: 'Times New Roman';">n</span><span style="">个整数，表示序列中每个元素。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数<span style="font-family: 'Times New Roman';">ans</span><span style="font-family: 宋体;">，即最少操作次数。</span></p>

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
<p>2 8 0 3</p>

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
<p>样例说明：开始序列为<span style="font-family: 'Times New Roman';">2 8 0 3</span><span style="">，目标序列为</span><span style="font-family: 'Times New Roman';">0 2 3 8</span><span style="">，可进行三次操作的目标序列：</span></p>
<p>1 .Swap (8<span style="">，</span><span style="font-family: 'Times New Roman';">0)</span><span style="">：</span><span style="font-family: 'Times New Roman';">2 0 8 3</span></p>
<p>2. Swap (2<span style="">，</span><span style="font-family: 'Times New Roman';">0)</span><span style="">：</span><span style="font-family: 'Times New Roman';">0 2 8 3</span></p>
<p>3. Swap (8, 3)<span style="">：</span><span style="font-family: 'Times New Roman';">0 2 3 8</span></p>
<p>【数据范围】</p>
<p>    对于<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据</span><span style="font-family: 'Times New Roman';">1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">10</span>4</p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据</span><span style="font-family: 'Times New Roman';">1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">5*10</span>5;</p>
<p>-maxlongint<span style="">≤</span><span style="font-family: 'Times New Roman';">A</span><span style="">［</span><span style="font-family: 'Times New Roman';">i</span><span style="">］≤</span><span style="font-family: 'Times New Roman';">maxlongint</span><span style="">。</span></p>
</div>
</div>