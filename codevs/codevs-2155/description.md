<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Mrs.Chen是一个很认真很称职的语文老师 ......<br>所以,当她看到学生作文里的人物关系描述得非常的麻烦的时候,她非常生气,于是宣布:凡是作文里有冗余关系的,一率罚抄出师表10次...同学们非常的恐惧,于是,每当他们写出一篇作文,都要拿来你这个语文兼OI天才这里,问你有没有冗余的关系 ...... 时间一久,你也烦了,于是就想写个程序来代劳 ...</p>
<p>现在这里有一篇作文,有n句描述人物关系的句子,描述了n个人的关系<br>每条句子的定义是这样的<br>X Y<br>它的意思是:X认识Y Y也认识X</p>
<p>现在要你求出文中冗余关系的数目.</p>
<p>注意: 假如A认识B,B认识C,则A也认识C</p>
<p>冗余关系的定义是指 : 即使没有这条关系,原图的所有关系照样成立.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行,两个整数,表示句子数量(n)，表示人数(m)。<br>接下来n行,每行两个数,意义在描述里已经说了.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数,表示冗余关系的数目.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br>1 2<br>1 3<br>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n,m&lt;=1000</p>
</div>
</div>