<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在很久很久以前，曾经有两个国家和睦相处，无忧无虑的生活着。 <br>一年一度的评比大会开始了，作为和平的两国，一个朋友圈数量最多的永远都是最值得<br>他人的尊敬，所以现在就是需要你求朋友圈的最大数目。 <br>两个国家看成是 AB 两国，现在是两个国家的描述： <br>1、 A 国：每个人都有一个友善值，当两个 A 国人的友善值 a、b，如果 a xor b mod 2=1，<br>那么这两个人都是朋友，否则不是； <br>2、 B 国：每个人都有一个友善值，当两个 B 国人的友善值 a、b，如果 a xor b mod 2=0<br>或者 (a or b)化成二进制有奇数个 1，那么两个人是朋友，否则不是朋友； <br>3、 A、B 两国之间的人也有可能是朋友，数据中将会给出 A、B之间&amp;ldquo;朋友&amp;rdquo;的情况。</p><p>4、 对于朋友的定义，关系是是双向的。 <br>在 AB 两国，朋友圈的定义：一个朋友圈集合 S，满足 <br>S属于A并B，对于所有的 i，j属于S，i 和 j是朋友 <br>由于落后的古代，没有电脑这个也就成了每年最大的难题，而你能帮他们求出最大朋<br>友圈的人数吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 t&lt;=6,表示输入数据总数。 <br>接下来 t 个数据： <br> 第一行输入三个整数 A,B,M，表示A国人数、B 国人数、AB 两国之间是朋友的对数； <br> 第二行 A 个数 ai，表示A 国第i 个人的友善值； <br> 第三行 B 个数 bi，表示B 国第j 个人的友善值； <br> 第 4&amp;mdash;&amp;mdash;3+M行，每行两个整数（i，j） ，表示第i 个A 国人和第 j 个B 国人是朋友。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;输出 t 行，每行，输出一个整数，表示最大朋友圈的数目。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 <br>2 4 7 <br>1 2 <br>2 6 5 4 <br>1 1 <br>1 2 <br>1 3 <br>2 1 <br>2 2 <br>2 3 <br>2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于其中 30%的数据，A=0，B&lt;=100； <br>对于其中 50%的数据，A&lt;=10，B&lt;=100； <br>对于其中 10%的数据，A&lt;=5，B&lt;=1000； <br>对于其中 10%的数据，A&lt;=5，B&lt;=1500； <br>对于 100%的数据，M&lt;=A*B，友善值在2^30 以内。</p>
</div>
</div>