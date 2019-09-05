# 题目描述


<p>
</p><table style="padding:0pt 5.4pt;border-collapse:collapse;">
<tbody>
<tr>
<td width="111" valign="top" style="background:#8064A2;border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="color:#FFFFFF;font-family:" calibri";font-size:16pt;font-weight:bold;"="">Problem 2</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
<td width="552" valign="top" style="background:#8064A2;border:1pt solid #9F8AB9;">
<p>
<span style="color:#FFFFFF;font-family:" calibri";font-size:16pt;font-weight:bold;"="">西行寺幽幽子<span>(spring.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">在幻想乡，西行寺幽幽子是以贪吃闻名的亡灵。不过幽幽子可不是只会吃，至少她还管理着亡灵界。话说在幽幽子居住的白玉楼有一颗常年不开花的樱树</span><span style="font-family:" calibri";font-size:10.5pt;"="">——</span><span style="font-family:" calibri";font-size:10.5pt;"="">西行妖。幽幽子决定去收集人间的春度，聚集起来让西行妖开花。很快，作为幽幽子家园艺师的魂魄妖梦收集到了</span><span style="font-family:" calibri";font-size:10.5pt;"="">M</span><span style="font-family:" calibri";font-size:10.5pt;"="">个单位的春度。并且在这段时间里，幽幽子计算出要让西行妖开</span><span style="font-size:10.5pt;">出</span><span style="font-family:" calibri";font-size:10.5pt;"="">一朵花需要</span><span style="font-family:" calibri";font-size:10.5pt;"="">N</span><span style="font-family:" calibri";font-size:10.5pt;"="">个单位的春度。现在幽幽子想要知道，使用所有的春度，能够让西行妖开出多少朵花。</span><span style="font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="border:1pt solid #9F8AB9;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输入格式</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
<td width="581" valign="top" style="border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">第</span><span style="font-family:" calibri";font-size:10.5pt;"="">1</span><span style="font-family:" calibri";font-size:10.5pt;"="">行：一个正整数</span><span style="font-family:" calibri";font-size:10.5pt;"="">M</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">第</span><span style="font-family:" calibri";font-size:10.5pt;"="">2</span><span style="font-family:" calibri";font-size:10.5pt;"="">行：一个正整数</span><span style="font-family:" calibri";font-size:10.5pt;"="">N</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">N,M</span><span style="font-family:" calibri";font-size:10.5pt;"="">的位数不超过</span><span style="font-family:" calibri";font-size:10.5pt;"="">L</span><span style="font-family:" calibri";font-size:10.5pt;"="">，</span><span style="font-family:" calibri";font-size:10.5pt;"="">L</span><span style="font-family:" calibri";font-size:10.5pt;"="">的范围在题目后面给出</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">第</span><span style="font-family:" calibri";font-size:10.5pt;"="">1</span><span style="font-family:" calibri";font-size:10.5pt;"="">行：一个整数</span><span style="font-family:" calibri";font-size:10.5pt;"="">ans</span><span style="font-family:" calibri";font-size:10.5pt;"="">，表示能开出花的朵数</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="border:1pt solid #9F8AB9;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="font-size:10.5pt;">73861758</span><span style="font-size:10.5pt;"></span> 
</p>
<p>
<span style="font-size:10.5pt;">12471</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="background:#DFD8E8;border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="font-size:10.5pt;">5922</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="border:1pt solid #9F8AB9;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="border:1pt solid #9F8AB9;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">对于</span><span style="font-size:10.5pt;">60</span><span style="font-family:" calibri";font-size:10.5pt;"="">%</span><span style="font-family:" calibri";font-size:10.5pt;"="">的数据：</span><span style="font-family:" calibri";font-size:10.5pt;"="">L &lt;= 2,000</span><span style="font-family:" calibri";font-size:10.5pt;"="">且</span><span style="font-family:" calibri";font-size:10.5pt;"="">ans &lt;= 2,000</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">对于</span><span style="font-family:" calibri";font-size:10.5pt;"="">100%</span><span style="font-family:" calibri";font-size:10.5pt;"="">的数据：</span><span style="font-family:" calibri";font-size:10.5pt;"="">L &lt;= 20,000</span><span style="font-family:" calibri";font-size:10.5pt;"="">且</span><span style="font-family:" calibri";font-size:10.5pt;"="">ans &lt;= 2,000,000,000</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<span><span style="line-height:normal;"><img src="/upload/image/20160328/20160328183341_81602.jpg" alt=""/><br/>
</span></span> 
<p></p>
