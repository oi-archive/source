<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John 养了N(1&lt;=N&lt;=50,000)头牛，她们已经按1~N 依次编上了号。FJ 所不知道的是，他的所有牛都梦想着从农场逃走，去参加马戏团的演出。可奶牛们很快发现她们那笨拙的蹄子根本无法在钢丝或晃动的的秋千上站稳（她们还尝试过把自己装在大炮里发射出去，但可想而知，结果是悲惨的）。最终，她们决定练习一种最简单的杂技：把所有牛都摞在一起，比如说,第一头牛站在第二头的身上，同时第二头牛又站在第三头牛的身上...最底下的是第N 头牛。每头牛都有自己的体重以及力量， 编号为i 的奶牛的体重为W_i(1&lt;=W_i&lt;=10,000)，力量为S_i(1&lt;=S_i&lt;=1,000,000,000)。当某头牛身上站着另一些牛时它就会在一定程度上被压扁，我们不妨把它被压扁的程度叫做它的压扁指数。对于任意的牛，她的压扁指数等于摞在她上面的所有奶牛的总重（当然不包括她自己）减去它的力量。奶牛们按照一定的顺序摞在一起后，她们的总压扁指数就是被压得最扁的那头奶牛的压扁指数。你的任务就是帮助奶牛们找出一个摞在一起的顺序，使得总压扁指数最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>Line 1: A single line with the integer N.<br>Lines 2..N+1: Line i+1 describes cow i with two space-separated integers, W_i and S_i.</p>
<p>第一行:一个正整数N</p>
<p>第二只地N+1行：两个正整数，为Wi和Si.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Line 1: A single integer, giving the largest risk of all<br />the cows in any optimal ordering that minimizes the risk.</p>
<p>一个表示总压扁指数最小的正整数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>10 3<br>2 5<br>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】<br>把重为10的奶牛放在底部。它将支撑其余两头牛，所以它的风险是2+3-3=2。其他两头牛<br>风险比它低。</p>
</div>
</div>