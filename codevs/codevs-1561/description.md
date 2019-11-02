<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>汶川地震发生时，四川<span style="font-family: Times New Roman;">**</span><span style="">中学正在上课，一看地震发生，老师们立刻带领</span><span style="font-family: Times New Roman;">x</span><span style="">名学生逃跑，整个学校可以抽象地看成一个有向图，图中有</span><span style="font-family: Times New Roman;">n</span><span style="">个点，</span><span style="font-family: Times New Roman;">m</span><span style="">条边。</span><span style="font-family: Times New Roman;">1</span><span style="">号点为教室，</span><span style="font-family: Times New Roman;">n</span><span style="">号点为安全地带，每条边都只能容纳一定量的学生，超过楼就要倒塌，由于人数太多，校长决定让同学们分成几批逃生，只有第一批学生全部逃生完毕后，第二批学生才能从</span><span style="font-family: Times New Roman;">1</span><span style="">号点出发逃生，现在请你帮校长算算，每批最多能运出多少个学生，</span><span style="font-family: Times New Roman;">x</span><span style="">名学生分几批才能运完。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行<span style="font-family: Times New Roman;">3</span><span style="">个整数</span><span style="font-family: Times New Roman;">n,m,x(x&lt;2^31,n&lt;=200,m&lt;=2000)</span><span style="">；以下</span><span style="font-family: Times New Roman;">m</span><span style="">行，每行三个整数</span><span style="font-family: Times New Roman;">a,b,c</span><span style="">（</span><span style="font-family: Times New Roman;">a1,a&lt;&gt;b,0</span><span style="">描述一条边，分别代表从</span><span style="font-family: Times New Roman;">a</span><span style="">点到</span><span style="font-family: Times New Roman;">b</span><span style="">点有一条边，且可容纳</span><span style="font-family: Times New Roman;">c</span><span style="">名学生。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">两个整数，分别表示每批最多能运出多少个学生，<span style="font-family: Times New Roman;">x</span><span style="font-family: 宋体;">名学生分几批才能运完。如果无法到达目的地（</span><span style="font-family: Times New Roman;">n</span><span style="font-family: 宋体;">号点）则输出&ldquo;</span><span style="font-family: Times New Roman;">Orz&nbsp;Ni&nbsp;Jinan&nbsp;Saint&nbsp;Cow</span><span style="font-family: 宋体;">！&rdquo;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 7 7</p>
<p>1 2 1</p>
<p>1 4 2</p>
<p>2 3 1</p>
<p>4 5 1</p>
<p>4 3 1</p>
<p>3 6 2</p>
<p>5 6 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>题意澄清：</p>
<p>比如<br>1 2 100<br>2 3 1</p>
<p><br>100<span style="">个学生先冲到</span><span style="font-family: Cambria Math;">2</span><span style="">号点，然后</span><span style="font-family: Cambria Math;">1</span><span style="">个</span><span style="font-family: Cambria Math;">1</span><span style="">个慢慢沿</span><span style="font-family: Cambria Math;">2-3</span><span style="">边走过去</span></p>
<p>这样不行……</p>
</div>
</div>
</div>