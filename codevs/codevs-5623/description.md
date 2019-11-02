<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在日常生活中，通过年、月、日这三个要素可以表示出一个唯一确定的日期。</p><p>牛牛习惯用8位数字表示一个日期，其中，前4位代表年份，接下来2位代表月 份，最后2位代表日期。显然：一个日期只有一种表示方法，而两个不同的日期的表 示方法不会相同。</p><p>牛牛认为，一个日期是回文的，当且仅当表示这个日期的8位数字是回文的。现 在，牛牛想知道：在他指定的两个日期之间包含这两个日期本身），有多少个真实存 在的日期是回文的。</p><p>一个8位数字是回文的，当且仅当对于所有的i （ 1 &lt;=i&lt;= 8 )从左向右数的第i个 数字和第9-i个数字（即从右向左数的第i个数字）是相同的。</p><p>例如：</p><p>•对于2016年11月19日，用8位数字20161119表示，它不是回文的。</p><p>•对于2010年1月2日，用8位数字20100102表示，它是回文的。</p><p>•对于2010年10月2日，用8位数字20101002表示，它不是回文的。</p><p>每一年中都有12个月份：</p><p>其中，1、3、5、7、8、10、12月每个月有31天；4、6、9、11月每个月有30天；而对于2月，闰年时有29天，平年时有28天。</p><p>一个年份是闰年当且仅当它满足下列两种情况其中的一种：</p><p>1.这个年份是4的整数倍，但不是100的整数倍；</p><p>2.这个年份是400的整数倍。</p><p>例如：</p><p>•以下几个年份都是闰年：2000、2012、2016。</p><p>•以下几个年份是平年：1900、2011、2014。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包括两行，每行包括一个8位数字。</p><p>第一行表示牛牛指定的起始日期。</p><p>第二行表示牛牛指定的终止日期。</p><p>保证date_i和都是真实存在的日期，且年份部分一定为4位数字，且首位数字不为0。</p><p>保证date1 —定不晚于date2。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，包含一个整数，表示在date1和date2之间，有多少个日期是回文的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>20110101<br>20111231</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p><p>对于样例1，符合条件的日期是20111102。</p><p>对于样例2，符合条件的日期是20011002和20100102。</p><p>【子任务】</p><p>对于60%的数据，满足date1 = date2。</p><p><br></p>
</div>
</div>