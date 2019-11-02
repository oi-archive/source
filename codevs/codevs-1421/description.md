<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，秋姐妹是掌管秋天的神明，作为红叶之神的姐姐静叶和作为丰收之神的妹妹穰子。如果把红叶和果实联系在一起，自然会想到烤红薯。烤红薯需要很多的叶子，才能把红薯烤得很香，所以秋姐妹决定比比谁能够收集到最多的红叶。静叶将红叶分成了N堆(编号1..N)，并且规定了它们的选取顺序，刚好形成一颗有向树。在游戏过程中，两人从根节点开始，轮流取走红叶，当一个人取走节点i的红叶后，另一个人只能从节点i的儿子节点中选取一个。当取到某个叶子时游戏结束，然后两人会比较自己得到的红叶数量。已知两人采用的策略不一样，静叶考虑在让穰子取得尽可能少的前提下，自己取的最多；而穰子想得是在自己尽可能取得多的前提下，让静叶取得最少。在两人都采取最优策略的情况下，请你计算出游戏结束时两人的红叶数量。<br> 　　游戏总是静叶先取，保证只存在一组解。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：1个正整数N，表示红叶堆数<br> 　　第2行：N个整数，第i个数表示第i堆红叶的数量num[i]<br> 　　第3..N+1行：2个正整数u,v，表示节点u为节点v的父亲</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：2个整数，分别表示静叶取到的叶子数和穰子取到的叶子数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6<br> 4 16 16 5 3 1<br> 1 2<br> 2 4<br> 1 3<br> 3 5<br> 3 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7 16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>　　对于30%的数据：1 ≤ N ≤ 100，1 ≤ num[i] ≤ 100<br> 　　对于60%的数据：1 ≤ N ≤ 10,000，1 ≤ num[i] ≤ 10,000<br> 　　对于100%的数据：1 ≤ N ≤ 100,000，1 ≤ num[i] ≤ 10,000<br>　提示<br>　　样例解释：<br> 　　首先静叶一定能取得节点1的4片红叶，留给穰子的是节点2和3，均为16片红叶。<br> 　　若选取节点2则静叶下一次可以最多得到5片红叶，而选择3静叶最多也只能得到3片红叶，<br> 　　所以此时穰子会选择节点3，故静叶最后得到的红叶数为7，穰子为16。<br><br> 　　注意：<br> 　　保证两人得到的红叶数在[0, 2^31-1]。</p>
</div>
</div>