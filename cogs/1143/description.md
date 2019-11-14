# 题目描述


<p style="text-indent:141.7500pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">treecut</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">题目描述：</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  有一个N个节点的无根树，各节点编号为1..N，现在要求你删除其中的一个点，使分割开的连通块中节点个数都不超过原来的一半多。 </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据范围</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">   1 &lt;= N &lt;= 10,000</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件 treecut.in</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  第一行：一个整数N。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  后面有N-1行：每行两个整数 X 和 Y，表示一个边连接的两个节点号。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件 treecut.out</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">   输出所有可能选择的点。如果有多个节点，按编号从小到大输出，每个一行。 如果找不到这样的点，输出一行：&#34;NONE&#34;.</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例</span> 
</p>
<table style="padding:0.75pt;">
<tbody>
<tr>
<td style="border:0.7500pt outset #000000;" width="67" valign="center">
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
<td style="border:0.7500pt outset #000000;" width="282" valign="center">
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">10</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1 2</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">2 3</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3 4</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4 5</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">6 7</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">7 8</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">8 9</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">9 10</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3 8</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
<td style="border:0.7500pt outset #000000;" width="211" valign="center">
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">样例说明：</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">删除3号或8号</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">节点，则分枝</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">最多有5个节点</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;"> </span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.7500pt outset #000000;" width="67" valign="center">
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出</span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
<td style="border:0.7500pt outset #000000;" width="282" valign="center">
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">8         </span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
<td style="border:0.7500pt outset #000000;" width="211" valign="center">
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">    </span><span style="font-size:9.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
