<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，铃仙•优昙华院•稻叶是从月球逃到永远亭的月兔。同样居住在永远亭的地球兔子因幡帝老是对铃仙恶作剧。某一天，铃仙终于决定要惩罚一下帝，不过首先得在迷途竹林里把帝抓住。永远亭的迷途竹林可以视为一个由N个路口(编号1..N)，M条单向路连接的区域。开始时，帝在路口1，每一个单位时间，帝会以相同的概率走到相邻的路口或是停留在当前路口，一条路可以重复走，但是帝不会走回头路，也就是说如果帝从路口x走到了路口y，在到过其他路口前，她一定不会从路口y走回路口x。现在铃仙想知道，在T秒钟以后，在哪个路口抓到帝的可能性最大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　输入格式<br>　　第1行：3个非负整数N, M, T<br> 　　第2..M+1行：每行2个整数u,v，表示存在一条从路口u到路口v的单向路<br> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　输出格式<br />　　第1..N行：一个实数，第i行表示在路口i抓到帝的概率，单位为%，保留3位小数<br />　&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入<br>3 4 2<br> 1 2<br> 1 3<br> 2 1<br> 2 3<br> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>　样例输出<br>11.111<br> 27.778<br> 61.111<br> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>　数据范围<br>　　对于30%的数据，N ≤ 5, M ≤ 10, T ≤ 10<br> 　　对于60%的数据，N ≤ 10, M ≤ 50, T ≤ 500<br> 　　对于100%的数据，N ≤ 50, M ≤ 2000, T ≤ 500<br>　提示<br>　　样例解释：<br> 　　时刻0: 1(100%)<br> 　　时刻1: 1(33.333%) 2(33.333%) 3(33.333%)<br> 　　时刻2: 1(11.111%) 2(11.111%+16.667%) 3(33.333%+11.111%+16.667%)<br> 　　在时刻2时，只能从路口2走向路口3，不可返回路口1。<br> 　　若时刻2选择停留在路口2，时刻3时仍然不可以从路口2走回路口1，因为尚未走到过其他路口。<br><br> 　　注意：输入数据中无重复的边，且不存在自环。</p>
</div>
</div>