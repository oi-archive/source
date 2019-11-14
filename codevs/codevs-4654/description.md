<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><br>在一年前赢得了小镇的最佳草坪比赛后，FJ变得很懒，再也没有修剪过草坪。现在，<br>新一轮的最佳草坪比赛又开始了，FJ希望能够再次夺冠。<br><br>然而，FJ的草坪非常脏乱，因此，FJ只能够让他的奶牛来完成这项工作。FJ有N<br>(1 &lt;= N &lt;= 100,000)只排成一排的奶牛，编号为1...N。每只奶牛的效率是不同的，<br>奶牛i的效率为E_i(0 &lt;= E_i &lt;= 1,000,000,000)。<br><br>靠近的奶牛们很熟悉，因此，如果FJ安排超过K只连续的奶牛，那么，这些奶牛就会罢工<br>去开派对:)。因此，现在FJ需要你的帮助，计算FJ可以得到的最大效率，并且该方案中<br>没有连续的超过K只奶牛。<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><br>* 第一行：空格隔开的两个整数N和K<br><br>* 第二到N+1行：第i+1行有一个整数E_i<br><br><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><br/>* 第一行：一个值，表示FJ可以得到的最大的效率值。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2</p><p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p><br></p><p>输入解释：</p><p><br></p><p>FJ有5只奶牛，他们的效率为1，2，3，4，5。他们希望选取效率总和最大的奶牛，但是</p><p>他不能选取超过2只连续的奶牛</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><br></p><p>12</p><p><br></p><p>FJ可以选择出了第三只以外的其他奶牛，总的效率为1+2+4+5=12。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 &lt;= N &lt;= 100,000</p><p>0 &lt;= E_i &lt;= 1,000,000,000</p>
</div>
</div>