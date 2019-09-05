# 题目描述


<div>
USACO/milk6(译by Twink)
<hr/>
</div>
<p>
描述
</p>
<p class="style7">
你第一天接手光明牛奶公司就发生了一件倒霉的事情：公司不小心发送了一批坏牛奶。很不幸，你发现这件事的时候，坏牛奶已经进入了送货网。这个送货网很大，而且关系复杂。你知道这批牛奶要发给哪个零售商，但是要把这批牛奶送到他手中有许多种途径。送货网由一些仓库和运输卡车组成，每辆卡车都在各自固定的两个仓库之间单向运输牛奶。在追查这些坏牛奶的时候，有必要保证它不被送到零售商手里，所以必须使某些运输卡车停止运输，但是停止每辆卡车都会有一定的经济损失。你的任务是，再保证坏牛奶不送到零售商的前提下，制定出停止卡车运输的方案，使损失最小。
</p>
<h3 class="style7">
<strong>PROGRAM NAME: milk6 </strong> 
</h3>
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
