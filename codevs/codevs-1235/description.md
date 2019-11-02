<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">假设一个试题库中有 n 道试题。每道试题都标明了所属类别。同一道题可能有多个类别</span><span style="">属性。现要从题库中抽取 m 道题组成试卷。并要求试卷包含指定类型的试题。试设计一个</span><span style="">满足要求的组卷算法。 </span><br><br><span style="">对于给定的组卷要求，计算满足要求的组卷方案</span>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第1行有2个正整数n和k (2 &lt;=k&lt;= 20, k&lt;=n&lt;= 1000) </span><span style="">k 表示题库中试题类型总数，n 表示题库中试题总数。第 2 行有 k 个正整数，第 i 个正整数</span><span style="">表示要选出的类型 i 的题数。这 k 个数相加就是要选出的总题数 m。接下来的 n 行给出了题</span><span style="">库中每个试题的类型信息。每行的第 1 个正整数 p 表明该题可以属于 p 类，接着的 p 个数是</span><span style="">该题所属的类型号。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: large;">第 i 行输出 &ldquo;i：&rdquo; 后接类</span><span style="font-size: large;">型 i 的题号。如果有多个满足要求的方案，只要输出 1 个方案。如果问题无解，则输出&ldquo;No </span><span style="font-size: large;">Solution!&rdquo;。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 </span><span style="">15 </span></p>
<p><span style="">3 3 4 </span></p>
<p><span style="">2 1 2 </span></p>
<p><span style="">1 3 </span></p>
<p><span style="">1 3 </span></p>
<p><span style="">1 3 </span></p>
<p><span style="">1 3 </span></p>
<p><span style="">3 1 2 3 </span></p>
<p><span style="">2 2 3 </span></p>
<p><span style="">2 1 3 </span></p>
<p><span style="">1 2 </span></p>
<p><span style="">1 2 </span></p>
<p><span style="">2 1 2 </span></p>
<p><span style="">2 1 3 </span></p>
<p><span style="">2 1 2 </span></p>
<p><span style="">1 1 </span></p>
<p><span style="">3 1 2 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1: 1 6 8  </span></p>
<p><span style="">2: 7 9 10  </span></p>
<p><span style="">3: 2 3 4 5</span></p>

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