<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    公元 2044 年，人类进入了宇宙纪元。L 国有 n 个星球，还有 n−1 条双向航道，每条航道建立在两个星球之间，这 n−1 条航道连通了 L 国的所有星球。小 P 掌管一家物流公司， 该公司有很多个运输计划，每个运输计划形如：有一艘物流飞船需要从 ui 号星球沿最快的宇航路径飞行到 vi 号星球去。显然，飞船驶过一条航道是需要时间的，对于航道 j，任意飞船驶过它所花费的时间为 tj，并且任意两艘飞船之间<strong>不会产生任何干扰</strong>。为了鼓励科技创新， L 国国王同意小 P 的物流公司参与 L 国的航道建设，即允许小P 把某一条航道改造成虫洞，飞船驶过虫洞<strong>不消耗时间</strong>。在虫洞的建设完成前小 P 的物流公司就预接了 m 个运输计划。在虫洞建设完成后，这 m 个运输计划会<strong>同时开始</strong>，所有飞船一起出发。当这 m 个运输计划都完成时，小 P 的物流公司的阶段性工作就完成了。如果小 P 可以自由选择将哪一条航道改造成虫洞， 试求出小 P 的物流公司完成阶段性工作所需要的最短时间是多少?</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">    第一行包括两个正整数 n,m，表示 L 国中星球的数量及小 P 公司预接的运输计划的数量，星球从 1 到 n 编号。接下来 n−1 行描述航道的建设情况，其中第 i 行包含三个整数 ai,bi 和 ti，表示第 i 条双向航道修建在 ai 与 bi 两个星球之间，任意飞船驶过它所花费的时间为 ti。数据保证 1&lt;=ai,bi&lt;=n 且 0&lt;=ti&lt;=1000。接下来 m 行描述运输计划的情况，其中第 j 行包含两个正整数 uj 和 vj，表示第 j 个运输计划是从 uj 号星球飞往 vj号星球。数据保证 1&lt;=ui,vi&lt;=n</span><span style=""></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-align: left;"><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">&nbsp;&nbsp;&nbsp;&nbsp;输出文件只包含一个整数，表示小 P 的物流公司完成阶段性工作所需要的最短时间。<span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;; font-size: 16px;"></span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">6 3<br style="font-family: arial, verdana, helvetica, sans-serif;">1 2 3<br style="font-family: arial, verdana, helvetica, sans-serif;">1 6 4<br style="font-family: arial, verdana, helvetica, sans-serif;">3 1 7<br style="font-family: arial, verdana, helvetica, sans-serif;">4 3 6<br style="font-family: arial, verdana, helvetica, sans-serif;">3 5 5<br style="font-family: arial, verdana, helvetica, sans-serif;">3 6<br style="font-family: arial, verdana, helvetica, sans-serif;">2 5<br style="font-family: arial, verdana, helvetica, sans-serif;">4 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">11</span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">样例解释:</span></p><p style=""><span style="">    将第 1 条航道改造成虫洞： 则三个计划耗时分别为：11,12,11，故需要花费的时间为 12。</span></p><p style=""><span style="">    将第 2 条航道改造成虫洞： 则三个计划耗时分别为：7,15,11，故需要花费的时间为 15。</span></p><p style=""><span style="">    将第 3 条航道改造成虫洞： 则三个计划耗时分别为：4,8,11，故需要花费的时间为 11。</span></p><p style=""><span style="">    将第 4 条航道改造成虫洞： 则三个计划耗时分别为：11,15,5，故需要花费的时间为 15。</span></p><p style=""><span style="">    将第 5 条航道改造成虫洞： 则三个计划耗时分别为：11,10,6，故需要花费的时间为 11。</span></p><p style=""><span style="">    故将第 3 条或第 5 条航道改造成虫洞均可使得完成阶段性工作的耗时最短，需要花费的时间为 11。</span></p><p><br></p><p><span style="">测试数据及约定:</span></p><p><br></p><p><br></p><table width="568"><tbody><tr><td style="" valign="middle"><span style="">测试点编号</span></td><td style="" valign="middle"><span style="">n=</span></td><td style="" valign="middle"><span style="">m=</span></td><td style="" valign="middle"><span style="">约定</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">1<br></span></td><td height="19" style="" valign="middle" width="79"><span style="">100<br></span></td><td height="19" style="" valign="middle" width="79"><span style="">1<br></span></td><td height="19" style="" valign="middle" width="311"><br></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">2</span></td><td height="19" style="" valign="middle" width="79"><span style="">100</span></td><td style="" valign="middle" width="79"><span style="">100</span><br></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与<span style="">i+1号星球</span></span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">3</span></td><td height="19" style="" valign="middle" width="79"><span style="">100</span></td><td style="" valign="middle"><span style="">100</span></td><td style="" valign="middle" width="311"><br></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">4</span></td><td height="19" style="" valign="middle" width="79"><span style="">2000</span></td><td height="19" style="" valign="middle" width="79"><span style="">1</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">5</span></td><td height="19" style="" valign="middle" width="79"><span style="">1000</span></td><td height="19" style="" valign="middle" width="79"><span style="">1000</span></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与i+1号星球</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">6</span></td><td height="19" style="" valign="middle" width="79"><span style="">2000</span></td><td height="19" style="" valign="middle" width="79"><span style="">2000</span></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与i+1号星球</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">7</span></td><td height="19" style="" valign="middle" width="79"><span style="">3000</span></td><td height="19" style="" valign="middle" width="79"><span style="">3000</span></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与i+1号星球</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">8</span></td><td height="19" style="" valign="middle" width="79"><span style="">1000</span></td><td height="19" style="" valign="middle" width="79"><span style="">1000<br></span></td><td style="" valign="middle" width="311"><br></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">9</span></td><td height="19" style="" valign="middle" width="79"><span style="">2000</span></td><td height="19" style="" valign="middle" width="79"><span style="">2000</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">10</span></td><td height="19" style="" valign="middle" width="79"><span style="">3000</span></td><td height="19" style="" valign="middle" width="79"><span style="">3000</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">11</span></td><td height="19" style="" valign="middle" width="79"><span style="">80000</span></td><td height="19" style="" valign="middle" width="79"><span style="">1<br></span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">12</span></td><td height="19" style="" valign="middle" width="79"><span style="">100000</span></td><td height="19" style="" valign="middle" width="79"><span style="">1</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">13</span></td><td height="19" style="" valign="middle" width="79"><span style="">70000</span></td><td height="19" style="" valign="middle" width="79"><span style="">70000</span></td><td height="19" style="" valign="middle" width="311"><span style=""></span><p><span style="">第i条航道连接i号星球与i+1号星球</span></p><span style=""></span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">14</span></td><td height="19" style="" valign="middle" width="79"><span style="">80000</span></td><td height="19" style="" valign="middle" width="79"><span style="">80000</span></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与i+1号星球</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">15</span></td><td height="19" style="" valign="middle" width="79"><span style="">90000</span></td><td height="19" style="" valign="middle" width="79"><span style="">90000</span></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与i+1号星球</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">16</span></td><td height="19" style="" valign="middle" width="79"><span style="">100000</span></td><td height="19" style="" valign="middle" width="79"><span style="">100000</span></td><td height="19" style="" valign="middle" width="311"><span style="">第i条航道连接i号星球与i+1号星球</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">17</span></td><td height="19" style="" valign="middle" width="79"><span style="">80000</span></td><td height="19" style="" valign="middle" width="79"><span style="">80000</span></td><td style="" valign="middle" width="311"><br></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">18</span></td><td height="19" style="" valign="middle" width="79"><span style="">90000</span></td><td height="19" style="" valign="middle" width="79"><span style="">90000</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">19</span></td><td height="19" style="" valign="middle" width="79"><span style="">100000</span></td><td height="19" style="" valign="middle" width="79"><span style="">100000</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><span style="">20</span></td><td height="19" style="" valign="middle" width="79"><span style="">300000</span></td><td height="19" style="" valign="middle" width="79"><span style="">300000</span></td></tr><tr><td height="19" style="" valign="middle" width="97"><p><br></p><p><span style="">所有数据</span></p><p><br></p></td><td height="19" style="" valign="middle" width="79"><br></td><td height="19" style="" valign="middle" width="79"><br></td><td height="19" style="" valign="middle" width="311">1 &lt;= ai, bi, uj, vj &lt;= n, 0 &lt;= ti &lt;= 1000</td></tr></tbody></table><p><span style="">(所有测试点编号加10)</span></p>
</div>
</div>