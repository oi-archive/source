<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个Byteland上有一副非常有名的图画需要被封存。这个作品需要在2个实验室进行处理。这个处理过程被分为许多步骤。对于每个步骤，我们知道它必须要在哪个实验室进行。</p>
<p>在两个实验室之间运输这些这些美丽但又易碎的画会带来额外的风险，因此这个运输的过程需要尽可能的被避免。理想情况下所有的工作都会在第一个实验室做完，然后剩下的在另一个实验室完成，<strong>但是有些步骤必须在另一步骤完成之后才能完成</strong>。你的任务是找到一个工作的顺序，让这个被运输的过程最少。输出需要运输的次数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行N和M，代表着N个步骤，和M个先后关系。下面一行N个数字，第I个数字是1或2，代表了第I个工作需要在哪个实验室完成，下面M行I,J，代表了第I个工作必须在第J个工作前完成。</p>
<p>你可以认为这个题目必有解</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出最少需要的运输次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6</p>
<p>1 2 1 2 1</p>
<p>1 2</p>
<p>1 3</p>
<p>2 4</p>
<p>3 4</p>
<p>2 5</p>
<p>3 5</p>

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
<p>30%数据保证n&lt;=5。</p>
<p>100%数据中n&lt;=100000，m&lt;=1000000。</p>
</div>
</div>