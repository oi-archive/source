<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Tom最近在研究一个有趣的排序问题。如图所示，通过2个栈S1和S2，Tom希望借助以下4种操作实现将输入序列升序排序。</p>
<p>操作a</p>
<p>如果输入序列不为空，将第一个元素压入栈S1</p>
<p>操作b</p>
<p>如果栈S1不为空，将S1栈顶元素弹出至输出序列</p>
<p>操作c</p>
<p>如果输入序列不为空，将第一个元素压入栈S2</p>
<p>操作d</p>
<p>如果栈S2不为空，将S2栈顶元素弹出至输出序列</p>
<p>如果一个1~n的排列P可以通过一系列操作使得输出序列为1，2，…，(n-1)，n，Tom就称P是一个“可双栈排序排列”。例如(1,3,2,4)就是一个“可双栈排序序列”，而(2,3,4,1)不是。下图描述了一个将(1,3,2,4)排序的操作序列：&lt;a,c,c,b,a,d,d,b&gt;</p>
<p> </p>
<p>当然，这样的操作序列有可能有几个，对于上例(1,3,2,4)，&lt;a,c,c,b,a,d,d,b&gt;是另外一个可行的操作序列。Tom希望知道其中字典序最小的操作序列是什么。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是一个整数n。</p>
<p>第二行有n个用空格隔开的正整数，构成一个1~n的排列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共一行，如果输入的排列不是&ldquo;可双栈排序排列&rdquo;，输出数字0；否则输出字典序最小的操作序列，每两个操作之间用空格隔开，行尾没有空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例1】</p>
<p>4</p>
<p>1 3 2 4</p>
<p> </p>
<p>【样例2】</p>
<p>4</p>
<p>2 3 4 1</p>
<p> </p>
<p>【样例3】</p>
<p>3</p>
<p>2 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例1】</p>
<p>a b a a b b a b</p>
<p>【样例2】</p>
<p>0</p>
<p>【样例3】</p>
<p>a c a b b d</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据满足： n&lt;=10</p>
<p>50%的数据满足： n&lt;=50</p>
<p>100%的数据满足： n&lt;=1000</p>
</div>
</div>