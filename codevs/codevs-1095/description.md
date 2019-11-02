<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""> 人类终于登上了火星的土地并且见到了神秘的火星人。人类和火星人都无法理解对方的语言，但是我们的科学家发明了一种用数字交流的方法。这种交流方法是这样的，首先，火星人把一个非常大的数字告诉人类科学家，科学家破解这个数字的含义后，再把一个很小的数字加到这个大数上面，把结果告诉火星人，作为人类的回答。</p>
<p style="">火星人用一种非常简单的方式来表示数字——掰手指。火星人只有一只手，但这只手上有成千上万的手指，这些手指排成一列，分别编号为<span style="font-family: DejaVu Serif Condensed,serif;">1</span>，<span style="font-family: DejaVu Serif Condensed,serif;">2</span>，<span style="font-family: DejaVu Serif Condensed,serif;">3<span style="">……</span></span>。火星人的任意两根手指都能随意交换位置，他们就是通过这方法计数的。</p>
<p style="">一个火星人用一个人类的手演示了如何用手指计数。如果把五根手指——拇指、食指、中指、无名指和小指分别编号为<span style="font-family: DejaVu Serif Condensed,serif;">1</span>，<span style="font-family: DejaVu Serif Condensed,serif;">2</span>，<span style="font-family: DejaVu Serif Condensed,serif;">3</span>，<span style="font-family: DejaVu Serif Condensed,serif;">4</span>和<span style="font-family: DejaVu Serif Condensed,serif;">5</span>，当它们按正常顺序排列时，形成了<span style="font-family: DejaVu Serif Condensed,serif;">5</span>位数<span style="font-family: DejaVu Serif Condensed,serif;">12345</span>，当你交换无名指和小指的位置时，会形成<span style="font-family: DejaVu Serif Condensed,serif;">5</span>位数<span style="font-family: DejaVu Serif Condensed,serif;">12354</span>，当你把五个手指的顺序完全颠倒时，会形成<span style="font-family: DejaVu Serif Condensed,serif;">54321</span>，在所有能够形成的<span style="font-family: DejaVu Serif Condensed,serif;">120</span>个<span style="font-family: DejaVu Serif Condensed,serif;">5</span>位数中，<span style="font-family: DejaVu Serif Condensed,serif;">12345</span>最小，它表示<span style="font-family: DejaVu Serif Condensed,serif;">1</span>；<span style="font-family: DejaVu Serif Condensed,serif;">12354</span>第二小，它表示<span style="font-family: DejaVu Serif Condensed,serif;">2</span>；<span style="font-family: DejaVu Serif Condensed,serif;">54321</span>最大，它表示<span style="font-family: DejaVu Serif Condensed,serif;">120</span>。下表展示了只有<span style="font-family: DejaVu Serif Condensed,serif;">3</span>根手指时能够形成的<span style="font-family: DejaVu Serif Condensed,serif;">6</span>个<span style="font-family: DejaVu Serif Condensed,serif;">3</span>位数和它们代表的数字：</p>
<p style="">三进制数</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">123</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">132</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">213</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">231</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">312</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">321</span></p>
<p style=""> </p>
<p style="">代表的数字</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">4</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">5</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">6<br></span></p>
<p style="">现在你有幸成为了第一个和火星人交流的地球人。一个火星人会让你看他的手指，科学家会告诉你要加上去的很小的数。你的任务是，把火星人用手指表示的数与科学家告诉你的数相加，并根据相加的结果改变火星人手指的排列顺序。输入数据保证这个结果不会超出火星人手指能表示的范围。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入包括三行，第一行有一个正整数<span style="font-family: DejaVu Serif Condensed,serif;">N</span>，表示火星人手指的数目（<span style="font-family: DejaVu Serif Condensed,serif;">1 &lt;= N &lt;= 10000</span>）。第二行是一个正整数<span style="font-family: DejaVu Serif Condensed,serif;">M</span>，表示要加上去的小整数（<span style="font-family: DejaVu Serif Condensed,serif;">1 &lt;= M &lt;= 100</span>）。下一行是<span style="font-family: DejaVu Serif Condensed,serif;">1</span>到<span style="font-family: DejaVu Serif Condensed,serif;">N</span>这<span style="font-family: DejaVu Serif Condensed,serif;">N</span>个整数的一个排列，用空格隔开，表示火星人手指的排列顺序。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">输出只有一行，这一行含有<span style="font-family: DejaVu Serif Condensed,serif;">N</span>个整数，表示改变后的火星人手指的排列顺序。每两个相邻的数中间用一个空格分开，不能有多余的空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>3</p>
<p>1 2 3 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 2 4 5 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">【数据规模】</p>
<p style="">对于<span style="font-family: DejaVu Serif Condensed,serif;">30%</span>的数据，<span style="font-family: DejaVu Serif Condensed,serif;">N&lt;=15</span>；</p>
<p style="">对于<span style="font-family: DejaVu Serif Condensed,serif;">60%</span>的数据，<span style="font-family: DejaVu Serif Condensed,serif;">N&lt;=50</span>；</p>
<p style="">对于全部的数据，<span style="font-family: DejaVu Serif Condensed,serif;">N&lt;=10000</span>；</p>
<p style=""> </p>
</div>
</div>