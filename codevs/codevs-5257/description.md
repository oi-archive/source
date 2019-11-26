<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><img src="/source/codevs/codevs-5257/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9ibG9iXzIwMTYwODE4MTY0MzU4Xzk5Ni5wbmc=.png" title=""></p><p style=""><span style=""><span style="">【题目背景】</span></span></p><p style=""><span style=""><span style="">花好月圆、繁星点点的静谧之夜，</span>yy和wyw在赏月。突然外星人ftm驾驶的飞碟飞来把yy吸了进去，ftm通过投影把自己和yy的影像投在地上，不怀好意的笑了笑：“yy已经被我绑架了，快来追我啊。”于是wyw就踏上了追逐飞碟的征程。</span></p><p style=""><span style=""><span style="">【题目描述】</span></span></p><p style=""><span style=""><span style="">与此同时，在飞碟上：</span></span></p><p style=""><span style="">yy：你想怎么样。</span></p><p style=""><span style="">ftm：把wyw折磨死然后看你痛苦的表情</span></p><p style=""><span style="">yy：。。。</span></p><p style=""><span style="">ftm：？？？</span></p><p style=""><span style=""><span style="">突然</span>yy把瘦小的ftm的手扳到背后然后把他按在地下不能动弹。</span></p><p style=""><span style="">yy一只手按着ftm，另一只手在飞船的操作屏上乱点。</span></p><p style=""><span style="">ftm：</span><span style="">2333没有用的，只有我才能够操纵飞船。我已经设置了程序，程序执行k次之后才会把你放掉。</span></p><p style=""><span style="">ftm设定的程序是这样的：每次当wyw追上飞船时，飞船就会启动传送装置，把wyw传送到另一个地点，再把飞船本身传到离那个地点最远的地点。</span></p><p style=""><span style="">yy很无奈，ftm也丝毫没有要妥协的意思，于是yy想知道wyw一共要跑多少路。</span></p><p style=""><span style=""><span style="">飞船所存储的地图是一张由</span>N个地点和N-1条道路组成的，这N-1条道路连通了N个地点，并且每条道路都有一定的长度。</span></p><p style=""><span style="">yy被绑架的地点用f</span><sub><span style="">0</span></sub><span style=""><span style="">来表示，</span>wyw从这里出发，wyw第i次被传送到的地点用f</span><sub><span style="">i</span></sub><span style=""><span style="">来表示，对于任意的</span>i≥2，有f</span><sub><span style="">i</span></sub><span style="">=[(f</span><sub><span style="">i-1</span></sub><span style="">*f</span><sub><span style="">i-2</span></sub><span style="">)mod N]+1（f</span><sub><span style="">0</span></sub><span style=""><span style="">和</span>f</span><sub><span style="">1</span></sub><span style=""><span style="">是给定的）</span></span></p><p style=""><span style=""><span style="">作为</span></span><span style="">OIER的你，一定想帮yy算出wyw一共要跑多少路对吧。由于答案可能会很大，直接输出对</span><span style="">1</span><span style="">,</span><span style="">000</span><span style="">,000,007取模的值</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">        第一行有四个整数N、k、f<sub>0</sub>、f<sub>1</sub></span></p><p style=""><span style="">        </span><span style="">接下来有N-1行，每行又三个整数u、v、w表示从地点u到地点v有一条长度为w的路</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:15px;font-family:&#39;微软雅黑&#39;,sans-serif">输出只有一个整数，表示路程总数对1,000,000,007取模的值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">4 2 2 4</span></p><p style=""><span style="">4 1 1</span></p><p style=""><span style="">1 2 3</span></p><p style=""><span style="">1 3 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">12</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""></span></p><p style=""><span style=""></span></p><p style=""><span style="">对于20%的数据，1≤N≤100，1≤k≤10,000</span></p><p style=""><span style="">对于60%的数据，1≤N≤3,000，1≤k≤1,000,000</span></p><p style=""><span style="">对于 100%的数据，1≤N≤1,000,000，1≤k≤10,000,000，1≤w≤1000，1≤f<sub>0</sub>,f<sub>1</sub>,u,v≤N</span></p><p style=""><span style="">注：测试数据是随机生成的</span></p>
</div>
</div>