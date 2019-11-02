<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>SBJ最近收到了n张数学卷子，这些卷子的标号为0 ... n-1，他不想写这些卷子，于是他的好朋友SCX热心地想要帮他撕掉n-1张卷子。SBJ很高兴，但是SCX说，他撕试卷的顺序是从0号试卷开始，每数m次撕掉一张卷子。但是SBJ并不管这东西，扔下笔，出去玩去了。<br><br>当Urimoo看到SBJ出去玩很不爽，作为SBJ的小弟，他必须把他的那张剩下的试卷写完。此时SCX因为在刷物理卷子没有撕试卷，作为Urimoo的好朋友，你必须告诉他第几张试卷没有被撕，Urimoo听到后就会兴高采烈的跑去写试卷啦(≧▽≦)~~~！！！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数T，表示有T组数据；</p><p>接下来T行，每行两个整数n, m。</p><p>n, m的描述见题意。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据，每行输出一个整数，k，表示你告诉Urimoo他要做第k张试卷。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>5 3</p><p>681 600</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>562</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><br>对于30%的数据：1 &lt;= n, m &lt;= 1000；</p><p>对于50%的数据：1 &lt;= n, m &lt;= 10000，1 &lt;= T &lt;= 5；</p><p>对于80%的数据：1 &lt;= n, m &lt;= 100000，1 &lt;= T &lt;= 50；</p><p>对于100%的数据：1 &lt;= n, m &lt;= 1000000，1 &lt;= T &lt;= 80。</p><p>所有输入数据均为随机生成。<br></p><p><img src="/source/codevs/codevs-4155/img/aHR0cDovL2ltZy5ibG9nLmNzZG4ubmV0LzIwMTUwOTA5MTkyMjU4MDE3" title=""><br></p><p><br></p><p>第一次撕掉2号试卷；<br>第二次撕掉0号试卷；<br>第三次撕掉4号试卷；<br>第四次撕掉1号试卷。</p>
</div>
</div>