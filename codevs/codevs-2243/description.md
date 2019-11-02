<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>随着捷运线的增加，台北市捷运局决定开发一个 App，来提供大众更便利的捷运搭乘经验。这个App 需要在任何时间点，找出给定之两个捷运站之间，不含等车时间的最短搭车时间。所有捷运线都在 06:00 从第一站与最后一站同时列车进站对开，每隔五分钟就发一班车，最后一班车则在 23:55 发车。捷运到站后（包含起站）停留时间都是一分钟 ( 所以第一班车其实是在06:01 离站) 。为了确保App 的实用性，使用者抵达某捷运站时间必须早于该站捷运开车时间，才能顺利的搭上捷运。举例而言，若抵达时间为 13:55 ，而欲搭的捷运于13:54 抵达，且将于 13:55 开车，那么本班车就赶不上，必须等待下一班车。但若是13:54抵达捷运站，则立刻搭上本班捷运（虽然要一分钟后捷运才会离站）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个正整数  n, m  ( 1≤n≤10, 1≤m≤100 ) ，以空白隔开，代表共有n 条捷运线，且有 m 个交叉点，每个交叉点代表两条捷运线共站，本题不会有三条或三条以上的捷运线共站。接下来的n 行，每行都有四个以上的正整数i, k, s<sub>1</sub>, s<sub>2</sub>,..., s<sub>k</sub>，连续两个数字之间以空白隔开，其中i  ( 1≤i≤100 ) 为捷运线代号，k  ( 2≤k≤20 ) 为该捷运线总站数，s<sub>p</sub>  (1≤p≤k)  代表从( p-1) 号站到p 号站所需的行车时间( 以分钟为单位)，因为 s<sub>1</sub> 是起站，因此 s<sub>1</sub> 一定是0。接下来有 m 行，每行四个正整数  i , p , j , q ，连续两个数字之间以空白隔开，代表i 号捷运线的p 号站与j 号捷运线的q 号站共站。最后有五行的使用者测试资料，每行有六个数字：hh, mm,  i , p , j , q ，连续两个数字之间以空白隔开，代表 App 使用者可于hh: mm ( 6≤hh≤23,  0≤mm≤59 ) 前抵达i 号捷运线的p 号站且希望前往 j 号捷运线的q号站。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每个使用者测试资料都有一行的输出，共五行。每行一个正整数，代表抵达目的地捷运站所需搭乘捷运最短时间( 以分钟为单位)，此时间不包含初始等待捷运或转搭另一捷运线时在月台等待捷运进站时间。所有的测试资料都会在捷运停驶前可以抵达目的地。</p>
<p>以输入范例第一个测资：6 0 10 1 10 3为例，使用者于 06:00 抵达10号捷运线的1 号站，目的地为 10号线的3 号站，因此搭乘捷运所需的最短时间为：1 分钟 ( 在捷运上等待离站) + 2 分钟 ( 到达2 号站所需时间) + 1 分钟 ( 在捷运上等待离站) + 2 分钟 ( 到达3 号站所需时间) = 6 分钟。若以输入范例第四个测资：12 7 2 1 10 1&nbsp; 为例，使用者于12:07 抵达2 号捷运线的1 号站，目的地为10号线的1 号站，因此搭乘捷运所需的最短时间为：1 分钟 (12:10之捷运进站后搭上捷运并在捷运上等待离站) + 4 分钟 ( 到达2 号站所需时间) + 1 分钟 (2号线于12:15 到站后下车等待12:18 抵达的10号线，上车并在捷运上等待离站) + 2 分钟 ( 到达 10号线2 号站所需时间) + 1 分钟 ( 在捷运上等待离站) + 2 分钟 ( 到达10号线1 号站所需时间) = 11 分钟。<img src="../../../media/image/problem/2243.png" alt="" width="326" height="204" /></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>10 7 0 2 2 3 2 1 3</p>
<p>2 3 0 4 4</p>
<p>7 5 0 5 1 1 3</p>
<p>10 3 2 2</p>
<p>7 2 10 5</p>
<p>7 4 2 3</p>
<p>6 0 10 1 10 3</p>
<p>6 12 10 7 10 1</p>
<p>13 55 2 1 2 3</p>
<p>12 7 2 1 10 1</p>
<p>23 0 10 5 2 3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>19</p>
<p>10</p>
<p>11</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>TW一百学年度全国高级中学咨询学科能力竞赛决赛4</p>
</div>
</div>