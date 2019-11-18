<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">一元 n 次多项式可用如下的表达式表示：</span><img height="90" src="/source/codevs/codevs-1150/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9VGZReUhOOUU=.do" style="" width="655"><span style="">数，请按照如下规定的格式要求输出该多项式： </span></p>
<p><span style="">1. 多项式中自变量为x，从左到右按照次数递减顺序给出多项式。 </span></p>
<p><span style="">2. 多项式中只包含系数不为0 的项。 </span></p>
<p><span style="">3. 如果多项式n 次项系数为正，则多项式开头不出现“+”号，如果多项式n 次项系 数为负，则多项式以“-”号开头。 </span></p>
<p><span style="">4. 对于不是最高次的项，以“+”号或者“-”号连接此项与前一项，分别表示此项 系数为正或者系数为负。紧跟一个正整数，表示此项系数的绝对值（如果一个高于0 次的项， 其系数的绝对值为1，则无需输出1）。如果x 的指数大于1，则接下来紧跟的指数部分的形 式为“x^b”，其中b 为x 的指数；如果x 的指数为1，则接下来紧跟的指数部分形式为“x”； 如果x 的指数为0，则仅需输出系数即可。</span></p>
<p><span style="">5. 多项式中，多项式的开头、结尾不含多余的空格。</span></p>
<p>一元 n 次多项式可用如下的表达式表示：1 011 f (x) a x a xn ... a x annn = + − + + +− ， ≠ 0 n a其中，ii a x 称为i 次项， i a 称为i 次项的系数。给出一个一元多项式各项的次数和系数，请按照如下规定的格式要求输出该多项式：1. 多项式中自变量为x，从左到右按照次数递减顺序给出多项式。2. 多项式中只包含系数不为0 的项。3. 如果多项式n 次项系数为正，则多项式开头不出现“+”号，如果多项式n 次项系数为负，则多项式以“-”号开头。4. 对于不是最高次的项，以“+”号或者“-”号连接此项与前一项，分别表示此项系数为正或者系数为负。紧跟一个正整数，表示此项系数的绝对值（如果一个高于0 次的项，其系数的绝对值为1，则无需输出1）。如果x 的指数大于1，则接下来紧跟的指数部分的形式为“x^b”，其中b 为x 的指数；如果x 的指数为1，则接下来紧跟的指数部分形式为“x”；如果x 的指数为0，则仅需输出系数即可。5. 多项式中，多项式的开头、结尾不含多余的空格。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>共有2 行</span></p>
<p><span>第一行 1 个整数，n，表示一元多项式的次数。 </span></p>
<p><span>第二行有 n+1 个整数，其中第i 个整数表示第n-i+1 次项的系数，每两个整数之间用空 格隔开。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>共1 行，按题目所述格式输出多项式。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>100 -1 1 -3 0 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>100x^5-x^4+x^3-3x^2+10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 ≤ n ≤ 100，多项式各次项系数的绝对值均不超过100。</p>
</div>
</div>