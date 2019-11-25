<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>上午的训练结束了，THU ACM小组集体去吃午餐，他们一行N人来到了著名的十食堂。这里有两个打饭的窗口，每个窗口同一时刻只能给一个人打饭。由于每个人的口味（以及胃口）不同，所以他们要吃的菜各有不同，打饭所要花费的时间是因人而异的。另外每个人吃饭的速度也不尽相同，所以吃饭花费的时间也是可能有所不同的。</p>
<p>THU ACM小组的吃饭计划是这样的：先把所有的人分成两队，并安排好每队中各人的排列顺序，然后一号队伍到一号窗口去排队打饭，二号队伍到二号窗口去排队打饭。每个人打完饭后立刻开始吃，所有人都吃完饭后立刻集合去六教地下室进行下午的训练。</p>
<p>现在给定了每个人的打饭时间和吃饭时间，要求安排一种最佳的分队和排队方案使得所有人都吃完饭的时间尽量早。</p>
<p>假设THU ACM小组在时刻0到达十食堂，而且食堂里面没有其他吃饭的同学（只有打饭的师傅）。每个人必须而且只能被分在一个队伍里。两个窗口是并行操作互不影响的，而且每个人打饭的时间是和窗口无关的，打完饭之后立刻就开始吃饭，中间没有延迟。</p>
<p>现在给定N个人各自的打饭时间和吃饭时间，要求输出最佳方案下所有人吃完饭的时刻。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数N，代表总共有N个人。</p>
<p>以下N行，每行两个整数 A<sub>i</sub>，B<sub>i</sub>。依次代表第i个人的打饭时间和吃饭时间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数T，代表所有人吃完饭的最早时刻。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>2 2</p>
<p>7 7</p>
<p>1 3</p>
<p>6 4</p>
<p>8 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>所有输入数据均为不超过200的正整数。</p>
</div>
</div>