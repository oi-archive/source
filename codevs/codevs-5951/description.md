<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'> 很多人都不知道， 奶牛们特别喜欢玩字谜游戏。 农夫约翰最近创造出了一个找单词的字谜游戏， 例如， 下面的这个字谜游戏：</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>      <img src="/source/codevs/codevs-5951/img/aHR0cDovL3ByYXllci5odXN0b2ouY29tL3VwbG9hZC9pbWFnZS8yMDE2MDcyMS8yMDE2MDcyMTE4NTQ1MF8zMTg0OC5wbmc=.png" style=""></p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>   作为奶牛， 他们只对单词“ MOO” 感兴趣， 这个单词可以出现在很多不同的位置， 比如水平排列、 垂直排列或者对角线排列（ 也就是 8 个方向） ， 上图中总共有 6 个“MOO” 出现了。<br style="">    农夫约翰自己也是一个字谜游戏的爱好者， 但是奶牛们不希望约翰比他们还要早去玩这个游戏， 于是他们用其他的字符分别代替了“M” 和“O” 这两个字符， 例如， “A” 也许被替换为“X” ， “B” 也许被替换为“A” ， 等等， 没有字符是自己替代自己的。 没有两个字符替代相同的字符（ 因为这个会引发混乱） 。不幸的是奶牛们忘记了他们替代的字符的关系， 现在请你帮助他们找出“MOO” 最多可以出现的次数</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>第一行是两个正整数 N 和 M， 表示字谜游戏的行和列的数量。</p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'>接下来 N 行， 每行 M 个字符， 表示字谜游戏中的字符。 字符都是由大写的“ A” 到“Z”组成的。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-size: 14px; background-color: rgb(239, 239, 239);">输出“MOO” 最多可能出现的次数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style='font-family: Menlo, Monaco, Consolas, "Courier New", monospace;'>4 6
TAMHGI
MMQVWM
QMMQSM
HBQUMQ</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'><br style="">样例中， 如果 M 和 O 分别被 Q 和 M 代替， 那么出现 QMM 的情况总共有 6 种， 这是最多的情况。<br style=""></p><p><br style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'></p><p style='font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;'><br style="">【 数据规模】<br style=""><br style="">1&lt;=N,M&lt;=50。</p><p><br></p>
</div>
</div>