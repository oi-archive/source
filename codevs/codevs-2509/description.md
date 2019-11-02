<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>The annual sailing race is organized on a round shape lake. There are N harbors, numbered from 1 to N <br>around the lake counterclockwise. The race consists of several stages, where each stage runs on a straight <br>line from one harbor to another, and the race track can only meet a harbor at most once. The organizers want <br>to create a race track that contains the highest possible number of stages. They must keep in mind that a <br>sailboat at a given harbor may only go to some specific harbors on a direct route. Fortunately, for each <br>harbor A they have the list of direct destinations from A, i.e. a list of other harbors to which a sailboat can go <br>on a straight line from A. Generally, the race track consists of non-intersecting stages, to avoid the collision <br>of sailboats. This year, however, a new technology is available, with which one crossing may be allowed if it <br>lies on the first stage. So if the race track starts at harbor S and the next harbor in the track is T then at most <br>one stage can cross the first stage S-T. The organizers may decide to allow a crossing like this, or rather <br>choose the classical design with non-intersecting stages.</p>
<p>Task <br>You are to write a program that computes a race track of the given type containing the highest possible <br>number of stages.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The first line of the input contains two integers, the first number N (1 ≤ N ≤ 500) is the number of harbors <br>and the second number k is the type of the required race track. If k is 0 then a classical track (without <br>crossings) is required, while if k is 1 then the track may contain at most one crossing, as specified above. <br>The next N lines contain the list of direct destinations from the harbors. The (i+1)th line contains the list for <br>harbor i, a space-separated list of integers, terminated by 0.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The first line of the output contains one integer M, the maximal number of stages that a race track of the <br />given type can contain. The second line contains the identifier number of the starting harbor of one such race <br />track. If there are multiple solutions, your program should output only one; it does not matter which one.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7 1 <br>5 0 <br>5 0 <br>7 0 <br>3 0 <br>4 0 <br>4 3 0 <br>2 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 <br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>In 40% of the test cases k=0. In 50% of the test cases N is at most 100. <br>No partial score is awarded for a correct first line.</p>
</div>
</div>