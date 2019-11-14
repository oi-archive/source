<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>傻逼和他的朋友2b，38喜欢玩一种数字游戏：他们按某种顺序在纸上写下</p><p>1～N(1&lt;=N&lt;=10)之间的所有数，然后把相邻的数字相加，得到一个比原数列少一项的数列。对新数列重复上述的操作，直到整个数列只剩一个数为止。N=4 的时候，整个游戏的流程可</p><p>能如下所示： </p><p>        3   1    2   4<br></p><p>          4   3    6<br></p><p>            7    9<br></p><p>               16  </p><p>    他们很快不满足于这种简单的游戏，于是他们玩起了另一个版本：对于给定的 N 以及最后剩下的数，求初始的数列。不幸的是，由于他们的数学学得不是很好，这个游戏对于他们来说是有些难度的。 请你写个程序来帮助三个神经病玩这个游戏，以保持他们在神经病人心中的地位。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输出为一行，包括 2个用空格隔开的整数：N 和这N 个数字经过运算后的最终结果。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第 1行: 输出一个完整包含 1～N的长度为N的数列，它经过若干次相邻数加和的运算后能够得到输入中要求的结果。如果有多个数列符合要求，输出字典序最小的一个。也就是说，数列中位置靠前的数字要尽量小。&nbsp;</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 16 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 1 2 4 </p><p>输出说明:  其他的数列经过以上运算，可能也能得到相同的结果，比如说 3 2 1 4，但所有符合条件的数字串中，3 1 2 4是字典序最小的一个。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>你猜猜看</p>
</div>
</div>