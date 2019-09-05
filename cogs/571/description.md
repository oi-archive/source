# 题目描述


<div>
<span style="font-size:12pt;"> Long long ago,Lost-Monkey</span><span style="font-size:12pt;">和</span><span style="font-size:12pt;">XXX</span><span style="font-size:12pt;">一起来到一个神庙废墟前，这里曾经是一座雄伟的神庙，他们想进去玩，可是神庙的门紧闭着。聪明的</span><span style="font-size:12pt;">Lost-Monkey</span><span style="font-size:12pt;">发现门上写着这样几句话：</span>
</div>
<div>
<span style="font-size:12pt;">        </span><span style="font-size:12pt;">不断改变的数字是神的叩问</span>
</div>
<div>
<span style="font-size:12pt;">        </span><span style="font-size:12pt;">永恒不变的规则是门的钥匙</span>
</div>
<div>
<span style="font-size:12pt;">        </span><span style="font-size:12pt;">跟上神的节奏你将走向光明</span>
</div>
<div>
<span style="font-size:12pt;">再往下看原来所谓的规则是一个递推数列</span>
</div>
<div>
<span style="font-size:12pt;">F[0]=1</span>
</div>
<div>
<span style="font-size:12pt;">F[1]=1</span>
</div>
<div>
<span style="font-size:12pt;">F[n]=F[n div 2]+F[n div 3]+F[n div 5]+F[n div 7]</span>
</div>
<div>
<span style="font-size:12pt;">    </span><span style="font-size:12pt;">下面则是一个屏幕，不断地改变数字差不多</span><span style="font-size:12pt;">2</span><span style="font-size:12pt;">秒一次，所以你必须在</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">秒内得到答案。</span>
</div>
<div>
<span style="font-size:12pt;">    Lost-Monkey</span><span style="font-size:12pt;">一下就猜到了屏幕上的数字就是要你求数列的第多少项，然后把答案写在下面。</span>
</div>
<div>
 
</div>
<div>
<span style="font-size:12pt;">输入</span><span style="font-size:12pt;">:</span>
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">N</span><span style="font-size:12pt;">表示屏幕上的数。</span>
</div>
<div>
<span style="font-size:12pt;">输出：</span>
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">一个数，即</span><span style="font-size:12pt;">F[n]</span>
</div>
<div>
<span style="font-size:12pt;">样例</span>
</div>
<table style="border-right:medium none;border-top:medium none;border-left:medium none;border-bottom:medium none;border-collapse:collapse;" border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td style="border-right:windowtext 1pt solid;padding-right:5.4pt;border-top:windowtext 1pt solid;padding-left:5.4pt;padding-bottom:0cm;border-left:windowtext 1pt solid;width:213.05pt;padding-top:0cm;border-bottom:windowtext 1pt solid;background-color:transparent;" valign="top" width="284">
<div>
<span style="font-size:12pt;">losttemple.in</span>
</div>
</td>
<td style="border-right:windowtext 1pt solid;padding-right:5.4pt;border-top:windowtext 1pt solid;padding-left:5.4pt;padding-bottom:0cm;border-left:#ece9d8;width:213.05pt;padding-top:0cm;border-bottom:windowtext 1pt solid;background-color:transparent;" valign="top" width="284">
<pre>losttemple.out</pre>
</td>
</tr>
<tr>
<td style="border-right:windowtext 1pt solid;padding-right:5.4pt;border-top:#ece9d8;padding-left:5.4pt;padding-bottom:0cm;border-left:windowtext 1pt solid;width:213.05pt;padding-top:0cm;border-bottom:windowtext 1pt solid;background-color:transparent;" valign="top" width="284">
<pre>2</pre>
</td>
<td style="border-right:windowtext 1pt solid;padding-right:5.4pt;border-top:#ece9d8;padding-left:5.4pt;padding-bottom:0cm;border-left:#ece9d8;width:213.05pt;padding-top:0cm;border-bottom:windowtext 1pt solid;background-color:transparent;" valign="top" width="284">
<div>
<span style="font-size:12pt;">4</span>
</div>
</td>
</tr>
</tbody>
</table>
<div>
 
</div>
<div>
<span style="font-size:12pt;">数据范围约定</span><span style="font-size:12pt;">:</span>
</div>
<div>
<span style="font-size:12pt;">40%</span><span style="font-size:12pt;">的数据</span><span style="font-size:12pt;">,n&lt;=10000000</span>
</div>
<div>
<span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据，</span><span style="font-size:12pt;">n&lt;=4000000000000</span>
</div>
