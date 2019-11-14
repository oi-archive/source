<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>幼儿园里有</span><span style="font-family: 'Times New Roman';">N</span><span style="">个小朋友，</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="">老师现在想要给这些小朋友们分配糖果，要求每个小朋友都要分到糖果。但是小朋友们也有嫉妒心，总是会提出一些要求，比如小明不希望小红分到的糖果比他的多，于是在分配糖果的时候，</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="">需要满足小朋友们的</span><span style="font-family: 'Times New Roman';">K</span><span style="">个要求。幼儿园的糖果总是有限的，</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="">想知道他至少需要准备多少个糖果，才能使得每个小朋友都能够分到糖果，并且满足小朋友们所有的要求。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入的第一行是两个整数<span style="font-family: 'Times New Roman';">N</span><span style="">，</span><span style="font-family: 'Times New Roman';">K</span><span style="">。</span></span></p>
<p><span>接下来<span style="font-family: 'Times New Roman';">K</span><span style="">行，表示这些点需要满足的关系，每行</span><span style="font-family: 'Times New Roman';">3</span><span style="">个数字，</span><span style="font-family: 'Times New Roman';">X</span><span style="">，</span><span style="font-family: 'Times New Roman';">A</span><span style="">，</span><span style="font-family: 'Times New Roman';">B</span><span style="">。</span></span></p>
<p><span>如果<span style="font-family: 'Times New Roman';">X=1</span><span style="">， 表示第</span><span style="font-family: 'Times New Roman';">A</span><span style="">个小朋友分到的糖果必须和第</span><span style="font-family: 'Times New Roman';">B</span><span style="">个小朋友</span>分到的糖果一样多；</span></p>
<p><span>如果<span style="font-family: 'Times New Roman';">X=2</span><span style="">， </span></span><span>表示第<span style="font-family: 'Times New Roman';">A</span><span style="">个小朋友分到的糖果必须少于第</span><span style="font-family: 'Times New Roman';">B</span><span style="">个小朋友</span></span><span>分到的糖果</span><span>；</span></p>
<p><span>如果<span style="font-family: 'Times New Roman';">X=3</span><span style="">， </span></span><span>表示第<span style="font-family: 'Times New Roman';">A</span><span style="">个小朋友分到的糖果必须不少于第</span><span style="font-family: 'Times New Roman';">B</span><span style="">个小朋友</span></span><span>分到的糖果</span><span>；</span></p>
<p><span>如果<span style="font-family: 'Times New Roman';">X=4</span><span style="">， </span></span><span>表示第<span style="font-family: 'Times New Roman';">A</span><span style="">个小朋友分到的糖果必须多于第</span><span style="font-family: 'Times New Roman';">B</span><span style="">个小朋友</span></span><span>分到的糖果</span><span>；</span></p>
<p><span>如果<span style="font-family: 'Times New Roman';">X=5</span><span style="">， </span></span><span>表示第<span style="font-family: 'Times New Roman';">A</span><span style="">个小朋友分到的糖果必须不多于第</span><span style="font-family: 'Times New Roman';">B</span><span style="">个小朋友</span></span><span>分到的糖果；</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出一行，表示</span><span style="font-family: 'Times New Roman';">lxhgww</span><span style="font-family: 宋体;">老师至少需要准备的糖果数，如果不能满足小朋友们的所有要求，就输出</span><span style="font-family: 'Times New Roman';">-1</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>5 7</span><br><br><span> 1 1 2</span><br><br><span> 2 3 2</span><br><br><span> 4 4 1</span><br><br><span> 3 4 5</span><br><br><span> 5 4 5</span><br><br><span> 2 3 5</span><br><br><span> 4 5 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>11</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证 N&lt;=100</p>
<p> </p>
<p>对于100%的数据，保证 N&lt;=100000</p>
<p> </p>
<p>对于所有的数据，保证 K&lt;=100000，1&lt;=X&lt;=5，1&lt;=A, B&lt;=N</p>
</div>
</div>