<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="">某校大门外长度为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">的马路上有一排树，每两棵相邻的树之间的间隔都是</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span></span><span style=""><span style="">米。我们可以把马路看成一个数轴，马路的一端在数轴</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">0</span></span></span></span><span style=""><span style="">的位置，另一端在</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">的位置；数轴上的每个整数点，即</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">0</span></span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">2</span></span></span></span><span style=""><span style="">，</span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">……</span></span></span><span style=""><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">，都种有一棵树。</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span></span><span style=""><span style="">由于马路上有一些区域要用来建地铁。这些区域用它们在数轴上的起始点和终止点表示。已知任一区域的起始点和终止点的坐标都是整数，区域之间可能有重合的部分。现在要把这些区域中的树（包括区域端点处的两棵树）移走。你的任务是计算将这些树都移走后，马路上还有多少棵树。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">输入</span></span><span style=""><span style="">第一行有两个整数</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">（</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">10000</span></span></span></span><span style=""><span style="">）和</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">（</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">1</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">&lt;=</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">100</span></span></span></span><span style=""><span style="">），</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">代表马路的长度，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">代表区域的数目，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">L</span></span></span></span><span style=""><span style="">和</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">之间用一个空格隔开。接下来的</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">M</span></span></span></span><span style=""><span style="">行每行包含两个不同的整数，用一个空格隔开，表示一个区域的起始点和终止点的坐标。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;"><span style="color: #000000;"><span style="font-size: x-small;">输出</span></span><span style="color: #000000;"><span style="font-size: x-small;">包括一行，这一行只包含一个整数，表示马路上剩余的树的数目。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">500 </span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">3</span></span></span><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br><br></span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">150 </span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">300</span></span></span><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br><br></span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">100</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;"> 200</span></span></span><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br><br></span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">470</span></span></span><span style=""><span style=""><span style="font-family: Verdana,sans-serif;"> 471</span></span></span><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br><br><br></span></span></span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style=""><span style="font-family: Verdana,sans-serif;">298</span></span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">【数据规模】</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span></span><span style=""><span style="">对于</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;">20%</span></span></span></span><span style=""><span style="">的数据，区域之间没有重合的部分；</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Verdana,sans-serif;"><span style=""><br></span></span></span></span><span style=""><span style="">对于其它的数据，区域之间有重合的情况。</span></span></p>
</div>
</div>