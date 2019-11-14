<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>童年的我们，将和朋友分享美好的事物作为自己的快乐。这天，C小朋友得到了Plenty of candies，将要把这些糖果分给要好的朋友们。已知糖果从一个人传给另一个人需要1 秒的时间，同一个小朋友不会重复接受糖果。由于糖果足够多，如果某时刻某小朋友接受了糖果，他会将糖果分成若干份，分给那些在他身旁且还没有得到糖果的小朋友们，而且自己会吃一些糖果。由于嘴馋，小朋友们等不及将糖果发完，会在得到糖果后边吃边发。每个小朋友从接受糖果到吃完糖果需要m秒的时间。那么，如果第一秒C小朋友开始发糖，第多少秒所有小朋友都吃完了糖呢?</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为三个数n、p、c，为小朋友数、关系数和C小朋友的编号。<br>第二行为一个数m，表示小朋友吃糖的时间。<br>下面p行每行两个整数，表示某两个小朋友在彼此身旁</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数，为所有小朋友都吃完了糖的时间</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 1<br>2<br>1 2<br>2 3<br>1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【限制】<br>40%的数据满足：1&lt;=n&lt;=100<br>60%的数据满足：1&lt;=n&lt;=1000<br>100%的数据满足：1&lt;=n&lt;=100000<br>m&lt;=n*(n-1)/2,不会有同一个关系被描述多次的情况。</p>
<p>【样例解释】<br>　　第一秒，糖在1手上。第二秒，糖传到了2、3的手中。第三秒，糖传到了4的手中，此时1吃完了。第四秒，2、3吃完了。第五秒，4吃完了。所以答案是5。</p>
</div>
</div>