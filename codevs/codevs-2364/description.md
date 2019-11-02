<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这里是广袤无垠的宇宙 <br>这里是一泻千里的银河 <br>这里是独一无二的太阳系 <br>这里是蔚蓝色的地球 <br>这里，就是这里，是富饶的中国大陆！ <br>这里是神奇的河北大地 <br>这里是美丽的唐山 <br>这里是神话般的唐山一中 <br>这里是 Akai曾经的教室 <br>黑板上还留有当年 Akai做过的数学作业，其实也并不是什么很困难的题目: <br>“ <br>给出一个一元 n 次方程： <br>a0 + a1x + a2x<sup>2</sup>+…+ anx<sup>n</sup>= 0 <br>求此方程的所有有理数解。</p>
<p>” <br>Akai 至今还深刻记得当年熬夜奋战求解的时光 <br>他甚至还能记得浪费了多少草稿纸 <br>但是却怎么也想不起来最后的答案是多少了 <br>你能帮助他么？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数 n。第二行 n+1 个整数，分别代表 a0 到an </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出一个整数 t，表示有理数解的个数 <br />接下来 t 行，每行表示一个解 <br />解以分数的形式输出，要求分子和分母互质，且分母必须是正整数 <br />特殊的，如果这个解是一个整数，那么直接把这个数输出 <br />等价的解只需要输出一次 <br />所有解按照从小到大的顺序输出</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 <br>-24 14 29 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 <br>-4 <br>-3/2 <br>2/3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 30%的数据，n&lt;=10 <br>对于 100%的数据，n &lt;= 100，|ai| &lt;= 2*10<sup>7</sup>，an≠ 0</p>
</div>
</div>