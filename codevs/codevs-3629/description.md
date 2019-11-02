<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">给定两个字符串A和B，你的任务是把两个字符串的所有字符消除掉，每次执行消除，你可以选取使用下列的其中一种方式：</span></p><p style=""><span style="">（1)<span style="font-family: 'Times New Roman';">      </span></span><span style="">消除A字符串当前的第一个字符，如果该字符为原来A串中的第i位，那么需要花费costA[i]的代价；</span></p><p style=""><span style="">(2)<span style="font-family: 'Times New Roman';">      </span></span><span style="">消除B字符串当前的第一个字符，如果该字符为原来B串中的第i位，那么需要花费costB[i]的代价；</span></p><p><span style="">  </span><span style="">（3)<span style="font-family: 'Times New Roman';">      </span></span><span style="">同时消除A字符串和B字符串的第一个字符，如果该字符为原来A串中的第i位和原来B串中的第j位，那么需要花费costAB[i][j]的代价。</span></p><p><span style="">    消除的总代价为每一步操作代价的总和，当然我们需要将总代价最小化。同时，当我们选择执行(1)操作的时候，我们可以选择对B串进行旋转（言下之意，就是将B串分成两部分，然后交换位置之后连在一起，如“yaouf”可以旋转成“oufya”）。</span></p><p style=""><span style="">现在，请问消除的最小总代价是多少？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">    第一行两个整数</span><span style="">M,N</span><span style="">。表示A串和B串的长度。</span></p><p><span style="">    </span><span style="">第二行M个整数，表示costA[1] 至 costA[M];</span></p><p><span style="">    </span><span style="">第三行N个整数，表示costB[1] 至 costB[N];</span></p><p><span style="">    </span><span style="">接下来M行，每行N个整数，第i行第j个数表示costAB[i][j]。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 28px;">输出一个整数，表示最小的总代价</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p><p>2 4 6 7</p><p>8 10 12 10</p><p>14 16 18 17</p><p>13 17 5 19</p><p>2 4 6 14</p><p>1 10 12 3<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>29<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%<span style="">的数据</span>,M,N&lt;=100</p><p>50%<span style="">的数据</span>,M,N&lt;=500</p><p>100%<span style="">的数据</span>,M,N&lt;=1000, <span style="">所有</span>cost<span style="">的数非负且不大于</span>1000</p><p><br></p>
</div>
</div>