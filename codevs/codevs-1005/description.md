<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       9月12日是小松的朋友小寒的生日。小松知道小寒特别喜欢蝴蝶，所以决定折蝴蝶作为给小寒的生日礼物。他来到了PK大学最大的一家地下超市，在超市里，小松找到了<em>n</em>种可以用来折纸的本子。每种类型的本子里有若干不同颜色的纸若干张，当然同种类型的本子一定是<strong>完全一样</strong>的，而不同种类型的本子不一定完全不一样。他统计了一下，这里总共有<em>n</em>种不同类型的可以用来折纸的本子，每种本子各有<em>bi</em>本，所有的纸中有<em>m</em>种颜色是小寒所喜欢的颜色。小松希望他折的每种颜色的蝴蝶的数目是一样的。换句话说，小松必须折<em>m</em>*<em>k</em>只蝴蝶，其中<em>k</em>代表每种颜色蝴蝶的数目，这个数由小松自己来决定。但是小松又不能浪费纸，也就是说他买的本子中，只要是小寒喜欢的颜色的纸都要被折成蝴蝶。于是问题来了，每种类型的本子应该各买多少本，才能折出这<em>m</em>*<em>k</em>只蝴蝶呢？当然，由于小松是个很懒的人，他希望折的蝴蝶数目越少越好，只要表达了心意就可以了（也就是不能1只也不折）。而如果小松总共必须折1000只以上的蝴蝶才能满足要求，那么他就宁愿换一种礼物的方案了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入的第一行包含2个整数<em>n</em>（1<em>≤n</em><em>≤</em>8），<em>m</em>（1<em>≤m</em><em>≤</em>10）。表示有<em>n</em>种不同类型的本子和<em>m</em>种小寒喜欢的颜色。接下来一个<em>n</em>*<em>m</em>的矩阵。第<em>i</em>行第<em>j</em>列的整数<em>aij</em>表示在第<em>i</em>种类型的本子中包含小寒喜欢的颜色<em>j</em>的纸有<em>aij</em>（1<em>≤aij</em><em>≤</em>100）张。再接下来的一排<em>n</em>个整数<em>b1</em>到<em>bn</em>，表示每种颜色的本子在超市中有多少本（1<em>≤bi</em><em>≤</em>5）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输出包含一个整数，表示小松最少需要折的蝴蝶数目，如果该数目超过1000，则输出&rdquo;alternative!&rdquo;。（由于可能存在多种买本子的方案，所以这里就不要求输出具体方案了）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>2 1 2</p>
<p>4 8 4</p>
<p>5 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>36</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>