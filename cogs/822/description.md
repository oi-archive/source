# 题目描述


<p>
<span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;background-color:#FFFFFF;">来源：TYVJ八月月赛提高组第3题</span>
</p>
<p>
<span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;background-color:#FFFFFF;"><img src="/upload/image/20140108/20140108135552_49666.jpg" alt="" height="383" width="526"/><br/>
</span> 
</p>
<p>
<span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;background-color:#FFFFFF;"> 
</span></p><table style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;" class="ke-zeroborder" bgcolor="#FFFFFF" border="0" cellpadding="0" cellspacing="0" height="0">
<tbody>
<tr>
</tr>
<tr>
<td colspan="2" style="font-family:Tahoma;color:#FF9900;font-weight:bold;" align="left" height="20" valign="top" width="512">
描述 Description
</td>
<td rowspan="2" style="font-family:Tahoma;color:#355F29;">
<br/>
</td>
</tr>
<tr>
<td style="font-family:Tahoma;color:#355F29;" align="left" valign="top" width="10">
 
</td>
<td style="font-family:Tahoma;color:#355F29;" align="left" valign="top" width="502">
黄金矿工是一个经典的小游戏，它可以锻炼人的反应能力。该游戏中，可以通过“挖矿”获得积分并不断升级。玩家可以在线玩flash版黄金矿工，也可以下载后玩单机版黄金矿工。目前，黄金矿工小游戏有多个版本，例如黄金矿工双人版，黄金矿工单人版等。<br/>
Jimmy是一位黄金矿工，他所在的金矿是一个n*n的矩形区域（俯视），区域内有黄金、石头和TNT，由一个n*n的矩阵描述。黄金的价值对应矩阵中的正值，石头的价值对应矩阵中的负值，TNT由0表示。换句话说，挖到黄金赚钱，石头亏损，如果挖到TNT就挂了~_~<br/>
Jimmy租到的挖矿工具很特别，它的形状是一个长宽任意（均为正整数）的矩形，可以取走被该工具覆盖的矩形区域内的所有物品，但如果该区域内有TNT，该工具将被炸毁，此时Jimmy将不得不赔偿矿主+∞元！！！需要注意的是，该工具只能在金矿范围内使用（即不得超出金矿边界），且租金为每次使用十元。<br/>
现在，Jimmy想知道，如果他至多只有一次租用该工具的机会，他能获得的最大收益是多少。当然，如果Jimmy租用该工具无论如何都会亏损，他可以不租用，此时收益为0.<br/>
</td>
</tr>
<tr>
<td style="font-family:Tahoma;color:#355F29;" height="14" width="14">
<br/>
</td>
</tr>
</tbody>
</table>
<br/>
<table style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;" class="ke-zeroborder" bgcolor="#FFFFFF" border="0" cellpadding="0" cellspacing="0" height="0">
<tbody>
<tr>
</tr>
<tr>
<td colspan="2" style="font-family:Tahoma;color:#FF9900;font-weight:bold;" align="left" height="20" valign="top">
<br/>
输入格式 Input Format
</td>
<td rowspan="2" style="font-family:Tahoma;color:#355F29;">
<br/>
</td>
</tr>
<tr>
<td style="font-family:Tahoma;color:#355F29;" align="left" valign="top" width="10">
 
</td>
<td style="font-family:Tahoma;color:#355F29;" align="left" valign="top" width="502">
第一行：一个整数n<br/>
接下来n行，每行n个整数（绝对值&lt;100），为题目中所描述的矩阵。<br/>
</td>
</tr>
<tr>
<td style="font-family:Tahoma;color:#355F29;" height="14" width="14">
<br/>
</td>
</tr>
</tbody>
</table>
<br/>
<table style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;" class="ke-zeroborder" bgcolor="#FFFFFF" border="0" cellpadding="0" cellspacing="0" height="0">
<tbody>
<tr>
<td colspan="2" style="font-family:Tahoma;color:#FF9900;font-weight:bold;" align="left" height="20" valign="top" width="512">
<br/>
输出格式 Output Format
</td>
<td rowspan="2" style="font-family:Tahoma;color:#355F29;">
<br/>
</td>
</tr>
<tr>
<td style="font-family:Tahoma;color:#355F29;" align="left" valign="top" width="10">
 
</td>
<td style="font-family:Tahoma;color:#355F29;" align="left" valign="top" width="502">
一个数，即Jimmy所能获得的最大收益。
</td>
</tr>
</tbody>
</table>
<span style="color:#FF9900;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;font-weight:bold;background-color:#FFFFFF;">样例输入 Sample Input </span> 
<p></p>
<p>
<span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;background-color:#FFFFFF;"><span>3</span><br/>
<span>0 -1 -1</span><br/>
<span>0 -12 0</span><br/>
<span>-19 0 0</span><br/>
</span> 
</p>
<div>
<br/>
</div>
<table style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;" class="ke-zeroborder" bgcolor="#FFFFFF" border="0" cellpadding="0" cellspacing="0" height="0">
<tbody>
<tr>
<td colspan="2" style="font-family:Tahoma;color:#FF9900;font-weight:bold;" align="left" height="20" valign="top" width="512">
<br/>
样例输出 Sample Output 
</td>
</tr>
</tbody>
</table>
<br/>
<p>
<span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;background-color:#FFFFFF;">0</span> 
</p>
<p>
<span style="color:#355F29;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:12px;background-color:#FFFFFF;"> </span>
</p>
<div>
数据范围和注释 Hint
</div>
样例解释：<br/>
无论Jimmy怎么挖矿，挖到的不是石头，就是TNT，总之无论如何都会亏损，所以选择不租用工具，收益为0<br/>
<br/>
数据范围：<br/>
对于30%的数据：0&lt;n&lt;=10<br/>
对于60%的数据：0&lt;n&lt;=100<br/>
对于100%的数据：0&lt;n&lt;=300<br/>
<p>
<br/>
</p>
