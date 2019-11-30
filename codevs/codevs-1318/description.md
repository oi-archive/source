<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你有一支由n名预备役士兵组成的部队，士兵从1到n编号，要将他们拆分<br>成若干特别行动队调入战场。出于默契的考虑，同一支特别行动队中队员的编号<br>应该连续，即为形如(i, i + 1, …, i + k)的序列。<br> <br>编号为i的士兵的初始战斗力为x<br>i ，一支特别行动队的初始战斗力x为队内<br>士兵初始战斗力之和，即x = xi+ xi+1+ … + xi+k。 <br>通过长期的观察，你总结出一支特别行动队的初始战斗力x将按如下经验公<br>式修正为x'：x' = ax2 + bx + c，其中a, b, c是已知的系数（a &lt; 0）。 <br>作为部队统帅，现在你要为这支部队进行编队，使得所有特别行动队修正后<br>战斗力之和最大。试求出这个最大和。 <br>例如，你有4名士兵，x1 = 2, x2 = 2, x3 = 3, x4 = 4。经验公式中的参数为a = –1, <br>b = 10, c = –20。此时，最佳方案是将士兵组成3个特别行动队：第一队包含士兵<br>1和士兵2，第二队包含士兵3，第三队包含士兵4。特别行动队的初始战斗力分<br>别为4, 3, 4，修正后的战斗力分别为4, 1, 4。修正后的战斗力和为9，没有其它<br>方案能使修正后的战斗力和更大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入由三行组成。第一行包含一个整数n，表示士兵的总数。第二行包含三<br>个整数a, b, c，经验公式中各项的系数。第三行包含n个用空格分隔的整数x<br>1, x2, …, xn，分别表示编号为1, 2, …, n的士兵的初始战斗力。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示所有特别行动队修正后战斗力之和的最大值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 <br>-1 10 -20 <br>2 2 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据中，n ≤ 1000； <br>50%的数据中，n ≤ 10,000； <br>100%的数据中，1 ≤ n ≤ 1,000,000，–5 ≤ a ≤ –1，|b| ≤ 10,000,000，|c| ≤ 10,000,000，1 ≤ xi≤ 100。</p>
</div>
</div>