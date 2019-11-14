<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>很久以前，有一个传说中的“EWF”部族，他们世代生活在一个<em>N</em>×<em>M</em>的矩形大地上。虽然，生活的地区有高山、有沼泽，但通过勤劳勇敢，渐渐地，他们在自己的地盘上修筑了一条回路。</p>
<p>后来，“EWF”部族神秘地消失了。不过，考古学家在那片他们曾经生活过的地方找到了一份地图。地图是<em>N</em>×<em>M</em>的矩阵，左上角的坐标为(0, 0)，右下角的坐标为(<em>N</em>, <em>M</em>)。矩阵中的每个格子，表示高山、沼泽、平地、房屋或是道路其中之一。如果一个格子表示道路，那么经过这个格子的道路要么是直走，要么是拐弯。如下图，左边2幅表示直走格子的，右边4幅表示需要拐弯的格子。一个表示道路的格子只能表示下列情况之一。</p>
<p>可是，由于地图的年代久远，考古学家虽然能分清一个格子代表的地形，可对于道路的标记，考古学家们只能分清这一格是表示直走的还是拐弯的。现在，他们求助于你，希望你能帮助他们复原这份“EWF”部族的地图。</p>
<p style=""><span style="">很久以前，有一个传说中的“</span><span style="font-family: 'Times New Roman','serif';">EWF</span><span style="">”</span><span style="">部族，他们世代生活在一个</span><em><span style="font-family: 'Times New Roman','serif';">N</span></em><span style="font-family: 'Times New Roman','serif';">×<em>M</em></span><span style="">的矩形大地上。虽然，生活的地区有高山、有沼泽，但通过勤劳勇敢，渐渐地，他们在自己的地盘上修筑了一条回路。</span></p>
<p style=""><span style="">后来，“</span><span style="font-family: 'Times New Roman','serif';">EWF</span><span style="">”</span><span style="">部族神秘地消失了。不过，考古学家在那片他们曾经生活过的地方找到了一份地图。地图是</span><em><span style="font-family: 'Times New Roman','serif';">N</span></em><span style="font-family: 'Times New Roman','serif';">×<em>M</em></span><span style="">的矩阵，左上角的坐标为</span><span style="font-family: 'Times New Roman','serif';">(0, 0)</span><span style="">，右下角的坐标为</span><span style="font-family: 'Times New Roman','serif';">(<em>N</em>, <em>M</em>)</span><span style="">。矩阵中的每个格子，表示高山、沼泽、平地、房屋或是道路其中之一。如果一个格子表示道路，那么经过这个格子的道路要么是直走，要么是拐弯。如下图，左边</span><span style="font-family: 'Times New Roman','serif';">2</span><span style="">幅表示直走格子的，右边</span><span style="font-family: 'Times New Roman','serif';">4</span><span style="">幅表示需要拐弯的格子。一个表示道路的格子只能表示下列情况之一。</span></p>
<div>
<table border="1" cellpadding="0" cellspacing="0" style="">
<tbody>
<tr>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
</tr>
<tr>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
<td style="" valign="top" width="25">
<p><span style="font-family: 'Times New Roman','serif';"> </span></p>
</td>
</tr>
</tbody>
</table>
</div>
<p style=""><span style="">可是，由于地图的年代久远，考古学家虽然能分清一个格子代表的地形，可对于道路的标记，考古学家们只能分清这一格是表示直走的还是拐弯的。现在，他们求助于你，希望你能帮助他们复原这份“</span><span style="font-family: 'Times New Roman','serif';">EWF</span><span style="">”</span><span style="">部族的地图。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个用空格分隔的正整数<em>N</em>和<em>M</em>，分别表示地图的高和长。</p>
<p>接下来一个<em>N</em>行<em>M</em>列的矩阵描述地图，矩阵中没有多余字符。</p>
<p>大写“S”表示直走的道路，大写“T”表示拐弯的道路，点“.”表示高山、沼泽、平地和房屋。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含2<em>N</em>-1行，<strong>每行</strong><strong>2<em>M</em>-1</strong><strong>个字符</strong>，描述了这条回路。</p>
<p>所有第2<em>i</em>+1行的2<em>j</em>+1个字符为小写字母o，表示了矩阵的第<em>i</em>行第<em>j</em>列的格子的中心(<em>i</em>, <em>j</em>)。</p>
<p>若回路包含了(<em>i</em>, <em>j</em>)到(<em>i</em>, <em>j</em>+1)或(<em>i</em>, <em>j</em>+1)到(<em>i</em>, <em>j</em>)的一条路径，则第2<em>i</em>+1行的第2<em>j</em>+2个字符为减号&ldquo;-&rdquo;（ASCII码为45）；</p>
<p>若回路包含了(<em>i</em>, <em>j</em>)到(<em>i</em>+1, <em>j</em>)或(<em>i</em>+1, <em>j</em>)到(<em>i</em>, <em>j</em>)的一条路径，则第2<em>i</em>+2行的第2<em>j</em>+1个字符为竖线&ldquo;|&rdquo;（ASCII码为124）。</p>
<p><strong>其它以上未说明位置上的字符为空格（</strong><strong>ASCII</strong><strong>码为</strong><strong>32</strong><strong>）。</strong><strong></strong></p>
<p>输入数据保证至少存在一个合法解，故你的输出应有且仅有一条回路。如果存在多组答案，请输出任意一组。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4</p>
<p>TST.</p>
<p>S.TT</p>
<p>TSST</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>o-o-o o</p>
<p>|   | </p>
<p>o o o-o</p>
<p>|     |</p>
<p>o-o-o-o</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，有<em>N </em>≤ 10；</p>
<p>对于40%的数据，有1 ≤ <em>N</em>, <em>M </em>≤ 80；</p>
<p>对于40%的数据，输入没有“.”,且<em>N</em>, <em>M</em> &gt; 10；</p>
<p>对于100%的数据，满足1 ≤ <em>N</em>, <em>M </em>≤ 800。</p>
</div>
</div>