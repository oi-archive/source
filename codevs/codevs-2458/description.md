<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>         小Y最近遇到了一个棘手的问题。她有两项任务需要完成，其中第一项任务是重复操作1(<em>op</em><sub>1</sub>)<em>S</em><sub>1</sub>次，第二项任务是重复操作2(<em>op</em><sub>2</sub>)<em>S</em><sub>2</sub>次。为了完成这些任务，小 Y雇佣了<em>N</em>名工人。其中，第<em>i</em>个工人完成<em>op</em><sub>1</sub>所需时间为<em>T</em><sub>1,i</sub>，完成<em>op</em><sub>2</sub>所需时间为<em>T</em><sub>2,i</sub>。每个<em>op</em><sub>1</sub>和<em>op</em><sub>2</sub>都只能被一名工人完成，每名工人在任意时刻都只能做一项工作。</p>
<p>         所有的工人从第0秒开始工作。每当一个工人开始执行一项操作(<em>op</em><sub>1</sub>或<em>op</em><sub>2</sub>)，他必须一直执行下去直到完成而不能被打断。我们记第一项任务完成的时间为<em>E</em><sub>1</sub>，第二项任务完成的时间为<em>E</em><sub>2</sub>，你的任务就是安排这些工人的工作，使得<em>E</em><sub>1</sub>+<em>E</em><sub>2</sub>最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>         输入文件的第一行包含一个整数<em>T</em>，表示输入文件中数据的组数。</p>
<p>         每个测试数据的第一行包含三个整数<em>N</em> <em>S</em><sub>1</sub> <em>S</em><sub>2</sub>，含义如上文所述。</p>
<p>         接下来的<em>N</em>行每行包含两个整数<em>T</em><sub>1,I</sub>、<em>T</em><sub>2,i</sub>，分别表示第i个工人完成<em>op</em><sub>1</sub>和<em>op</em><sub>2</sub>所需的时间。</p>
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

<p>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;输出文件包含<em>T</em>行，每行只有一个整数，表示你找到的<em>E</em><sub>1</sub>+<em>E</em><sub>2</sub>的最小值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>         4</p>
<p> </p>
<p>1 2 3</p>
<p>10 20</p>
<p> </p>
<p>3 5 7</p>
<p>10 20</p>
<p>15 16</p>
<p>17 18</p>
<p> </p>
<p>4 3 6</p>
<p>10 12</p>
<p>8 9</p>
<p>16 11</p>
<p>13 20</p>
<p> </p>
<p>4 4 6</p>
<p>7 12</p>
<p>5 3</p>
<p>6 5</p>
<p>1000000 1000000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>       100</p>
<p>162</p>
<p>84</p>
<p>41</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>       100%的数据中，1&lt;=T&lt;=7 1&lt;=N&lt;=100 1&lt;=S1, S2&lt;=7 1&lt;=T1i, T2i&lt;=10<sup>6</sup></p>
</div>
</div>