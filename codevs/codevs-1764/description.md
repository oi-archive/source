<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　APIO王国正被忍者攻击！忍者非常厉害，因为他们在进攻的时候可以躲在阴影里面使得其他人看不到他们。整个王国除了国王居住的APIO城堡以外都已经被占领了。在城堡前，有N个灌木丛，从1到N编号，有K个忍者躲在恰好K个灌木丛后面。APIO城堡里有M个守卫。守卫i监视着编号从A</span><sub>i</sub><span>到B</span><sub>i</sub><span>的连续的一段灌木丛。每个守卫都向国王报告在他所监视范围内是否有忍者出现。作为国王的仆人，你需要告诉国王，基于守卫的报告，哪些灌木丛后面一定躲着一个忍者，即对于任何和守卫报告不矛盾的忍者排列方式，在这个灌木丛后面都躲着一个忍者。</span><br><span>　　你需要写一个程序来输出所有的这些灌木丛的编号。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行包含三个用空格分隔的整数N, K, M，N是灌木丛的个数，K是忍者的个数，M是守卫的个数。</span><br><span>　　接下来M行，每行描述一个守卫的信息。其中的第i行包含三个整数A</span><sub>i</sub><span>, B</span><sub>i</sub><span>, C</span><sub>i</sub><span>，表示第i个守卫的监视范围是从A</span><sub>i</sub><span>到B</span><sub>i</sub><span>（A</span><sub>i</sub><span> ≤ B</span><sub>i</sub><span>）。C</span><sub>i</sub><span>是0或者1，若是0表示范围内没有看到忍者，1表示范围内有至少一个忍者。</span><br><span>　　输入数据保证至少存在一种忍者排列方式满足所有条件。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　若存在灌木丛，在其后面一定躲着忍者，则将这些一定躲着忍者的灌木丛按照编号从小到大的顺序依次输出，每个一行。即若有X个这样的灌木丛，则需要输出X行。若不存在，则输出一行一个&ldquo;-1&rdquo;，不包含引号。</span></p>

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
<p><span>5 3 4</span><br><span>1 2 1</span><br><span>3 4 1</span><br><span>4 4 0</span><br><span>4 5 1</span></p>
<p><span><br></span></p>
<p><span>【样例输入2】</span></p>
<p><span><span>5 1 1</span><br><span>1 5 1</span></span></p>
<p><span><span><br></span></span></p>

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
<p><span>3</span><br><span>5</span></p>
<p><span><br></span></p>
<p><span>【样例输出2】</span></p>
<p><span><span>-1</span></span></p>
<p><span><span><br></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例解释1】</span></p>
<p><span><span>　　在这个样例中，有两种可能的安排方式：1，3，5或者2，3，5。即3和5后面必然躲着一个忍者。</span><br><span>　　考虑第一个灌木丛，存在一种安排方案使得它的后面躲着忍者，但也存在一种安排方案使得它后面没有躲忍者，因此不应该输出1。同理，不应该输出2。</span></span></p>
<p><span><span><br></span></span></p>
<p><span><span>【样例数据2】</span></span></p>
<p><span><span><span>　　在这个样例中，没有灌木丛后面一定躲着忍者。</span></span></span></p>
<p><span><span><br></span></span></p>
<p><span>【数据规模】</span></p>
<p><span>　　1 ≤ N ≤ 100,000 灌木的数量；</span><br><span>　　1 ≤ K ≤ N 忍者数；</span><br><span>　　1 ≤ M ≤ 100,000 守卫数。</span><br><span>　　对于10%的数据，N ≤ 20， M ≤ 100；</span><br><span>　　对于50%的数据，N ≤ 1000， M ≤ 1000。</span></p>
<p><span><br></span></p>
<p><strong>(采用国内数据)</strong></p>
</div>
</div>