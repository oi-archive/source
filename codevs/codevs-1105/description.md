<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="">在河上有一座独木桥，一只青蛙想沿着独木桥从河的一侧跳到另一侧。在桥上有一些石子，青蛙很讨厌踩在这些石子上。由于桥的长度和青蛙一次跳过的距离都是正整数，我们可以把独木桥上青蛙可能到达的点看成数轴上的一串整点：</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">0</span></span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span></span><span style=""><span style="">，</span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">……</span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">（其中</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">是桥的长度）。坐标为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">0</span></span></span></span><span style=""><span style="">的点表示桥的起点，坐标为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">的点表示桥的终点。青蛙从桥的起点开始，不停的向终点方向跳跃。一次跳跃的距离是</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">S</span></span></span></span><span style=""><span style="">到</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">T</span></span></span></span><span style=""><span style="">之间的任意正整数（包括</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">S,T</span></span></span></span><span style=""><span style="">）。当青蛙跳到或跳过坐标为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">的点时，就算青蛙已经跳出了独木桥。</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span></span><span style=""><span style="">题目给出独木桥的长度</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">，青蛙跳跃的距离范围</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">S,T</span></span></span></span><span style=""><span style="">，桥上石子的位置。你的任务是确定青蛙要想过河，最少需要踩到的石子数。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">输入</span></span><span style=""><span style="">第一行有一个正整数</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">（</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">10<sup>9</sup></span></span></span></span><span style=""><span style="">），表示独木桥的长度。第二行有三个正整数</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">S</span></span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">T</span></span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">，分别表示青蛙一次跳跃的最小距离，最大距离，及桥上石子的个数，其中</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">S</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">T</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">10</span></span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">100</span></span></span></span><span style=""><span style="">。第三行有</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">个不同的正整数分别表示这</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">个石子在数轴上的位置（数据保证桥的起点和终点处没有石子）。所有相邻的整数之间用一个空格隔开。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;"><span style="color: #000000;"><span style="font-size: x-small;">输出</span></span><span style="color: #000000;"><span style="font-size: x-small;">只包括一个整数，表示青蛙过河最少需要踩到的石子数。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">10</span></span></span><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">2</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;"> 3 </span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">5</span></span></span><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">2</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;"> 3 </span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">5 </span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">6 </span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">7</span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据规模</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span></span><span style=""><span style="">对于</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">30%</span></span></span></span><span style=""><span style="">的数据，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">10000</span></span></span></span><span style=""><span style="">；</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br><br></span></span></span></span><span style=""><span style="">对于全部的数据，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">10<sup>9</sup></span></span></span></span><span style=""><span style="">。</span></span></p>
</div>
</div>