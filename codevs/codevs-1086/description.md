<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">栈是计算机中经典的数据结构，简单的说，栈就是限制在一端进行插入删除操作的线性表。</p>
<p style="">栈有两种最重要的操作，即<span style="font-family: DejaVu Serif Condensed,serif;">pop</span>（从栈顶弹出一个元素）和<span style="font-family: DejaVu Serif Condensed,serif;">push</span>（将一个元素进栈）。</p>
<p style="">栈的重要性不言自明，任何一门数据结构的课程都会介绍栈。宁宁同学在复习栈的基本概念时，想到了一个书上没有讲过的问题，而他自己无法给出答案，所以需要你的帮忙</p>
<p style="">宁宁考虑的是这样一个问题：一个操作数序列，从<span style="font-family: DejaVu Serif Condensed,serif;">1</span>，<span style="font-family: DejaVu Serif Condensed,serif;">2</span>，一直到<span style="font-family: DejaVu Serif Condensed,serif;">n</span>（图示为<span style="font-family: DejaVu Serif Condensed,serif;">1</span>到<span style="font-family: DejaVu Serif Condensed,serif;">3</span>的情况），栈<span style="font-family: DejaVu Serif Condensed,serif;">A</span>的深度大于<span style="font-family: DejaVu Serif Condensed,serif;">n</span>。</p>
<p style="">现在可以进行两种操作，</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1.</span>将一个数，从操作数序列的头端移到栈的头端（对应数据结构栈的<span style="font-family: DejaVu Serif Condensed,serif;">push</span>操作）</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2. </span>将一个数，从栈的头端移到输出序列的尾端（对应数据结构栈的<span style="font-family: DejaVu Serif Condensed,serif;">pop</span>操作）</p>
<p style="">使用这两种操作，由一个操作数序列就可以得到一系列的输出序列，下图所示为由<span style="font-family: DejaVu Serif Condensed,serif;">1 2 3</span>生成序列<span style="font-family: DejaVu Serif Condensed,serif;">2 3 1</span>的过程。（原始状态如上图所示） 。</p>
<p style="">你的程序将对给定的<span style="font-family: DejaVu Serif Condensed,serif;">n</span>，计算并输出由操作数序列<span style="font-family: DejaVu Serif Condensed,serif;">1</span>，<span style="font-family: DejaVu Serif Condensed,serif;">2</span>，…，<span style="font-family: DejaVu Serif Condensed,serif;">n</span>经过操作可能得到的输出序列的总数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入文件只含一个整数<span style="font-family: DejaVu Serif Condensed,serif;">n</span>（<span style="font-family: DejaVu Serif Condensed,serif;">1≤n≤18</span>）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 0.74cm; margin-bottom: 0cm;">输出文件只有一行，即可能输出序列的总数目</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>当年官方数据有误，用int64(long long)可能会与答案不同，因为最后一个点答案溢出longint的。上传的数据是官方数据。</p>
</div>
</div>