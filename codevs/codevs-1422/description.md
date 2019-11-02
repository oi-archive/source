<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，河城荷取是擅长高科技工业的河童。荷取的得意之作除了光学迷彩外，还有震动整个幻想乡的巨型人形『非想天则』。不过由于人形太过巨大，所以为它充能是一件很麻烦的事。人形一共有N个电能池，编号1..N。其中前L个电能池(即编号为1..L的电能池)连接着外部充能接口，而编号为N的电能池连接着动力炉核心。在N个蓄能池之间有M条单向管道，每条管道有一个激活代价cost和电能传输极限limit。当激活度达到某个值时，所以激活代价小于等于这个值的管道都会被激活，但是每一条管道只能够最多传送limit个单位的电能。外部接口到电能池和电能池到动力炉核心的管道传输没有限制并且激活代价为0。现在荷取想往动力炉核心输入至少K个单位的电能，求需要的最小激活度。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：4个正整数N,M,L, K<br> 　　第2..M行：4个整数，u,v,limit,cost，表示一条由u到v的管道，传输极限limit，激活代价为cost</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：1个整数，表示最小激活代价</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 5 3 3<br> 1 4 2 4<br> 2 4 3 5<br> 3 5 4 2<br> 4 6 2 3<br> 5 6 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>　　对于30%的数据：1 ≤ L ≤ N ≤ 100，0 ≤ M ≤ 2,000，1 ≤ cost ≤ 10,000<br> 　　对于60%的数据：1 ≤ L ≤ N ≤ 1,000，0 ≤ M ≤ 20,000，1 ≤ cost ≤ 10,000<br> 　　对于100%的数据：1 ≤ L ≤ N ≤ 2,000，0 ≤ M ≤ 80,000，1 ≤ cost ≤ 1,000,000<br> 　　对于100%的数据：1 ≤ limit ≤ 1,000<br>　提示<br>　　样例解释：<br> 　　当激活度为4时，除了(2,4)外其他管道都能够使用。此时能够输入恰好4个单位电能。具体如下：<br> 　　(1,4) 输送2个单位电力<br> 　　(4,6) 输送2个单位电力<br> 　　(3,5) 输送2个单位电力<br> 　　(5,6) 输送2个单位电力<br> 　　<br><br> 　　注意：<br> 　　保证任意(u,v)都只出现一次。</p>
</div>
</div>