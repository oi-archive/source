<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>S 城现有两座监狱，一共关押着N 名罪犯，编号分别为1~N。他们之间的关系自然也极</p>
<p>不和谐。很多罪犯之间甚至积怨已久，如果客观条件具备则随时可能爆发冲突。我们用“怨</p>
<p>气值”（一个正整数值）来表示某两名罪犯之间的仇恨程度，怨气值越大，则这两名罪犯之</p>
<p>间的积怨越多。如果两名怨气值为c 的罪犯被关押在同一监狱，他们俩之间会发生摩擦，并</p>
<p>造成影响力为c 的冲突事件。</p>
<p>每年年末，警察局会将本年内监狱中的所有冲突事件按影响力从大到小排成一个列表，</p>
<p>然后上报到S 城Z 市长那里。公务繁忙的Z 市长只会去看列表中的第一个事件的影响力，</p>
<p>如果影响很坏，他就会考虑撤换警察局长。</p>
<p>在详细考察了N 名罪犯间的矛盾关系后，警察局长觉得压力巨大。他准备将罪犯们在</p>
<p>两座监狱内重新分配，以求产生的冲突事件影响力都较小，从而保住自己的乌纱帽。假设只</p>
<p>要处于同一监狱内的某两个罪犯间有仇恨，那么他们一定会在每年的某个时候发生摩擦。那</p>
<p>么，应如何分配罪犯，才能使Z 市长看到的那个冲突事件的影响力最小？这个最小值是少？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个正整数N 和M，分别表示罪犯的数目以及存在仇恨的罪犯对数。</p>
<p>接下来的M 行每行为三个正整数aj，bj，cj，表示aj 号和bj 号罪犯之间存在仇恨，其怨气值为cj。数据保证<em><span style="font-family: Times New Roman;">，</span></em>且每对罪犯组合只出现一次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共1 行，为Z 市长看到的那个冲突事件的影响力。如果本年内监狱</p>
<p class="p0">中未发生任何冲突事件，请输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 6</p>
<p>1 4 2534</p>
<p>2 3 3512</p>
<p>1 2 28351</p>
<p>1 3 6618</p>
<p>2 4 1805</p>
<p>3 4 12884</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3512</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>罪犯之间的怨气值如下面左图所示，右图所示为罪犯的分配方法，市长看到的冲突事件</p>
<p>影响力是3512（由2 号和3 号罪犯引发）。其他任何分法都不会比这个分法更优。</p>
<p>【数据范围】</p>
<p>对于30%的数据有N≤ 15。</p>
<p>对于70%的数据有N≤ 2000，M≤ 50000。</p>
<p>对于100%的数据有N≤ 20000，M≤ 100000。</p>
</div>
</div>