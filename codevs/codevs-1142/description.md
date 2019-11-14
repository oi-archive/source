<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某小学最近得到了一笔赞助，打算拿出其中一部分为学习成绩优秀的前5名学生发奖学金。期末，每个学生都有3门课的成绩：语文、数学、英语。先按总分从高到低排序，如果两个同学总分相同，再按语文成绩从高到低排序，如果两个同学总分和语文成绩都相同，那么规定学号小的同学排在前面，这样，每个学生的排序是唯一确定的。</p>
<p>任务：先根据输入的3门课的成绩计算总分，然后按上述规则排序，最后按排名顺序输出前5名学生的学号和总分。注意，在前5名同学中，每个人的奖学金都不相同，因此，你必须严格按上述规则排序。例如，在某个正确答案中，如果前两行的输出数据（每行输出两个数：学号、总分）是：</p>
<p>7 279</p>
<p>5 279</p>
<p>这两行数据的含义是：总分最高的两个同学的学号依次是7号、5号。这两名同学的总分都是279（总分等于输入的语文、数学、英语三科成绩之和），但学号为7的学生语文成绩更高一些。如果你的前两名的输出数据是：</p>
<p>5 279</p>
<p>7 279</p>
<p>则按输出错误处理，不能得分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>包含<em>n</em>+1行：</p>
<p>第1行为一个正整数<em>n</em>，表示该校参加评选的学生人数。</p>
<p>第2到<em>n</em>+1行，每行有3个用空格隔开的数字，每个数字都在0到100之间。第<em>j</em>行的3个数字依次表示学号为<em>j</em>-1的学生的语文、数学、英语的成绩。每个学生的学号按照输入顺序编号为1~<em>n</em>（恰好是输入数据的行号减1）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共有5行，每行是两个用空格隔开的正整数, 依次表示前5名学生的学号和总分。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>90 67 80</p>
<p>87 66 91</p>
<p>78 89 91</p>
<p>88 99 77</p>
<p>67 89 64</p>
<p>78 89 98</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6 265</p>
<p>4 264</p>
<p>3 258</p>
<p>2 244</p>
<p>1 237</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：各学生的总成绩各不相同</p>
<p>100%的数据满足：6&lt;=<em>n</em>&lt;=300</p>
</div>
</div>