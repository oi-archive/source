<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">雷骆的妈妈给他买了一个新玩具，这是一个奇怪的矩阵。如图： </span></p><p style=""><br></p><table cellpadding="0" cellspacing="0"><tbody><tr style=""><td height="37" style="" valign="top" width="48"><p style=""><span style="">1</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">2</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">3</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">4</span></p></td></tr><tr style=""><td height="37" style="" valign="top" width="48"><p style=""><span style="">5</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">6</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">7</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">8</span></p></td></tr><tr style=""><td height="37" style="" valign="top" width="48"><p style=""><span style="">9</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">10</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">11</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">12</span></p></td></tr><tr style=""><td height="37" style="" valign="top" width="48"><p style=""><span style="">13</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">14</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">15</span></p></td><td height="37" style="" valign="top" width="48"><p style=""><span style="">16</span></p></td></tr></tbody></table><p style=""><span style="">这是一个</span><em><span style="">N</span></em><span style="">*<em>N</em></span><span style="">的矩阵</span><span style="">(</span><span style="">我们从上到下，从左到右对其标号，比如说</span><span style="">5</span><span style="">在</span><span style="">(1,2)</span><span style="">，</span><span style="">12</span><span style="">在</span><span style="">(4,3))</span><span style="">，一开始依次标有</span><span style="">1~<em>N </em><sup>2</sup></span><span style="">个数字。</span>雷骆<span style=""></span><span style="">可以操作这个矩阵： </span></p><p style=""><span style="">·行的操作，就是将某一行向右移一格，最后一格将会被移动到第一格 </span></p><p style=""><span style="">·列的操作，就是将某一列向下移一格，最后一格将会被移动到第一格 </span></p><p style=""><span style="">由于</span>雷骆<span style=""></span><span style="">还小，智商有限，所以他如果要将某个数字</span><em><span style="">num</span></em><span style="">，目前在</span><span style="">(<em>x</em>0,<em>y</em>0)</span><span style="">，移动到特定的某格</span><span style="">(<em>x</em>,<em>y</em>)</span><span style="">。如果</span><em><span style="">x</span></em><span style="">0</span><span style="">≠</span><em><span style="">x</span></em><span style="">，则</span>雷骆<span style=""></span><span style="">会先移动</span><em><span style="">num</span></em><span style="">到</span><em><span style="">y</span></em><em><span style="">列</span></em><span style="">，然后再移动到x行。 </span></p><p style=""><span style="">现在妈妈给</span>雷骆<span style=""></span><span style="">布置了</span><em><span style="">K</span></em><span style="">个任务，要求</span>雷骆<span style=""></span><span style="">依次将</span><em><span style="">numi</span></em><span style="">移动到</span><span style="">(<em>xi</em>,<em>yi</em>)</span><span style="">上，妈妈想知道每个任务</span>雷骆<span style=""></span><span style="">需要操作多少次。</span><span style="">(</span><span style="">这些任务是依次进行的，且做第</span><em><span style="">i</span></em><span style="">个任务的时候，不需要考虑前</span><em><span style="">i</span></em><span style="">-1</span><span style="">个任务的要求是否满足</span><span style="">) </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行两个数</span><em><span style="">N</span></em><span style="">和</span><em><span style="">K</span></em><span style="">。 </span></p><p style=""><span style="">接下来</span><em><span style="">K</span></em><span style="">行，每行三个数，</span><em><span style="">numi xi yi</span></em><span style="">。 </span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 32px;line-height: 150%"><em><span style="font-size: 16px;line-height: 150%">共K</span></em><span style="font-size: 16px;line-height: 150%;font-family: 宋体">行，每行一个数表示，每个任务的操作次数。 </span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">5 3 </span></p><p style=""><span style="font-family: 'Courier New';">1 2 2 </span></p><p style=""><span style="font-family: 'Courier New';">2 2 2 </span></p><p style=""><span style="font-family: 'Courier New';">12 5 5 </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">2 </span></p><p style=""><span style="font-family: 'Courier New';">5 </span></p><p style=""><span style="font-family: 'Courier New';">3 </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于</span><span style="">60%</span><span style="">的数据</span><em><span style="">N</span></em><span style="">≤</span><span style="">5000</span><span style="">； </span></p><p style=""><span style="">对于</span><span style="">100%</span><span style="">的数据</span><span style="">2</span><span style="">≤</span><em><span style="">N</span></em><span style="">≤</span><span style="">10000</span><span style="">，</span><span style="">1</span><span style="">≤</span><em><span style="">K</span></em><span style="">≤</span><span style="">1000</span><span style="">。</span></p><p style=""><span style="">第一个任务完成后：</span></p><p style=""><span style="font-family: 'Courier New';">5 22 2 3 4 </span></p><p style=""><span style="font-family: 'Courier New';">6 1 8 9 10 </span></p><p style=""><span style="font-family: 'Courier New';">11 7 13 14 15 </span></p><p style=""><span style="font-family: 'Courier New';">16 12 18 19 20 </span></p><p style=""><span style="font-family: 'Courier New';">21 17 23 24 25 </span></p><p style=""><span style="">第二个任务在这个基础上，继续操作。同理第</span><span style="">3</span><span style="">个任务也是在第二个任务的完成的基础上，继续操作。</span></p><p><br></p>
</div>
</div>