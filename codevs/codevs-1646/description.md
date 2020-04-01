<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>话说3008年的Orz教主节，全民狂欢，传递教主圣火，以致万人空巷，股票飞涨。真乃锣鼓喧天，鞭炮齐鸣，红旗招展，人山人海呐。可是小X为了准备NOIP3008，不得不待在家里好好Coding。小X希望早点结束当天的任务，加入圣火传递队伍中去。</p>
<p>在这个不亚于狂欢节的日子里，小X的老师却“公然违抗”休假法令，布置小X写一个小根堆，但是小X不会堆的操作，所以想了一个偷懒的办法：</p>
<p>堆是一棵完全二叉树，每个结点有一个权。小根堆的根的权最小，且根的两个子树也是一个堆。可以用一个数组a来记录一棵完全二叉树，a[1]为根结点，若结点a[j]不是根结点，那么它的父亲为a[j/2]（取下整）；若结点a[k]不是叶子结点，那么它的左儿子为a[2k]，它的右儿子为a[2k+1]。</p>
<p>他希望一组数据按一定顺序依次插入数组中（即第i个数为a[i]），最后得出来就已经是一个堆，即不需要任何交换操作，若有多种方法，输出字典序最大的一组，显得这个数据更乱。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第1行为一个正整数n，为插入的数字的个数。</p>
<p>第2行包含n个正整数，为所有需要插入的数字，数字之间用空格隔开。</p>
<p>为了简化题目，数据保证n=2^k-1，即保证最后的堆是一棵满二叉树。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出包括1行，为插入的序列，数字之间用空格隔开，行末换行并没有空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>10 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 10 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> </p>
<p>【样例说明】</p>
<p>1 2 10与1 10 2都是满足要求的插入序列，但是1 10 2的字典序更大。</p>
<p> </p>
<p>【数据规模】</p>
<p>　　对于20%的数据，n≤7；</p>
<p>对于30%的数据，n≤15；</p>
<p>对于50%的数据，n≤1023； </p>
<p>对于100%的数据，n≤65535，所有数字不超过10^8，且各不相同。</p>
</div>
</div>