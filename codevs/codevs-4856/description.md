<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<table cellpadding="0" cellspacing="0" style="" width="602"><tbody><tr><td style="" valign="top"><p><span style="">猴子们有一个很大的花园，花园可以分成 </span><span style="">n </span><span style="">块不同的区域（编号为 </span><span style="">1 </span><span style="">到 </span><span style="">n</span><span style="">）</span> <span style="">春暖花开，。</span></p><p><span style="">同时也是杂草开始生长的季节，编号为 </span><span style="">i </span><span style="">的区域中有 </span><span style="">a</span><span style="">i </span><span style="">个单位面积的杂草。为了除去花园中</span></p><p><span style="">的杂草，猴子们请了 </span><span style="font-family: 'Times New Roman Bold';">n </span><span style="">个除草员分别给   </span><span style="font-family: 'Times New Roman Bold';">n </span><span style="">块区域除草，每个除草员每个单位时间内可以除</span></p><p><span style="">去 </span><span style="font-family: 'Times New Roman Bold';">1 </span><span style="">个单位面积的杂草，某个区域的杂草除完后该除草员立即停止工作。</span></p><p><span style="">   </span><span style="">为了提高除草的效率，希望尽快完成除草任务，猴子们买了一台除草机帮助除草员进行</span></p><p><span style="">除草，但这台除草机在一个单位时间内仅能供一个除草员使用，使用除草机后除草员的工</span></p><p><span style="">作效率提高到 </span><span style="">m</span><span style="">，即该除草员每个单位时间可以除去</span><span style=""> m </span><span style="">个单位面积的杂草（当然不使用后</span></p><p><span style="">仍然恢复到原来的工作效率）。</span></p><p><span style="">   </span><span style="">现在，请你编程帮猴子们决定，怎样分配这台除草机的使用对象才能使完成所有除草任</span></p><p><span style="">务的时间最短？</span></p></td></tr></tbody></table><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<table cellpadding="0" cellspacing="0" style="" width="602"><tbody><tr><td style="" valign="top"><p>输入共 2 行。</p><p>第 1 行两个整数 n 和 m，表示花园中共有 n 块待除草的不同区域和除草员使用除草机时</p></td></tr></tbody></table><table cellpadding="0" cellspacing="0" width="533"><tbody><tr><td style="" valign="top"><p>的工作效率为 m。</p><p>第 2 行 n 个整数，第 i 个整数 ai 表示第 i 块区域中有 ai 个单位面积的杂草。</p></td></tr></tbody></table><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<table cellspacing="0" cellpadding="0" hspace="0" vspace="0" width="469"><tbody><tr class="firstRow"><td valign="top" style="padding-top:0;padding-right:0;padding-bottom:0;padding-left:0"><p><span style="font-size: 13px;font-family: 宋体">输出一行，一个整数，表示完成所有除草任务所需的最短时间。</span></p></td></tr></tbody></table><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">34
235</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">2</span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table cellpadding="0" cellspacing="0" style="" width="602"><tbody><tr><td style="" valign="top"><p><span style="">【样例解释】</span></p><p><span style="">输入中有 3 块需要除草的区域，每块区域杂草的面积依次为 2，3，5 个单位面积。如果</span></p><p><span style="">使用除草机在单位时间内能除 4 个单位面积的草。</span></p><p><span style="">完成所有除草任务最少需要 </span><span style="">2 </span><span style="">个单位时间。方案可能不唯一，比如：</span></p><p><span style="">方案一：在第一个单位时间内，除草机给 2 号区域的除草员使用，第一个单位时间结束</span></p><p><span style="">时各区域依次还有 1，0，4 个单位面积的杂草。在第二个单位时间内，除草机给   3 号区域的</span></p><p><span style="">除草员使用，第二个单位时间结束时各区域依次还有   0，0，0 个单位面积的杂草，即经过   2</span></p><p><span style="">个单位时间后所有的杂草被除尽。</span></p><p><span style="">方案二：在第一个单位时间内，除草机给 3 号区域的除草员使用，第一个单位时间结束</span></p><p><span style="">时各区域依次还有 1，2，1 个单位面积的杂草。在第二个单位时间内，除草机给   2 号区域的</span></p><p><span style="">除草员使用，第二个单位时间结束时各区域依次还有   0，0，0 个单位面积的杂草，即经过   2</span></p><p><span style="">个单位时间后所有的杂草被除尽。</span></p></td></tr></tbody></table><table cellpadding="0" cellspacing="0" width="383"><tbody><tr><td style="" valign="top"><p><span style="">【数据范围】</span></p><p><span style="">30%</span><span style="">的数据，1≤n≤1000，0≤a</span><span style="">i</span><span style="">≤10000。</span></p><p><span style="">        </span><span style="">599</span><span style="">100%</span><span style="">的数据，1≤n≤10 ，0≤a</span><span style="">i</span><span style="">≤10   ，1≤m≤10   。</span></p></td></tr></tbody></table><p><br></p>
</div>
</div>