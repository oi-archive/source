<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">众所周知，IOIForum有很多水王，他们的发贴数是如此之多，以至于必须要用高精度数才能保存。</p><p style="">为了迎接国庆，IOIForum决定举行一次水王争霸赛，比赛的规则是将这些水王截止到2003年9月30日23时59分59秒这一刻所发的总贴数从大到小进行排序。每个水王当然都想取得尽量靠前的名次，所以他们竭尽全力，不择手段地进行灌水。</p><p style="">终于，激动人心的一刻到来了，2003年10月1日0时0分0秒，你作为裁判得到了每个水王的发贴数，现在，你的任务是公正地把这些水王按照发贴数从大到小进行排序。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入的第一行是一个1到1000的整数N，表示总共有N位水王参加了争霸赛。</p><p style="">以下依次给出每位水王的描述，一位水王的描述占据两行，第一行为一个仅由字母和数字组成的长度不超过20的字符串，代表这个水王的ID，第二行一个高精度的整数(非负数)，代表这个水王的发贴数。注意，这个整数的首位没有不必要的0。</p><p style="">考虑到IOIForum的数据库是有限的，所有水王发贴数的总长度（注意，是总长度而不是总和）不会超过10000。</p><p style="">除了子母、数字和必要的换行，输入中不会出现空格等字符。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Lucida Grande&#39;, Lucida, &#39;Lucida Sans Unicode&#39;, &#39;Lucida Sans&#39;, Tahoma, &#39;Segoe UI&#39;, Verdana, 微软雅黑, &#39;Microsoft YaHei&#39;, 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">依次输出按照发贴数从大到小排好序的各位水王的ID，每个ID占据单独的一行。不能有任何多余的字符。若几个ID的发贴数相同，则按照ID的字典顺序先后排列。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p><p>lowai</p><p>1534534124561243453</p><p>zhouyuan</p><p>23453265344</p><p>Maolaoda</p><p>23442353452342</p><p>BuTaoCaiGuai</p><p>7568784573464</p><p>ArthurKing</p><p>97534892734723947</p><p>hyyylr</p><p>623893451</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>lowai</p><p>ArthurKing</p><p>Maolaoda</p><p>BuTaoCaiGuai</p><p>zhouyuan</p><p>hyyylr</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=<span style="">1000</span></p>
</div>
</div>