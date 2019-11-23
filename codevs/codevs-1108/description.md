<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    有红（<span style="font-family: 'Times New Roman', serif;"><span>R</span></span>）、绿（<span style="font-family: 'Times New Roman', serif;"><span>G</span></span>）、蓝（<span style="font-family: 'Times New Roman', serif;"><span>B</span></span>）、黑（<span style="font-family: 'Times New Roman', serif;"><span>A</span></span>）、白（<span style="font-family: 'Times New Roman', serif;"><span>W</span></span>）五种颜色的方块放在一个<span style="font-family: 'Times New Roman', serif;"><span>M*N</span></span>（<span style="font-family: 'Times New Roman', serif;"><span>M</span></span>，<span style="font-family: 'Times New Roman', serif;"><span>N&lt;=50</span></span>）的方框中。现要求消去同色相连大于<span style="font-family: 'Times New Roman', serif;"><span>3</span></span>的所有方块。消去过程为：一次同时消去同一直线上（横、竖、斜线）同色相连大于、等于<span style="font-family: 'Times New Roman', serif;"><span>3</span></span>的块。在消去过程中，同一方块可在不同方向上重复使用。方块消去后，上面的块自动下落，重复消去过程，直至不能消去为止。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件<span><span>game.in</span></span>格式：第一行为<span><span>M N</span></span>，以下是<span><span>M*N</span></span>的字母矩阵。</p>
<p>举例：设有<span><span>5*5</span></span>的方框，其方块的分布如下所示：</p>
&lt;dl&gt;&lt;dd&gt;
&lt;colgroup&gt;&lt;col width="37"/&gt;&lt;col width="38"/&gt;&lt;col width="38"/&gt;&lt;col width="38"/&gt;&lt;col width="38"/&gt;&lt;col width="123"/&gt;&lt;/colgroup&gt;
<table cellpadding="7" cellspacing="0"><tbody>
<tr valign="TOP">
<td height="7" width="37">
<p><span><span>R</span></span></p>
</td>
<td width="38">
<p><span><span>R</span></span></p>
</td>
<td width="38">
<p><span><span>R</span></span></p>
</td>
<td width="38">
<p><span><span>A</span></span></p>
</td>
<td width="38">
<p><span><span>A</span></span></p>
</td>
<td width="123"> </td>
</tr>
<tr valign="TOP">
<td height="9" width="37">
<p><span><span>W</span></span></p>
</td>
<td width="38">
<p><span><span>R</span></span></p>
</td>
<td width="38">
<p><span><span>A</span></span></p>
</td>
<td width="38">
<p><span><span>A</span></span></p>
</td>
<td width="38">
<p><span><span>W</span></span></p>
</td>
</tr>
<tr valign="TOP">
<td height="6" width="37">
<p><span><span>A</span></span></p>
</td>
<td width="38">
<p><span><span>W</span></span></p>
</td>
<td width="38">
<p><span><span>B</span></span></p>
</td>
<td width="38">
<p><span><span>A</span></span></p>
</td>
<td width="38">
<p><span><span>B</span></span></p>
</td>
</tr>
<tr valign="TOP">
<td height="6" width="37">
<p><span><span>W</span></span></p>
</td>
<td width="38">
<p><span><span>R</span></span></p>
</td>
<td width="38">
<p><span><span>B</span></span></p>
</td>
<td width="38">
<p><span><span>W</span></span></p>
</td>
<td width="38">
<p><span><span>W</span></span></p>
</td>
</tr>
<tr valign="TOP">
<td height="6" width="37">
<p><span><span>B</span></span></p>
</td>
<td width="38">
<p><span><span>B</span></span></p>
</td>
<td width="38">
<p><span><span>W</span></span></p>
</td>
<td width="38">
<p><span><span>W</span></span></p>
</td>
<td width="38">
<p><span><span>A</span></span></p>
</td>
</tr>
</tbody>
</table>
&lt;/dd&gt;&lt;/dl&gt;

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件<span><span lang="en-US">game.out</span></span>须输出消去所有可消去的方块后，剩余在方框中的方块信息。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman', serif;"><span>game.in:</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>5 5</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>RRRAA</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>WRAAW</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>AWBAB</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>WRBWW</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>BBWWA</span></span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman', serif;"><span>Game.out:</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>             A</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>WRA   W</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>AWB    B</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>WRBWW</span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span>BBWWA</span></span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>