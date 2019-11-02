<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">【问题描述】<br style="">小灰灰有一个很大的花园,花园可以分成 </span><span style="">n </span><span style="">块不同的区域(编号为 </span><span style="">1 </span><span style="">到 </span><span style="">n</span><span style="">)。春暖花开,</span><span style="">同时也是杂草开始生长的季节,编号为 </span><span style="">i </span><span style="">的区域中有 </span><span style="">a</span><span style="">i </span><span style="">个单位面积的杂草。为了除去花园中 的杂草,灰灰请了 </span><span style="">n </span><span style="">个除草员分别给 </span><span style="">n </span><span style="">块区域除草,每个除草员每个单位时间内可以除 去 </span><span style="">1 </span><span style="">个单位面积的杂草,某个区域的杂草除完后该除草员立即停止工作。</span></p><p style=""><span style="">为了提高除草的效率,希望尽快完成除草任务,小灰灰买了一台除草机帮助除草员进行 除草,但这台除草机在一个单位时间内仅能供一个除草员使用,使用除草机后除草员的工作效率提高到 </span><span style="">m</span><span style="">,即该除草员每个单位时间可以除去 </span><span style="">m </span><span style="">个单位面积的杂草(当然不使用后 仍然恢复到原来的工作效率)。</span></p><p style=""><span style="">现在,请你编程帮灰灰们决定,怎样分配这台除草机的使用对象才能使完成所有除草任务的时间最短? </span></p><p style=""><span style="">由于灰灰变身成猴子，所以他灰常心急，需要在1s内知道方案。</span></p><p style=""><span style=""><br></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入共 </span><span style="">2 </span><span style="">行。</span></p><p style=""><span style="">第 </span><span style="">1 </span><span style="">行两个整数 </span><span style="">n </span><span style="">和 </span><span style="">m</span><span style="">,表示花园中共有 </span><span style="">n </span><span style="">块待除草的不同区域和除草员使用除草机时</span><span style="">的工作效率为 </span><span style="">m</span><span style="">。</span></p><p style=""><span style="">第 </span><span style="">2 </span><span style="">行 </span><span style="">n </span><span style="">个整数,第 </span><span style="">i </span><span style="">个整数 </span><span style="">a</span><span style="">i </span><span style="">表示第 </span><span style="">i </span><span style="">块区域中有 </span><span style="">a</span><span style="">i </span><span style="">个单位面积的杂草。</span> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; font-size: 14.545454025268555px; line-height: 23.99147605895996px; background-color: rgb(228, 240, 248);">输出一行,一个整数,表示完成所有除草任务所需的最短时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">3 4 </span></p><p><span style="font-family: monospace;">2 3 5</span></p>

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
<p style=""><span style="">样例解释】<br style=""><br style="">输入中有 </span><span style="">3 </span><span style="">块需要除草的区域,每块区域杂草的面积依次为 </span><span style="">2</span><span style="">,</span><span style="">3</span><span style="">,</span><span style="">5 </span><span style="">个单位面积。如果</span><span style="">使用除草机在单位时间内能除 </span><span style="">4 </span><span style="">个单位面积的草。</span></p><p style=""><br style="font-family: 'Times New Roman';"></p><p style=""><span style="">完成所有除草任务最少需要 </span><span style="">2 </span><span style="">个单位时间。方案可能不唯一,比如: 方案一:在第一个单位时间内,除草机给 </span><span style="">2 </span><span style="">号区域的除草员使用,第一个单位时间结束</span></p><p style=""><br style="font-family: 'Times New Roman';"></p><p style=""><span style="">时各区域依次还有 </span><span style="">1</span><span style="">,</span><span style="">0</span><span style="">,</span><span style="">4 </span><span style="">个单位面积的杂草。在第二个单位时间内,除草机给 </span><span style="">3 </span><span style="">号区域的 除草员使用,第二个单位时间结束时各区域依次还有 </span><span style="">0</span><span style="">,</span><span style="">0</span><span style="">,</span><span style="">0 </span><span style="">个单位面积的杂草,即经过 </span><span style="">2 </span><span style="">个单位时间后所有的杂草被除尽。</span></p><p style=""><br style="font-family: 'Times New Roman';"></p><p style=""><span style="">方案二:在第一个单位时间内,除草机给 </span><span style="">3 </span><span style="">号区域的除草员使用,第一个单位时间结束 时各区域依次还有 </span><span style="">1</span><span style="">,</span><span style="">2</span><span style="">,</span><span style="">1 </span><span style="">个单位面积的杂草。在第二个单位时间内,除草机给 </span><span style="">2 </span><span style="">号区域的 除草员使用,第二个单位时间结束时各区域依次还有</span><span style="">0</span><span style="">,</span><span style="">0</span><span style="">,</span><span style="">0 </span><span style="">个单位面积的杂草,即经过 </span><span style="">2 </span><span style="">个单位时间后所有的杂草被除尽。 </span></p><p style=""><br style="font-family: 'Times New Roman';"></p><p style=""><span style="">【数据范围】</span></p><p style=""><br style="font-family: 'Times New Roman';"></p><p style=""><span style="">30%</span><span style="">的数据,</span><span style="">1</span><span style="">≤</span><span style="">n</span><span style="">≤</span><span style="">1000</span><span style="">,</span><span style="">0</span><span style="">≤</span><span style="">a</span><span style="">i</span><span style="">≤</span><span style="">10000</span><span style="">。</span></p><p style=""><br style="font-family: 'Times New Roman';"></p><p style=""><span style="">100%</span><span style="">的数据,</span><span style="">1</span><span style="">≤</span><span style="">n</span><span style="">≤</span><span style="">10^</span><span style="">5</span><span style="">,</span><span style="">0</span><span style="">≤</span><span style="">a</span><span style="">i</span><span style="">≤</span><span style="">10^</span><span style="">9</span><span style="">,</span><span style="">1</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span><span style="">。<br style=""></span></p><p><span style=""><br></span></p><p><br></p>
</div>
</div>