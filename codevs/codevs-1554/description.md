<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Matrix67<span style="">要在下个月交给老师</span><span style="font-family: Times New Roman;">n</span><span style="">篇论文，论文的内容可以从</span><span style="font-family: Times New Roman;">m</span><span style="">个课题中选择。由于课题数有限，</span><span style="font-family: Times New Roman;">Matrix67</span><span style="">不得不重复选择一些课题。完成不同课题的论文所花的时间不同。具体地说，对于某个课题</span><span style="font-family: Times New Roman;">i</span><span style="">，若</span><span style="font-family: Times New Roman;">Matrix67</span><span style="">计划一共写</span><span style="font-family: Times New Roman;">x</span><span style="">篇论文，则完成该课题的论文总共需要花费</span><span style="font-family: Times New Roman;">Ai*x^Bi</span><span style="">个单位时间（系数</span><span style="font-family: Times New Roman;">Ai</span><span style="">和指数</span><span style="font-family: Times New Roman;">Bi</span><span style="">均为正整数）。给定与每一个课题相对应的</span><span style="font-family: Times New Roman;">Ai</span><span style="">和</span><span style="font-family: Times New Roman;">Bi</span><span style="">的值，请帮助</span><span style="font-family: Times New Roman;">Matrix67</span><span style="">计算出如何选择论文的课题使得他可以花费最少的时间完成这</span><span style="font-family: Times New Roman;">n</span><span style="">篇论文。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个用空格隔开的正整数<span style="font-family: Times New Roman;">n</span><span style="">和</span><span style="font-family: Times New Roman;">m</span><span style="">，分别代表需要完成的论文数和可供选择的课题数。 </span></p>
<p>以下<span style="font-family: Times New Roman;">m</span><span style="">行每行有两个用空格隔开的正整数。其中，第</span><span style="font-family: Times New Roman;">i</span><span style="">行的两个数分别代表与第</span><span style="font-family: Times New Roman;">i</span><span style="">个课题相对应的时间系数</span><span style="font-family: Times New Roman;">Ai</span><span style="">和指数</span><span style="font-family: Times New Roman;">Bi</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出完成<span style="font-family: Calibri;">n</span><span style="font-family: 宋体;">篇论文所需要耗费的最少时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 3</p>
<p>2 1</p>
<p>1 2</p>
<p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>19</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p>
<p>4<span style="">篇论文选择课题一，</span><span style="font-family: Times New Roman;">5</span><span style="">篇论文选择课题三，剩下一篇论文选择课题二，总耗时为</span><span style="font-family: Times New Roman;">2*4^1+1*1^2+2*5^1=8+1+10=19</span><span style="">。可以证明，不存在更优的方案使耗时小于</span><span style="font-family: Times New Roman;">19</span><span style="">。</span></p>
<p>【数据规模与约定】</p>
<p>对于<span style="font-family: Times New Roman;">30%</span><span style="">的数据，</span><span style="font-family: Times New Roman;">n&lt;=10,m&lt;=5</span><span style="">； </span></p>
<p>对于<span style="font-family: Times New Roman;">100%</span><span style="">的数据，</span><span style="font-family: Times New Roman;">n&lt;=200</span><span style="">，</span><span style="font-family: Times New Roman;">m&lt;=20</span><span style="">，</span><span style="font-family: Times New Roman;">Ai&lt;=100</span><span style="">，</span><span style="font-family: Times New Roman;">Bi&lt;=5</span><span style="">。</span></p>
</div>
</div>