<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>丽江河边有 n 家很有特色的客栈，客栈按照其位置顺序从1 到n 编号。每家客栈都按照某一种色调进行装饰（总共k 种，用整数0 ~ k-1 表示），且每家客栈都设有一家咖啡店，每家咖啡店均有各自的最低消费。<br>两位游客一起去丽江旅游，他们喜欢相同的色调，又想尝试两个不同的客栈，因此决定<strong>分别住在色调相同的两家客栈中</strong>。晚上，他们打算选择一家咖啡店喝咖啡，要求咖啡店位于两人住的两家客栈之间（包括他们住的客栈），且咖啡店的最低消费不超过p。<br>他们想知道总共有多少种选择住宿的方案，保证晚上可以找到一家最低消费不超过p元的咖啡店小聚。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共n+1 行。<br>第一行三个整数 n，k，p，每两个整数之间用一个空格隔开，分别表示客栈的个数，色调的数目和能接受的最低消费的最高值；<br>接下来的 n 行，第i+1 行两个整数，之间用一个空格隔开，分别表示i 号客栈的装饰色调和i 号客栈的咖啡店的最低消费。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，一个整数，表示可选的住宿方案的总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2 3<br>0 5<br>1 3<br>0 2<br>1 4<br>1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例说明】</p>
<table border="0">
<tbody>
<tr>
<td>客栈编号</td>
<td>①</td>
<td>②</td>
<td>③</td>
<td>④</td>
<td>⑤</td>
</tr>
<tr>
<td>色调 </td>
<td>0 </td>
<td>1 </td>
<td>0 </td>
<td>1 </td>
<td>1 </td>
</tr>
<tr>
<td>最低消费 </td>
<td>5 </td>
<td>3 </td>
<td>2 </td>
<td>4 </td>
<td>5</td>
</tr>
</tbody>
</table>
<p>2 人要住同样色调的客栈，所有可选的住宿方案包括：住客栈①③，②④，②⑤，④⑤，<br>但是若选择住 4、5 号客栈的话，4、5 号客栈之间的咖啡店的最低消费是 4，而两人能承受<br>的最低消费是 3 元，所以不满足要求。因此只有前 3 种方案可选。</p>
<p> </p>
<p>【数据范围】<br>对于 30%的数据，有n≤100；<br>对于 50%的数据，有n≤1,000；<br>对于 100%的数据，有2≤n≤200,000，0&lt;k≤50，0≤p≤100， 0≤最低消费≤100。</p>
</div>
</div>