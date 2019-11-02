<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一共 n × m 个硬币，摆成 n × m 的长方形。dongdong 和 xixi 玩一个游戏，每次可以选择一个连通块，并把其中的硬币全部翻转，但是需要满足存在一个硬币属于这个连通块并且所有其他硬币都在它的左上方 (可以正左方也可以正上方)，并且这个硬币是从反面向上翻成正面向上。dongdong 和 xixi 轮流操作。如果某一方无法操作，那么他 (她) 就输了。dongdong 先进行第一步操作，假设双方都采用最优策略。问 dongdong 是否有必胜策略。<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数 T，表示他们一共玩 T 局游戏。接下来是 T 组游戏描述。每组游戏第一行两个数 n;m，接下来 n 行每行 m 个字符，第 i 行第 j 个字符如果是 “H” 表示第 i 行第 j 列的硬币是正面向上，否则是反面向上。第 i 行 j 列的左上方是指行不超过 i 并且列不超过 j 的区域。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每局游戏，输出一行。如果 dongdong 存在必胜策略则输出 &ldquo;-_-&rdquo;(不含引号) 否则输出 &ldquo;=_=&rdquo;(不含引号)。(注意输出的都是半角符号，即三个符号ASCII 码分别为 45,61,95)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>2 3<br>HHH<br>HHH<br>2 3<br>HHH<br>TTH<br>2 1<br>T<br>H</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>=_=<br>-_-<br>-_-</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 40% 的数据，满足 1 ≤ n;m ≤ 5。<br>对于 100% 的数据，满足 1 ≤ n;m ≤ 100，1 ≤ T ≤ 50。</p>
</div>
</div>