<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在，你的任务是实现一个算法，模拟<strong>函数调用</strong>的流程。</p><p>我们会给出 n 个函数，它们被编号为[0, n)，给出每个函数所含的代码行数 l<sub>i</sub>，这些函数的调用和执行被以下命令控制：</p><p>·call：调用函数 i ，并停留在起始处，此时函数 i 成为当前函数。</p><p>·next：执行当前函数的下一行代码，如果这是当前函数的最后一行代码，那么返回。</p><p>·return：放弃执行当前函数的剩余代码，直接返回。</p><p>·info：输出正在调用中函数的数量。</p><p>我们认为只有call指令能够调用函数（即这些函数的执行过程中不会互相调用），只有next指令能够执行函数的代码（即代码不会自动执行）。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n，表示函数的数量。</p><p>第二行有n个正整数，给出了每个函数的代码行数l<sub>i</sub>。</p><p>第三行一个正整数m，表示操作的数量。</p><p>接下来m行，每行包含一个命令，命令格式已经在【题目描述】中陈述，输入保证命令合法。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个info指令，输出一行，每行为一个正整数，表示正在调用中函数的数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>2 6 1</p><p>7</p><p>call 0</p><p>next </p><p>info</p><p>call 1</p><p>return </p><p>next</p><p>info</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br></p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，n&lt;=1000, m&lt;=100000</p>
</div>
</div>