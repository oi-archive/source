<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有编号为1至n的n个同学一起去探险,现在把他们分成k个小组,每个小组完成一项探险任务。分组时,如果第i人与第j人分在同一组(i&lt;j),则他们之间的所有人(第i+1,i+2,…,j-1个)也必须在同一个小组中。</p>
<p>一个小组内所有人的体力和越小，途中可能越危险。为了确保每个同学的安全，要求分组时，使得所有小组中，体力和最小的那个小组的所有人的体力和尽量大。</p>
<p>依次告诉你每个人的体力，如何分组呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件explore.in的第1行有二个正整数n和k，互相之间以一个空格分隔。</p>
<p>第2行有n个正整数(互相以一个空格分隔)，表示n个人的体力值。其中第j个整数表示第j个人的体力值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件explore.out中只有1行,该行只有一个整数,表示最佳划分方案中，最弱的小组中，所有人的体力值之和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 2</p>
<p>5 2 1 6 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>分成2个小组时，第1小组由前4个人组成，第2小组由第5个人单独组成，此时最弱小组的体力和为9（其它划分方案时最弱小组的体力和都小于9）。</p>
</div>
</div>