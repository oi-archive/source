<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小Z是一个小有名气的钢琴家，最近C博士送给了小Z一架超级钢琴，小Z希望能够用这架钢琴创作出世界上最美妙的音乐。</p>
<p>这架超级钢琴可以弹奏出n个音符，编号为1至n。第i个音符的美妙度为Ai，其中Ai可正可负。</p>
<p>一个“超级和弦”由若干个编号连续的音符组成，包含的音符个数不少于L且不多于R。我们定义超级和弦的美妙度为其包含的所有音符的美妙度之和。两个超级和弦被认为是相同的，当且仅当这两个超级和弦所包含的音符集合是相同的。</p>
<p>小Z决定创作一首由k个超级和弦组成的乐曲，为了使得乐曲更加动听，小Z要求该乐曲由k个不同的超级和弦组成。我们定义一首乐曲的美妙度为其所包含的所有超级和弦的美妙度之和。小Z想知道他能够创作出来的乐曲美妙度最大值是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含四个正整数n, k, L, R。其中n为音符的个数，k为乐曲所包含的超级和弦个数，L和R分别是超级和弦所包含音符个数的下限和上限。</p>
<p>接下来n行，每行包含一个整数Ai，表示按编号从小到大每个音符的美妙度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件只有一个整数，表示乐曲美妙度的最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 2 3</p>
<p>3</p>
<p>2</p>
<p>-6</p>
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;N&lt;=500000,0&lt;k&lt;=50000</p>
<p>所有数据满足：-1000 ≤ Ai ≤ 1000，1 ≤ L ≤ R ≤ n且保证一定存在满足要求的乐曲。</p>
</div>
</div>