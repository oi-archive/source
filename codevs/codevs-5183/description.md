<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>普通队列是常用的数据结构，然而，在人们素质不是很高的地方，人们排队时并不一定使用普通队列，而是使用「小组队列」。</p><p>真实情况往往是这样的：每个人都属于一个小组，并且该小组的人非常团结。每当一个人来排队的时候，他会先看一下前边有没有自己小组的成员，如果有的话，他会站到自己小组最后一个成员的后边，否则，他只有站到整个队列的最后。</p><p>现在，要求你编写一种数据结构来模拟小组队列，具体来说：</p><p>有 m 个小组， n 个元素，每个元素属于且仅属于一个小组。</p><p>支持以下操作：</p><p>·push ：使元素 x 进队，如果前边有 x 所属小组的元素，x 会排到自己小组最后一个元素的下一个位置，否则 x 排到整个队列最后的位置。</p><p>·pop  ：出队，弹出队头 <strong>并输出</strong> 出队元素，出队的方式和普通队列相同，即排在前边的元素先出队。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个正整数 n,m ，分别表示元素个数和小组个数，元素和小组均从0开始编号。</p><p>接下来一行 n 个非负整数 ai ，表示元素i所在的小组。</p><p>接下来一行一个正整数 T ，表示操作数。</p><p>接下来 T 行，每行为一个操作，命令格式已经在【题目描述】中陈述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个出队操作输出一行，为刚出队的元素。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p><p>0 0 1 1</p><p>6</p><p>push 2</p><p>push 0</p><p>push 3</p><p>pop</p><p>pop</p><p>pop</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>3</p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于前30%的数据，1&lt;=n&lt;=100，1&lt;=m&lt;=10，T&lt;=50。</p><p>对于100%的数据，1&lt;=n&lt;=100000, 1&lt;=m&lt;=300, T&lt;=100000，输入保证操作合法。</p>
</div>
</div>