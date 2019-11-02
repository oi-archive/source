<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>原始部落用一种稀有的泥土烧制直径相同的圆瓷片并串成项链，串的时候沿瓷片的直径方向顺次连接，瓷片之间没有空隙也不重叠，一条项链至少由一个瓷片构成。 </p>
<p>每个烧制的瓷片厚度是一定的，直径D和所用泥土的体积V有以下关系：</p>
<p>D = 0.3（V - V<sub>0</sub>）(V ≥ V<sub>0</sub>)</p>
<p>D = 0                  (V &lt; V<sub>0)</sub></p>
<p>其中 V0为烧制每一片的损耗，单位与 V 相同。当用料小于等于 V0时，不能烧制成瓷<br>片。 <br>例： V <sub>总</sub> = 10，V<sub>0</sub> = 1，若烧制成一片瓷片，V = V <sub>总</sub>= 10，D = 0.9。如果把泥土均分成 2 份，每份泥土的体积为 V = V <sub>总</sub>/2 = 5，单个瓷片的直径为D' = 0.6 , 串起来的总长为 1.2。 给定了泥土的总体积和烧制单个瓷片的损耗，烧制的瓷片数不同，能够得到的项链总长度也不相同，请计算烧制多少个瓷片能使所得到的项链最长。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件仅有两行，每一行仅包含一个整数和一个换行/回车符。第一行的数字为泥土总体积 V 总 (0&lt;V 总&lt;60000)，第二行为烧制单个瓷片的损耗 V0(0&lt; V0&lt;600)。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件中仅包含一个数字和一个换行/回车符。该数字为能获得最长项链而烧制的瓷片数。 如果不能烧制成瓷片或者最优解不唯一（存在两个或者两个以上方案均能获得最长项链）， 输出数字 0。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：</p>
<p>10</p>
<p>1</p>
<p>样例输入2：</p>
<p>10</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1：</p>
<p>5</p>
<p>样例输出2：</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>