<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们在编程时，最关心的一个问题就是算法的时间复杂度。但是分析一个程序的复杂度是一项很困畦的工作，特别是在程序的风格不是很好的情况下。所以，专门研究算法的<span>SERKOI</span>小组决定开发出一个分析程序复杂度的软件。</p>
<p>由于这是一个全新的领域，所以<span>SERKOI</span>小组决定先从简单情况入手。假设程序只包含循环和顺序结构，而且程序的结构定义如下：</p>
<p><span>program </span>： ：<span> = begin </span>＜<span>statement</span>＞<span> end</span></p>
<p><span>statement </span>： ：<span> = 1oop x </span>＜<span>statement</span>＞<span> end | op x </span>＜<span>statement</span>＞<span> |</span></p>
<p><span>break </span>＜<span>statement</span>＞<span> | continue </span>＜<span>statement</span>＞<span> | </span>空语句</p>
<p>注意：</p>
<p><span>1.</span>一个程序都是以<span>begin</span>开始，以相应的<span>end</span>结束；</p>
<p><span>2.loop x </span>＜<span>statement</span>＞<span> end</span>表示其中的语句＜<span>Statement</span>＞重复执行<span>x</span>次；</p>
<p><span>3.op x</span>表示执行<span>x</span>个单位操作；</p>
<p><span>4.</span>上面两点中的<span>x</span>可以是一个正整数或<span>n</span>（程序复杂度多项式的唯一变量）；</p>
<p><span>5</span>．<span>break</span>语句的作用是跳出上一层循环，<span>continue</span>语句的作用是跳过这一层循环的其它语句，直接进入下一次循环。如果它们（<span>break</span>或<span>continue</span>）不在任一层循环中，则它们将被忽略。</p>
<p>你必须写一个程序，求出这个程序的复杂度，并以多项式的形式输出。</p>
<p>例如．下面程序的复杂度为<span>n^2</span>＋<span>2n </span>：</p>
<p><span>begin</span></p>
<p><span>op n</span></p>
<p><span>loop 3</span></p>
<p><span>op n</span></p>
<p><span>break</span></p>
<p><span>end</span></p>
<p><span>loop n</span></p>
<p><span>loop n</span></p>
<p><span>op l </span></p>
<p><span>continue</span></p>
<p><span>op n</span></p>
<p><span>end</span></p>
<p><span>end</span></p>
<p><span>end </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中包含一个完整的程序，每两条语句之间至少用一个空格或换行符隔开。循环的嵌套最多不超过<span>20</span>层，而且保证最终时间复杂度多项式每项的系数不超过<span>10^9</span>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>将计算出的时间复杂度多项式按降幂且数学书写的习惯方式写到输出文件中。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>begin loop n loop 3 loop n</span></p>
<p><span>op 20</span></p>
<p><span>end end end</span></p>
<p><span>loop n op 3 break end</span></p>
<p><span>loop n loop n</span></p>
<p><span>op l</span></p>
<p><span>break</span></p>
<p><span>end end</span></p>
<p><span>end</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>60n^2</span>＋<span>n</span>＋<span>3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>属于简单的CTSC题</p>
</div>
</div>