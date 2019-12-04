<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>王先生是一位收藏家，他收集了非常多有名的雕像。某天，为了美观，他想要将收藏台上的雕像按照某种方式重新摆放，由于雕像都有一定的重量，所以他决定雇用一位年轻人，小明，來帮忙搬雕像。 <br> 王先生收藏的雕像目前是以随机的方式放在收藏台上，收藏台的位置由左至右成一列排开，编号依序为1, 2,..., n ，每个收藏台上放置一个雕像，而收藏台i (1 ≤ i ≤ n) 上目前放的雕像编号为 Si，其高度为 hi 公分，重量为 wi 公斤。王先生要求小明依照下列方式去重新摆放雕像: <br> (a) 搬动过程中，一次只能搬一个雕像，而每个收藏台可暂时放置 0个、1 个、或多个雕像。 <br> (b) 完成重新摆放之后需符合下列条件： </p>
<ul style="">
<li>每个收藏台上放置一个雕像。 </li>
<li>雕像必须根据高度，由低至高从最左边的收藏台开始依序放置。 </li>
<li>若任二雕像的高度相同时，则重量轻的雕像放置在左边。 </li>
<li>若任二雕像高度和重量都相同时，则依照原先雕像的左右相对顺序來放置，也就是說原先在左边的雕像必须放置在左边。 </li>
</ul>
<p>为了节省搬运的距離，小明希望你替他写出一个程序，根据上述方式将雕像重新摆放在收藏台上且搬动的总距離为最短。本题假设任二相邻收藏台的距離为1 公尺。 <br> 以下为一个范例，假设有 5 个收藏台，雕像 Si (1 ≤ i ≤ 5) 的高度和重量以(hi, wi)表示，并依序为(5,20) ，(10,25) ，(78,40) ，(25,25) ，(5,15) 。一种搬动方式如图(a)所示，搬动的总距離为 12公尺，而另一种搬动方式如图(b)所示，搬动的总距離为8 公尺，是所有符合搬动方式中的最短距離。</p>

<img src="/source/codevs/codevs-2221/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzIyMjEucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有一个整數n，1≤ n≤ 10000，代表收藏台的个數。接下來的n 行，每行有兩个整數以空白隔开，其中第 i 行(1 ≤i ≤ n) 为目前放在收藏台i 上雕像Si 的高度hi( 单位为公分) 和重量wi( 单位为公斤) ，hi 和wi 都介于1 和65536 之间</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整數，代表搬动雕像所需的最短总距離( 单位为公尺) 。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>5</p>
<p>5 20</p>
<p>10 25</p>
<p>78 40</p>
<p>25 25</p>
<p>5 15</p>
<p> </p>
<p>样例2：</p>
<p>8</p>
<p>5 15</p>
<p>3 5</p>
<p>9 13</p>
<p>13 20</p>
<p>24 30</p>
<p>40 50</p>
<p>9 12</p>
<p>5 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>8</p>
<p> </p>
<p>样例2：</p>
<p>18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤ n≤ 10000</p>
<p>hi 和wi 都介于1 和65536 之间</p>
<p>TW一百学年度全国高级中学咨询学科能力竞赛决赛1</p>
</div>
</div>