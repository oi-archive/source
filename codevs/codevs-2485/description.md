<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　七夕节因牛郎织女的传说而被扣上了「情人节」的帽子。于是TYVJ今年举办了一次线下七夕祭。Vani同学今年成功邀请到了cl同学陪他来共度七夕，于是他们决定去TYVJ七夕祭游玩。</p>
<p>　　TYVJ七夕祭和11区的夏祭的形式很像。矩形的祭典会场由N排M列共计N×M个摊点组成。虽然摊点种类繁多，不过cl只对其中的一部分摊点感兴趣，比如章鱼烧、苹果糖、棉花糖、射的屋……什么的。Vani预先联系了七夕祭的负责人zhq，希望能够通过恰当地布置会场，使得各行中cl感兴趣的摊点数一样多，并且各列中cl感兴趣的摊点数也一样多。不过zhq告诉Vani，摊点已经布置完毕了，唯一的调整方式就是交换两个相邻的摊点。两个摊点相邻，当且仅当他们处在同一行或者同一列的相邻位置上。由于zhq率领的TYVJ开发小组成功地扭曲了空间，每一行或每一列的第一个位置和最后一个位置也算作相邻。现在Vani想知道他的两个要求最多能满足多少个。在此前提下，至少需要交换多少次摊点。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行包含三个整数N和M和T。T表示cl对多少个摊点感兴趣。 <br>　　接下来T行，每行两个整数x, y，表示cl对处在第x行第y列的摊点感兴趣。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　首先输出一个字符串。如果能满足Vani的全部两个要求，输出both；如果通过调整只能使得各行中cl感兴趣的摊点数一样多，输出row；如果只能使各列中cl感兴趣的摊点数一样多，输出column；如果均不能满足，输出impossible。&nbsp;<br />　　如果输出的字符串不是impossible， 接下来输出最小交换次数，与字符串之间用一个空格隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】<br>2 3 4 <br>1 3 <br>2 1 <br>2 2 <br>2 3</p>
<p>【样例输入2】<br>3 3 3 <br>1 3 <br>2 2 <br>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】<br>row 1</p>
<p>【样例输出2】<br>both 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围与约定 <br>　　对于30% 的数据，N, M≤100。 <br>　　对于70% 的数据，N, M≤1000。 <br>　　对于100% 的数据，1≤N, M≤100000，0≤T≤min(NM, 100000)，1≤x≤N，1≤y≤M。</p>
<p>来源：Nescafe 18</p>
</div>
</div>