<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某天WJMZBMR学习了一个神奇的算法：树的点分治！<br>这个算法的核心是这样的：<br>消耗时间=0<br>Solve(树 a)<br> 消耗时间 += a 的 大小<br> 如果 a 中 只有 1 个点<br> 退出<br> 否则在a中选一个点x，在a中删除点x<br> 那么a变成了几个小一点的树，对每个小树递归调用Solve<br>我们注意到的这个算法的时间复杂度跟选择的点x是密切相关的。<br>如果x是树的重心，那么时间复杂度就是O(nlogn)<br>但是由于WJMZBMR比较傻逼，他决定随机在a中选择一个点作为x！<br>Sevenkplus告诉他这样做的最坏复杂度是O(n^2)<br>但是WJMZBMR就是不信&gt;_&lt;。。。<br>于是Sevenkplus花了几分钟写了一个程序证明了这一点。。。你也试试看吧^_^<br>现在给你一颗树，你能告诉WJMZBMR他的傻逼算法需要的期望消耗时间吗？（消耗时间按在Solve里面的那个为标准）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示树的大小<br>接下来n-1行每行两个数a,b，表示a和b之间有一条边<br>注意点是从0开始标号的</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个浮点数表示答案<br />四舍五入到小数点后4位<br />如果害怕精度跪建议用long double或者extended</p>
<p>(由于没有SpecialJudge功能，请强制输出4位小数)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>0 1<br>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5.6667</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p>
<p>测试点<br>1..3:n&lt;=20<br>4..5:n&lt;=30<br>6..7:n&lt;=5000<br>8..9:n&lt;=30000且树直径小于1100<br>10：n&lt;=30000</p>
<p>(Wikioi的评测姬好神，Std和最快都是不到1s，所以时限缩到2s)</p>
<p> </p>
<p>【卖萌向】</p>
<p>其实跟点分治没什么大关系呢。。。真的吗？</p>
<p> </p>
<p>【来源】</p>
<p>我们都爱GYZ摸你赛 Problem B Normal</p>
</div>
</div>