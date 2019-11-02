<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">某数学老师自称为解析几何高手，曾做过几十万道解析几何题，认为解析几何这一块，自己没有一道题不会做。但是有一天，魔法炮同学问了他一道仅仅关于二维坐标系中点的问题，居然真的把他给难住了！这道题是这样的：</span></p><p style=""><span style="">坐标系中有</span><span style="">n</span><span style="">个点，第</span><span style="">i</span><span style="">个点的坐标为</span><span style="">(xi,yi)</span><span style="">，现在要对这</span><span style="">n</span><span style="">个点同时进行</span><span style="">m</span><span style="">个操作，操作有如下几种（</span><span style="">p</span><span style="">和</span><span style="">q</span><span style="">为两个实数）：</span></p><p style=""><span style="">①<span style="font-family: 'Times New Roman';">    </span></span><span style="">M p q</span><span style="">：沿</span><span style="">x</span><span style="">轴向右平移</span><span style="">p</span><span style="">个单位，沿</span><span style="">y</span><span style="">轴向上平移</span><span style="">q</span><span style="">个单位。</span><span style="">(-10&lt;=p&lt;=10)</span></p><p style=""><span style="">②<span style="font-family: 'Times New Roman';">    </span></span><span style="">Z p</span><span style="">：横纵坐标同时扩大</span><span style="">p</span><span style="">倍。</span><span style="">(0&lt;=p&lt;=10)</span></p><p style=""><span style="">③<span style="font-family: 'Times New Roman';">    </span></span><span style="">O</span><span style="">：沿</span><span style="">x</span><span style="">轴上下翻转。</span></p><p style=""><span style="">④<span style="font-family: 'Times New Roman';">    </span></span><span style="">T</span><span style="">：沿</span><span style="">y</span><span style="">轴左右翻转。</span></p><p style=""><span style="">⑤<span style="font-family: 'Times New Roman';">    </span></span><span style="">S</span><span style="">：关于原点做对称变换。</span></p><p style=""><span style="">⑥<span style="font-family: 'Times New Roman';">    </span></span><span style="">R p</span><span style="">：绕原点逆时针旋转</span><span style="">p</span><span style="">°（</span><span style="">0</span><span style="">≤</span><span style="">p&lt;360</span><span style="">）。</span></p><p style=""><span style="">注：</span><span style="">(x,y)</span><span style="">旋转角度α后变为</span><span style="">(xcos</span><span style="">α</span><span style="">-ysin</span><span style="">α</span><span style="">,xsin</span><span style="">α</span><span style="">+ycos</span><span style="">α</span><span style="">)</span><span style="">。</span></p><p><span style="">       </span><span style="">现在要求出所有操作后，每个点的坐标！聪明的同学，你能帮老师解决难题吗？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行两个整数</span><span style="">n,m</span><span style="">。</span></p><p><span style="">接下来</span><span style="">n</span><span style="">行每行两个实数</span><span style="">xi,yi</span><span style="">，代表第</span><span style="">i</span><span style="">个点的坐标。</span></p><p><span style="">接下来</span><span style="">m</span><span style="">行每行一个操作，以大写字母开头。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:16px;font-family:宋体">共</span><span style="font-size:16px;font-family:&#39;Times New Roman&#39;">n</span><span style="font-size:16px;font-family: 宋体">行，每行两个整数</span><span style="font-size:16px;font-family:&#39;Times New Roman&#39;">xi,yi</span><span style="font-size:16px;font-family: 宋体">，代表所有变换后第</span><span style="font-size:16px;font-family:&#39;Times New Roman&#39;">i</span><span style="font-size:16px;font-family: 宋体">个点的坐标（保留两位小数）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 4</span></p><p><span style="">1 2</span></p><p><span style="">-2 2.5</span></p><p><span style="">0 -3</span></p><p><span style="">Z 2</span></p><p><span style="">O</span></p><p><span style="">M 3 6</span></p><p><span style="">R 90</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">-2.00 5.00</span></p><p><span style="">-1.00 -1.00</span></p><p><span style="">-12.00 3.00</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">1&lt;=n&lt;=10<sup>5</sup></span></p><p style=""><span style="">1&lt;=m&lt;=10<sup>4</sup></span></p><p style=""><span style="">-10<sup>5</sup>&lt;=xi,yi&lt;=10<sup>5</sup></span></p><p style=""><span style="">输入保证</span><span style="">Z</span><span style="">操作不会超过</span><span style="">100</span><span style="">次。</span></p><p style=""><span style="">注意：对于样例中出现的负零的情况，直接输出即可，不必去掉负号。</span></p><p style=""><span style=""></span><br></p><p><br></p>
</div>
</div>