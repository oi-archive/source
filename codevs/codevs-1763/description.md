<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　在一个忍者的帮派里，一些忍者们被选中派遣给顾客，然后依据自己的工作获取报偿。</span><br><span>　　在这个帮派里，有一名忍者被称之为Master。除了Master以外，每名忍者都有且仅有一个上级。为保密，同时增强忍者们的领导力，所有与他们工作相关的指令总是由上级发送给他的直接下属，而不允许通过其他的方式发送。</span><br><span>　　现在你要招募一批忍者，并把它们派遣给顾客。你需要为每个被派遣的忍者支付一定的薪水，同时使得支付的薪水总额不超过你的预算。另外，为了发送指令，你需要选择一名忍者作为管理者，要求这个管理者可以向所有被派遣的忍者发送指令，在发送指令时，任何忍者（不管是否被派遣）都可以作为消息的传递人。管理者自己可以被派遣，也可以不被派遣。当然，如果管理者没有被派遣，你就不需要支付管理者的薪水。</span><br><span>　　你的目标是在预算内使顾客的满意度最大。这里定义顾客的满意度为派遣的忍者总数乘以管理者的领导力，其中每个忍者的领导力也是一定的。</span><br><span>　　写一个程序，给定每一个忍者i的上级B</span><sub>i</sub><span>，薪水C</span><sub>i</sub><span>，领导力L</span><sub>i</sub><span>，以及支付给忍者们的薪水总预算M，输出在预算内满足上述要求时顾客满意度的最大值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　第一行包含两个整数N和M，其中N表示忍者的个数，M表示薪水的总预算。</span><br><span>　　接下来N行描述忍者们的上级、薪水以及领导力。其中的第i行包含三个整数B</span><sub>i </sub><span>, C</span><sub>i </sub><span>, L</span><sub>i</sub><span>分别表示第i个忍者的上级，薪水以及领导力。Master满足B</span><sub>i</sub><span>= 0，并且每一个忍者的上级的编号一定小于自己的编号 B</span><sub>i</sub><span> &lt; i。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出一个数，表示在预算内顾客的满意度的最大值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5 4</span><br><span>0 3 3</span><br><span>1 3 5</span><br><span>2 2 2</span><br><span>1 2 4</span><br><span>2 3 1</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>6</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span><span>【样例解释】</span></span></p>
<p><span><span>　　如果我们选择编号为1的忍者作为管理者并且派遣编号为3和编号为4的忍者，薪水总和为4，没有超过总预算4。因为派遣了2个忍者并且管理者的领导力为3，用户的满意度为2 × 3 = 6，是可以得到的用户满意度的最大值。</span></span></p>
<p><span><br></span></p>
<p><span>【数据规模】</span></p>
<p><span>　　1 ≤ N ≤ 100,000 忍者的个数；</span><br><span>　　1 ≤ M ≤ 1,000,000,000 薪水总预算；</span><br><span>　　0 ≤ B</span><sub>i</sub><span> &lt; i 忍者的上级的编号；</span><br><span>　　1 ≤ C</span><sub>i</sub><span> ≤ M 忍者的薪水；</span><br><span>　　1 ≤ L</span><sub>i</sub><span> ≤ 1,000,000,000 忍者的领导力。</span><br><span>　　对于30%的数据，N ≤ 3000。</span></p>
<p><span><br></span></p>
<p><strong>(采用国内数据)</strong></p>
</div>
</div>