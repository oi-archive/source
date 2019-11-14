<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">某人心情不好想跳楼，他想知道他从多少层楼跳下去所受伤害的的值和死亡的临界值为多少，已知他的生命值为</span><span style="">o</span><span style="">，跳的楼层数为</span><span style="">x</span><span style="">，第</span><span style="">n</span><span style="">层楼跳下去所受的伤害是</span></p><p style=""><strong><span style="text-decoration: underline;"><span style="font-family: 'Helvetica','sans-serif';">[(n-1)(n-2)......2*1]</span></span></strong><span style="">,</span><span style="">请你帮他算一算。（或许最好的办法是高精度。。。）</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入有两行：</span></p><p style=""><span style="">第一行一个数</span><span style="">o</span><span style="">，表示他的生命值，且</span><span style="">o&lt;10</span><span style="">的</span><span style="">255</span><span style="">次方</span><span style="">,</span></p><p style=""><span style="">第二行输入一个数</span><span style="">x</span><span style="">，表示他从多少层楼跳下去，</span><span style="">146&gt;x&gt;=50</span><span style="">，</span></p><p style=""><span style="">o,x</span><span style="">均为整数。（当然这是脱离现实的。。。）</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 10px;line-height: 20px;background: white"><span style=";font-family:宋体;color:#58666E">输出两行：</span></p><p style="margin-bottom: 10px;line-height: 20px;background: white"><span style=";font-family:宋体;color:#58666E">第一行表示该人跳楼后所受到的伤害值，</span></p><p style="margin-bottom: 10px;line-height: 20px;background: white"><span style=";font-family:宋体;color:#58666E">第二行表示该人距死亡还剩多少生命值，</span></p><p style="margin-bottom: 10px;line-height: 20px;background: white"><span style=";font-family:宋体;color:#58666E">若</span><span style=";font-family:&#39;Helvetica&#39;,&#39;sans-serif&#39;;color:#58666E">x</span><span style=";font-family:宋体;color:#58666E">项小于规定数据，则输出</span><span style=";font-family:&#39;Helvetica&#39;,&#39;sans-serif&#39;;color:#58666E">“error!&quot;</span><span style=";font-family:宋体;color:#58666E">，</span></p><p style="line-height: 20px;background: white"><span style=";font-family:宋体;color:#58666E">若数据均符合且计算后距死亡为</span><span style=";font-family:&#39;Helvetica&#39;,&#39;sans-serif&#39;;color:#58666E">0</span><span style=";font-family:宋体;color:#58666E">生命值或更少，则输出第一行的数后，再输出</span><span style=";font-family:&#39;Helvetica&#39;,&#39;sans-serif&#39;;color:#58666E">“died”</span><span style=";font-family:宋体;color:#58666E">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【</span><span style="">1</span><span style="">】</span></p><p style=""><span style="">3628809</span></p><p style=""><span style="">10</span></p><p style=""><span style="">【</span><span style="">2</span><span style="">】</span></p><p style=""><span style="">700000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000</span></p><p style=""><span style="font-family: Helvetica, sans-serif;">99</span></p><p style=""><span style="">【</span><span style="">3</span><span style="">】</span></p><p style=""><span style="">12345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901234</span></p><p style=""><span style="">101</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【</span><span style="">1</span><span style="">】</span></p><p style=""><span style="">error!</span></p><p style=""><span style="">【</span><span style="">2</span><span style="">】</span></p><p style=""><span style="">The first data:933262154439441526816992388562667004907159682643816214685929638952175999932299156089414639761565182862536979208272237582511852109168640000000000000000000000</span></p><p style=""><span style="">The second data:699999999999999999999999999999999999999999999066737845560558473183007611437332995092840317356183785314070361047824000067700843910585360238434817137463020791727762417488147890831360000000000000000000000</span></p><p style=""><span style="">【</span><span style="">3</span><span style="">】</span></p><p style=""><span style="">The first data:9425947759838359420851623124482936749562312794702543768327889353416977599316221476503087861591808346911623490003549599583369706302603264000000000000000000000000</span></p><p style=""><span style="">The second data:12345678901234567890123456789012345678901234567890123456789012345678901234567890123456789012336252953474729530702605165887862742151672255095420913020684456325484256968573901980285924484087092887656266633453239412762309194931964626123456789012345678901234</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">o&lt;10</span><span style="">的</span><span style="">255</span><span style="">次方</span><span style="">;</span></p><p style=""><span style="">146&gt;x&gt;=50.</span></p><p><br></p>
</div>
</div>