<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>密码箱终于被打开了，里面真的有一张古代的藏宝图，这是一个古代君主留下来的宝藏，藏在一个至今没有人发现的地下宫殿中，要取得宝藏必须破解重重机关。小可可毫无畏惧，作为他的好朋友，你们就这样开始了寻宝旅程。经过千辛万苦，你们来到了地下宫殿的入口，遇到了第一个麻烦。宫殿的大门怎么都无法打开。小可可仔细观察以后发现，大门的左半扇门上有一些数字，像一个n*n的矩阵般排列，右半扇门对应的位置上也有同样的n*n数字排列，不过数字均为0，这些0都可以通过机关变成其他的数字，甚至是负数，但是排列方式不会变。小可可仔细研究了藏宝图，发现要打开这扇门必须要将右半扇门上的数字按照一定的规律进行改变。若假设左边n*n矩阵为A，改变后的右边n*n矩阵为B，这个规律就是：</p>
<p>它们的乘积C矩阵 C=A*B=E<sub>n</sub></p>
<p>其中E<sub>n</sub>为：E<sub>i,j</sub>=0（若i不等于j），E<sub>i,j</sub>=1（若i等于j）。即，Ｂ为Ａ的逆矩阵。</p>
<p>你能帮助小可可打开这扇门吗？</p>
<p> </p>
<p><span style="text-decoration: underline;">输入</span>：输入文件的第一行为一个整数n (1&lt;=n&lt;=200)<em>.</em></p>
<p>以下n行，每行n个数，按照行主序给出A的每个元素，即：</p>
<p>A<sub>1,1</sub>, A<sub>1,2</sub>, ……，A<sub>1,n</sub>，</p>
<p>A<sub>2,1</sub>, A<sub>2,2</sub>, ……，A<sub>2,n</sub>，</p>
<p>……</p>
<p>A<sub>n,1</sub>, A<sub>n,2</sub>, ……，A<sub>n,n</sub>.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为一个整数n (1&lt;=n&lt;=200)<em>.</em></p>
<p>以下n行，每行n个数，按照行主序给出A的每个元素，即：</p>
<p>A<sub>1,1</sub>, A<sub>1,2</sub>, ……，A<sub>1,n</sub>，</p>
<p>A<sub>2,1</sub>, A<sub>2,2</sub>, ……，A<sub>2,n</sub>，</p>
<p>……</p>
<p>A<sub>n,1</sub>, A<sub>n,2</sub>, ……，A<sub>n,n</sub>.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件为n行，每行n个整数，且在-2,000,000,000与2,000,000,000之间，每两个相邻的数用一个空格隔开，即按照行主序表示的矩阵B。</p>
<p>输入数据保证这个矩阵B存在，且B的每个元素为一个整数，并且在-2,000,000,000与2,000,000,000之间。</p>
<p>特别提示：由于测试采取文件比对方式，所以这里约定，如果结果中某个数为0，则应输出0，而不是-0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 -1 1</p>
<p>0 1 2</p>
<p>1 0 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 4 -3</p>
<p>2 3 -2</p>
<p>-1 -1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>