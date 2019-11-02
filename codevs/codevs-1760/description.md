<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　对于一个由平面上点组成的集合S，以及一个平面上的点p，函数f(p,S)<span style="text-decoration: underline;"><em><strong>当且仅当p在S的凸包内部（包括S的凸包的边界）</strong></em></span>时值为1，其余情况下其值为0。</span><br><span>　　现给定两个平面上的点集P={p<sub>1</sub>,p<sub>2</sub>,…,p<sub>N</sub> }和A={a<sub>1</sub>,a<sub>2</sub>,…,a<sub>M</sub> }，我们称A中的一个点a<sub>i</sub>为<strong><span style="text-decoration: underline;"><em>极点</em></span></strong>，当且仅当其满足</span></p>
<p><span><img height="58" src="/source/codevs/codevs-1760/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZU5iNWRyRjk=.do" style="" width="183"></span></p>
<p><span><span>　　也就是说，<span style="text-decoration: underline;"><em><strong>a<sub>i</sub>不在任意 A 集合中非 a<sub>i</sub> 的点与P组成的凸包内部。</strong></em></span></span><br><span>　　请统计出集合A中极点的个数。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入第一行包含两个用空格隔开的正整数N和M；</span><br><span>　　第二行包含N个用空格隔开的整数对，第i个数对(x<sub>i</sub><sup>p</sup>,y<sub>i</sub><sup>p</sup>)表示点p<sub>i</sub>的坐标；</span><br><span>　　第三行包含M个用空格隔开的整数对，第j个数对(x<sub>j</sub><sup>a</sup>,y<sub>j</sub><sup>a</sup>)表示点a<sub>j</sub>的坐标。</span><br><span>　　对于同一个集合，输入数据保证不会出现坐标相同的两个点。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出包含一行一个整数，表示集合A中极点的个数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 5</span><br><span>6 3 7 -1 -6 -5 1 5</span><br><span>-5 -5 7 -5 9 -9 -10 11 -5 -6</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例解释】</span></p>
<p><span>　　极点分别为(-10,11)，(9,-9)以及(-5,-6)。</span></p>
<p><span><br></span></p>
<p><span>【数据规模】</span></p>
<p><span><span>　　对于10%的数据满足M = 1；</span><br><span>　　对于30%的数据满足N,M ≤ 50；</span><br><span>　　对于另外30%的数据满足N ≤ 10，M ≤ 20000；</span><br><span>　　对于100%的数据满足3 ≤ N ≤ 10<sup>5</sup>, 1 ≤ M ≤ 10<sup>5</sup>，|x<sub>i</sub> |,|y<sub>i</sub> | ≤ 10<sup>6</sup>，且点集P的凸包面积不为0。</span></span></p>
</div>
</div>