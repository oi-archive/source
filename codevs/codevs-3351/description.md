<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某商品推销员到某小区推销产品，产品推销除了商品质量好之外，还需要客户能影响和带动身边信赖他的人也购买，如果A购买了产品，那么信赖A的B就有可能也购买，那么信赖B的C就也可能成为潜在客户。依据这种信赖关系，就可能构成一个庞大的潜在客户网。</p>
<p>聪明的推销员经过细心调查整理了这个小区里N个人的信赖关系，并且用1~N给这N个人编号。另外，这N个人中有P个潜在客户可能会被推销员直接说服购买产品，细心的推销员还估算了说服每个人具体需要花费的时间，那么请你帮推销员计算一下他最少需要花费多长时间来建立起这N个人的潜在客户网？</p>
<p>如果不能把这N个人全部纳入潜在客户网，输出不能被纳入网络的人的编号。注意，信赖关系不一定是相互的啊！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件第一行只有一个整数<span>n(n&lt;=3000)</span>。</span></p>
<p><span>第二行是整数<span>p</span>。表示能被说服的人数，<span>1</span>≤<span>p</span>≤<span>n</span>。</span></p>
<p><span> </span><span>接下来的<span>p</span>行，每行有两个整数，第一个数是一个能被说服的人的编号，第二个数表示他被说服需要花费的时间。这个数不超过<span>20000</span>个时间单位。</span></p>
<p><span>紧跟着一行只有一个整数<span>r</span>，<span>1</span>≤<span>r</span>≤<span>8000</span>。然后<span>r</span>行，每行两个正整数，表示数对<span>(A, B)</span>，<span>B</span>信赖<span>A</span>。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>如果可以把<span lang="EN-US">N</span>个人全部纳入潜在客户网，第一行输出<span lang="EN-US">YES</span>，并在第二行输出所需要花费的最少说服时间。否则输出<span lang="EN-US">NO</span>，并在第二行输出不能纳入网络的人编号中，编号最小的。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong>输入样例1：                       输出样例2：</strong></p>
<p>3                                                                            YES</p>
<p>2                                                                            110</p>
<p>1 10</p>
<p>2 100</p>
<p>2</p>
<p>1 3</p>
<p>2 3</p>
<p><strong>输入样例2：                       输出样例2：</strong></p>
<p>4                                                                           NO</p>
<p>2                                                                           3</p>
<p>1 100</p>
<p>4 200</p>
<p>2</p>
<p>1 2</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong>输出样例1：</strong></p>
<p>YES</p>
<p>110</p>
<p> </p>
<p><strong>输出样例2：</strong></p>
<p>NO</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的输入数据有n&lt;=10。</p>
<p>对于100%的输入数据有n&lt;=3000。</p>
</div>
</div>