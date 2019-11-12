# 题目描述


<p>
</p><table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
<tbody>
<tr>
<td colspan="2" style="border:1.0000pt solid #78C0D4;background:#4BACC6;" valign="top" width="111">
<p>
<span style="color:#FFFFFF;font-weight:bold;font-size:16.0000pt;font-family:&#39;Calibri&#39;;">Problem </span><span style="color:#FFFFFF;font-weight:bold;font-size:16pt;">3</span><span style="color:#FFFFFF;font-weight:bold;font-size:16pt;"></span> 
</p>
</td>
<td style="border:1.0000pt solid #78C0D4;background:#4BACC6;" valign="top" width="552">
<p>
<span style="color:#FFFFFF;font-weight:bold;font-size:16.0000pt;font-family:&#39;Calibri&#39;;">琪露诺<span>(iceroad.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-weight:bold;font-size:16pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">题目描述</span><span style="font-weight:bold;font-size:10.5pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="581">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">在幻想乡，琪露诺是以笨蛋闻名的冰之妖精。某一天，琪露诺又在</span><span style="font-size:10.5pt;">玩速</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">冻青蛙</span><span style="font-size:10.5pt;">，就是用冰把青蛙瞬间冻起来</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">。但是这只青蛙比以往的要聪明许多，在琪露诺来之前就已经跑到了河的对岸。于是琪露诺决定到河岸去追青蛙。小河可以看作一列格子依次编号为</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">到</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">N</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">，琪露诺只能从编号小的格子移动到编号大的格子。而且琪露诺按照一种特殊的方式进行移动，当她在格子</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">i</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">时，她只会移动到</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">i+L</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">到</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">i+R</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">中的一格。你问为什么她这么移动，这还不简单，因为她是笨蛋啊。每一个格子都有一个冰冻指数</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">A[i]</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">，编号为</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">的格子冰冻指数为</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">。当琪露诺停留在那一格时就可以得到那一格的冰冻指数</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">A[i]</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">。琪露诺希望能</span><span style="font-size:10.5pt;">够</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">在到达对岸时，获取最大的冰冻指数，这样她才能狠狠地教训那只青蛙。但是由于她实在是太笨了，所以她决定拜托你帮它决定怎样前进。开始时，琪露诺在编号</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">的格子上，只要她下一步的位置编号大于</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">N</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">就算到达对岸。</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">输入格式</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;" valign="top" width="581">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">第</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">行：</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">个正整数</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">N, L, R</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">第</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">行：</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">N+1</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">个整数，第</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">i</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">个数表示编号为</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">i-1<span>的格子的冰冻指数</span><span>A[i-1]</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">输出格式</span><span style="font-weight:bold;font-size:16pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="581">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">第<span>1</span><span>行：一个整数，表示最大冰冻指数。保证不超过</span></span><span style="font-size:10.5pt;">2^31-1</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">第<span>2</span><span>行：空格分开的若干个整数，表示琪露诺前进的路线，最后输出</span><span>-1</span><span>表示到达对岸</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">输入样例</span><span style="font-weight:bold;font-size:10.5pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;" valign="top" width="581">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">5 2 3</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">0 12 3 11 7 -2</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">输出样例</span><span style="font-weight:bold;font-size:10.5pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="581">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">11</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">0 3 -1</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">数据范围</span><span style="font-weight:bold;font-size:16pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;" valign="top" width="581">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">对于<span>60%</span><span>的数据：</span><span>N &lt;= 10,000</span></span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">对于<span>100%</span><span>的数据：</span><span>N &lt;= 200,000</span></span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">对于所有数据 <span>-1,000 &lt;= A[i] &lt;= 1,000</span><span>且</span><span>1 &lt;= L &lt;= R &lt;= N</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="82">
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">注意</span><span style="font-weight:bold;font-size:10.5pt;"> </span><span style="font-size:10.5pt;"></span> 
</p>
</td>
<td colspan="2" style="border:1.0000pt solid #78C0D4;background:#D2EAF1;" valign="top" width="581">
<p>
<span style="font-size:10.5pt;">此题采用<span>Special Judge</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<span><span style="line-height:normal;"><img src="/images/upload/image/20120715/20120715145851_90809.jpg" alt=""/><br/>
</span></span> 
<p></p>
