<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    N位同学站成一排，音乐老师要请其中的(N-K)位同学出列，使得剩下的K位同学排成合唱队形。<br><br>    合唱队形是指这样的一种队形：设K位同学从左到右依次编号为1，2…，K，他们的身高分别为T1，T2，…，TK，  则他们的身高满足T1&lt;...&lt;Ti&gt;Ti+1&gt;…&gt;TK(1&lt;=i&lt;=K)。<br><br>    你的任务是，已知所有N位同学的身高，计算最少需要几位同学出列，可以使得剩下的同学排成合唱队形。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件chorus.in的第一行是一个整数N(2&lt;=N&lt;=100)，表示同学的总数。第一行有n个整数，用空格分隔，第i个整数Ti(130&lt;=Ti&lt;=230)是第i位同学的身高(厘米)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;&nbsp;输出文件chorus.out包括一行，这一行只包含一个整数，就是最少需要几位同学出列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8<br>186 186 150 200 160 130 197 220</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于50％的数据，保证有n&lt;=20；<br>对于全部的数据，保证有n&lt;=100。</p>
</div>
</div>