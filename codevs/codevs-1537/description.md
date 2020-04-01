<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>巫妖王的天灾军团终于卷土重来，血色十字军组织了一支先锋军前往诺森德大陆对抗天灾军团，以及一切沾有亡灵气息的生物。孤立于联盟和部落的血色先锋军很快就遭到了天灾军团的重重包围，现在他们将主力只好聚集了起来，以抵抗天灾军团的围剿。可怕的是，他们之中有人感染上了亡灵瘟疫，如果不设法阻止瘟疫的扩散，很快就会遭到灭顶之灾。大领主阿比迪斯已经开始调查瘟疫的源头。原来是血色先锋军的内部出现了叛徒，这个叛徒已经投靠了天灾军团，想要将整个血色先锋军全部转化为天灾军团！无需惊讶，你就是那个叛徒。在你的行踪败露之前，要尽快完成巫妖王交给你的任务。</p>
<p> </p>
<p>军团是一个N行M列的矩阵，每个单元是一个血色先锋军的成员。感染瘟疫的人，每过一个小时，就会向四周扩散瘟疫，直到所有人全部感染上瘟疫。你已经掌握了感染源的位置，任务是算出血色先锋军的领主们感染瘟疫的时间，并且将它报告给巫妖王，以便对血色先锋军进行一轮有针对性的围剿。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：四个整数N，M，A，B，表示军团矩阵有N行M列。有A个感染源，B为血色敢死队中领主的数量。</p>
<p>接下来A行：每行有两个整数x，y，表示感染源在第x行第y列。</p>
<p>接下来B行：每行有两个整数x，y，表示领主的位置在第x行第y列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">第1至B行：每行一个整数，表示这个领主感染瘟疫的时间，输出顺序与输入顺序一致。如果某个人的位置在感染源，那么他感染瘟疫的时间为0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4 2 3</p>
<p>1 1</p>
<p>5 4</p>
<p>3 3</p>
<p>5 3</p>
<p>2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1</p>
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】</p>
<p>1&lt;=M,N&lt;=500</p>
<p>1&lt;=A,B&lt;=M*N</p>
</div>
</div>