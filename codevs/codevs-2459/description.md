<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>         奶酪店里最近出现了<em>m</em>只老鼠！它们的目标就是把生产出来的所有奶酪都吃掉。奶酪店中一天会生产<em>n</em>块奶酪，其中第<em>i</em>块的大小为<em>p<sub>i</sub></em>，会在第<em>r<sub>i</sub></em>秒被生产出来，并且必须在第<em>d<sub>i</sub></em>秒之前将它吃掉。第<em>j</em>只老鼠吃奶酪的速度为<em>s<sub>j</sub></em>，因此如果它单独吃完第<em>i</em>快奶酪所需的时间为<em>p<sub>i</sub></em>/<em>s<sub>j</sub></em>。老鼠们吃奶酪的习惯很独特，具体来说：</p>
<p>(1)     在任一时刻，一只老鼠最多可以吃一块奶酪；</p>
<p>(2)     在任一时刻，一块奶酪最多被一只老鼠吃。</p>
<p>         由于奶酪的保质期常常很短，为了将它们全部吃掉，老鼠们需要使用一种神奇的魔法来延长奶酪的保质期。将奶酪的保质期延长<em>T</em>秒是指所有的奶酪的<em>d<sub>i</sub></em>变成<em>d<sub>i</sub></em>+T。同时，使用魔法的代价很高，因此老鼠们希望找到最小的<em>T</em>使得可以吃掉所有的奶酪。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>         输入文件的第一行包含一个整数<em>K</em>，表示输入文件中数据的组数。</p>
<p>         每组数据的第一行包含两个整数<em>n</em>和<em>m</em>，分别表示奶酪和老鼠的数量。接下来的<em>n</em>行每行包含三个整数<em>p<sub>i</sub></em>,<em>r<sub>i</sub></em>,<em>d<sub>i</sub></em>。最后<em>m</em>行每行包含一个整数，表示<em>s<sub>j</sub></em>。<em>p<sub>i</sub></em>,<em>r<sub>i</sub></em>,<em>d<sub>i</sub></em>,<em>s<sub>j</sub></em>的含义如上文所述。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;输出文件中包含<em>K</em>行，每行包含一个实数，表示你找到的最小的<em>T</em>。你的答案和标准答案的<em><span style="text-decoration: underline;">绝对误差</span></em>不应超过。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>         2</p>
<p>         2 2</p>
<p>         13 0 4</p>
<p>         10 1 3</p>
<p>         4</p>
<p>         2</p>
<p>         1 1</p>
<p>         1 0 2</p>
<p>         1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>         0.5</p>
<p>         0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">100%的数据中，1&lt;=K&lt;=5 1&lt;=n, m&lt;=30 1&lt;=pi&lt;=10<sup>5 </sup> 0&lt;=ri&lt;di&lt;=10<sup>7</sup> 1&lt;=si&lt;=10<sup>5</sup></span></p>
</div>
</div>