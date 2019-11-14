<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>循环数是那些不包括0且没有重复数字的整数(比如81362)并且还应同时具有一个有趣的性质, 就像这个例子:</p>
<p>如果你从最左边的数字开始(在这个例子中是8)向右数最左边这个数(如果数到了最右边就回到最左边),你会停止在另一个新的数字(如果停在一个相同的数字上，这个数就不是循环数).就像: 8 1 3 6 2 从最左边接下去数8个数字: 1 3 6 2 8 1 3 6 所以下一个数字是6</p>
<p>重复这样做 (这次从“6”开始数6个数字) 并且你会停止在一个新的数字上: 2 8 1 3 6 2, 也就是2</p>
<p>再这样做 (这次数两个): 8 1</p>
<p>再一次 (这次一个): 3</p>
<p>又一次: 6 2 8 这时你回到了起点,在经过每个数字一次后回到起点的就是循环数。如果你经过每一个数字一次以后没有回到起点, 你的数字不是一个循环数。</p>
<p>给你一个数字 M (在1到9位之间), 找出第一个比 M大的循环数, 输出数据保证结果能用一个无符号长整型数装下。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>仅仅一行, 包括M</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅仅一行，输出第一个比M大的循环数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>81361</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>81362</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>