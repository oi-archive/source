

# PROGRAM NAME: milk6 


<h3 class="style7">
<strong>INPUT FORMAT (file milk6.in)</strong> 
</h3>
<table border="1">
<tbody>
<tr>
<td class="style7">
第一行:
</td>
<td class="style7">
两个整数N(2&lt;=N&lt;=32)、M(0&lt;=M&lt;=1000), N表示仓库的数目，M表示运输卡车的数量。仓库1 代表发货工厂，仓库N 代表坏牛奶要发往的零售商。
</td>
</tr>
<tr>
<td class="style7">
第2..M+1行:
</td>
<td class="style7">
每行3个整数 Si, Ei, Ci. Si ,Ei表示这 辆卡车的出发仓库，目的仓库。Ci(0 &lt;= C i &lt;= 2,000,000) 表示让这辆卡车停止运输的损失
</td>
</tr>
</tbody>
</table>
<h3 class="style7">
OUTPUT FORMAT
</h3>
<p>
<span class="style7">第1行两个整数c、t,c表示最小的损失，T表示要停止的最少卡车数。接下来t 行表示你要停止哪几条线路。如果有多种方案使损失最小，输出停止的线路最少的方案。</span> 
</p>
<h3 class="style7">
SAMPLE INPUT (file milk6.in)
</h3>
4 5<br/>
1 3 100<br/>
3 2 50<br/>
2 4 60<br/>
1 2 40<br/>
2 3 80
<h3 class="style7">
SAMPLE OUTPUT (file milk6.out)
</h3>
<span class="style7">60 1 3</span> 
<p>
 
</p>
