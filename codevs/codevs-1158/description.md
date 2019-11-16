<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">尼克每天上班之前都连接上英特网，接收他的上司发来的邮件，这些邮件包含了尼克主管的部门当天要完成的全部任务，每个任务由一个开始时刻与一个持续时间构成。<br>    尼 克的一个工作日为N分钟，从第一分钟开始到第N分钟结束。当尼克到达单位后他就开始干活。如果在同一时刻有多个任务需要完成，尼克可以任选其中的一个来 做，而其余的则由他的同事完成，反之如果只有一个任务，则该任务必需由尼克去写成，假如某些任务开始时刻尼克正在工作，则这些任务也由尼克的同事完成。如 果某任务于第P分钟开始，持续时间为T分钟，则该任务将在第P+T-1分钟结束。<br>    写一个程序计算尼克应该如何选取任务，才能获得最大的空暇时间。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入数据第一行包含两个用空格隔开的整数N和K，1≤N≤10000，1≤K≤10000，N表示尼克的工作时间，单位为分，K表示任务总数。<br>    接下来共有K行，每一行有两个用空格隔开的整数P和T，表示该任务从第P分钟开始，持续时间为T分钟，其中1≤P≤N，1≤P+T-1≤N。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: large;">输出文件仅一行包含一个整数表示尼克可能获得的最大空暇时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">15 6<br>1 2<br>1 6<br>4 11<br>8 5<br>8 1<br>11 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>