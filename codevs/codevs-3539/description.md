<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><strong>最近查理九世这一系列的书销售量迅速飙升，而书城的图书管理员也因此有了烦恼，他开始记不清楚查理九世第几部销售了几册，也无法整理归类。这时他想到了聪明的你，(这个家伙早不想起，晚不想起，偏偏在这个时候想起，有这样的朋友也是无奈啊)请你帮他把这些杂乱的数据按照销售量从高到低排序，并输出前五名，以便他将这些书放到热销书架上。</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><strong>第一行有一个数n，说明有n个数据。接下来n行每行两个数，分别是书册数和销售量。(若销售量相同则按册数排序</strong><strong>)</strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><strong>五行，热销书的册数。(若不足五行，则输出error)</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong>5</strong></p><p><strong>1 3</strong></p><p><strong>2 1</strong></p><p><strong>3 6</strong></p><p><strong>5 4</strong></p><p><strong>6 2</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong>3<br></strong></p><p><strong>5</strong></p><p><strong>1</strong></p><p><strong>6</strong></p><p><strong>2</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>60%的数据：1&lt;n&lt;100，1&lt;a[i]&lt;10000。</strong></p><p><strong>100%的数据：1&lt;n&lt;1000000，1&lt;a[i]&lt;1000000。</strong></p><p><strong><br></strong></p><p><b>参考代码（程序填空）：</b></p><p></p><p><strong>type cljs=record</strong></p><p><strong>  xb,xs:longint;</strong></p><p><strong>end;</strong></p><p><strong>var</strong></p><p><strong>  a:array[1..1000000] of ?;</strong></p><p><strong>  b:array[1..1000000] of ?;</strong></p><p><strong>  n,i,j,t,max,maxid:longint;</strong></p><p><strong>begin</strong></p><p><strong>  readln(n);</strong></p><p><strong>  for i:=1 to n do</strong></p><p><strong>    readln(a[i].?,a[i].?);</strong></p><p><strong>  t:=n;</strong></p><p><strong>  if n&gt;5 then</strong></p><p><strong>    n:=?;</strong></p><p><strong>  for i:=1 to n do</strong></p><p><strong>  begin</strong></p><p><strong>    max:=0;</strong></p><p><strong>    for j:=1 to t do</strong></p><p><strong>      if (a[j].?&gt;max) and not b[a[j].?] then</strong></p><p><strong>      begin</strong></p><p><strong>        max:=?;</strong></p><p><strong>        maxid:=?;</strong></p><p><strong>      end;</strong></p><p><strong>    b[maxid]:=?;</strong></p><p><strong>    writeln(?);</strong></p><p><strong>  end;</strong></p><p><strong>  for i:=1 to ? do</strong></p><p><strong>    writeln('error');</strong></p><p><strong>end.</strong></p><p><br></p>
</div>
</div>