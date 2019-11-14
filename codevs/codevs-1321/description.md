<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一年一度的圣诞节快要来到了。每年的圣诞节小E都会收到许多礼物，当然他也会送出许多礼物。不同的人物在小E心目中的重要性不同，在小E心中分量越重的人，收到的礼物会越多。小E从商店中购买了n件礼物，打算送给m个人，其中送给第i个人礼物数量为w<sub>i</sub>。请你帮忙计算出送礼物的方案数（两个方案被认为是不同的，当且仅当存在某个人在这两种方案中收到的礼物不同）。由于方案数可能会很大，你只需要输出模P后的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个正整数P，表示模；</p>
<p>第二行包含两个整整数n和m，分别表示小E从商店购买的礼物数和接受礼物的人数；</p>
<p>以下m行每行仅包含一个正整数w<sub>i</sub>，表示小E要送给第i个人的礼物数量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若不存在可行方案，则输出&ldquo;Impossible&rdquo;，否则输出一个整数，表示模P后的方案数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>100</p>
<p>4 2</p>
<p>1</p>
<p>2</p>
<p> </p>
<p>【样例输入2】</p>
<p>100</p>
<p>4 2</p>
<p>1</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>12</p>
<p> </p>
<p>【样例输出2】</p>
<p>Impossible</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>下面是对样例1的说明。</p>
<p>以“/”分割，“/”前后分别表示送给第一个人和第二个人的礼物编号。12种方案详情如下：</p>
<p>1/23 1/24 1/34</p>
<p>2/13 2/14 2/34</p>
<p>3/12 3/14 3/24</p>
<p>4/12 4/13 4/23</p>
<p> </p>
<p>数据规模</p>
<p>设P=p<sub>1</sub>^c<sub>1</sub> * p<sub>2</sub>^c<sub>2</sub> * p<sub>3</sub>^c<sub>3</sub> * … *p<sub>t</sub> ^ c<sub>t</sub>，p<sub>i</sub>为质数。</p>
<p>对于15%的数据，n≤15，m≤5，p<sub>i</sub>^c<sub>i</sub>≤10<sup>5</sup>；</p>
<p>在剩下的85%数据中，约有60%的数据满足t≤2，c<sub>i</sub>=1，p<sub>i</sub>≤10<sup>5</sup>，约有30%的数据满足p<sub>i</sub>≤200。</p>
<p>对于100%的数据，1≤n≤10<sup>9</sup>，1≤m≤5，1≤p<sub>i</sub>^c<sub>i</sub>≤10<sup>5</sup>。</p>
</div>
</div>