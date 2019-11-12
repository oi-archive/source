# 题目描述


<div>
USACO/tour(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
你赢得了一场航空公司举办的比赛，奖品是一张加拿大环游机票。旅行在这家航空公司开放的最西边的城市开始，然后一直自西向东旅行，直到你到达最东边的城市，再由东向西返回，直到你回到开始的城市。每个城市只能访问一次，除了旅行开始的城市之外，这个城市必定要被访问两次（在旅行的开始和结束）。你不允许使用其他公司的航线或者用其他的交通工具。
</p>
<p>
给出这个航空公司开放的城市的列表，和两两城市之间的直达航线列表。找出能够访问尽可能多的城市的路线，这条路线必须满足上述条件，也就是从列表中的第一个城市开始旅行，访问到列表中最后一个城市之后再返回第一个城市。
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: tourus</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT</span> 
</h3>
<table border="1">
<tbody>
<tr>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">Line 1:</span> 
</td>
<td>
航空公司开放的城市数 <span style="font-family:&#39;Times New Roman&#39;;">N </span>和将要列出的直达航线的数量 <span style="font-family:&#39;Times New Roman&#39;;">V</span>。<span style="font-family:&#39;Times New Roman&#39;;">N </span>是一个不大于 <span style="font-family:&#39;Times New Roman&#39;;">100 </span>的正整数。<span style="font-family:&#39;Times New Roman&#39;;">V </span>是任意的正整数。
</td>
</tr>
<tr>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">Lines 2..N+1:</span> 
</td>
<td>
每行包括一个航空公司开放的城市名称。城市名称按照自西向东排列。不会出现两个城市在同一条经线上的情况。每个城市的名称都是一个字符串，最多<span style="font-family:&#39;Times New Roman&#39;;">15</span>字节，由拉丁字母表上的字母组成；城市名称中没有空格。
</td>
</tr>
<tr>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">Lines N+2..N+2+V-1:</span> 
</td>
<td>
每行包括两个城市名称（由上面列表中的城市名称组成），用一个空格分开。这样就表示两个城市之间的直达双程航线。
</td>
</tr>
</tbody>
</table>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT</span> 
</h3>
<table border="1">
<tbody>
<tr>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">Line 1:</span> 
</td>
<td>
按照最佳路线访问的不同城市的数量 <span style="font-family:&#39;Times New Roman&#39;;">M</span>。如果无法找到路线，输出 <span style="font-family:&#39;Times New Roman&#39;;">1</span>。
</td>
</tr>
</tbody>
</table>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file tourus.in)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">8 9	
Vancouver		
Yellowknife	
Edmonton
Calgary
Winnipeg
Toronto	
Montreal
Halifax	
Vancouver Edmonton
Vancouver Calgary	
Calgary Winnipeg
Winnipeg Toronto
Toronto Halifax
Montreal Halifax
Edmonton Montreal
Edmonton Yellowknife
Edmonton Calgary</span></pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file tourus.out)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">7</span></pre>
<p>
也就是<span style="font-family:&#39;Times New Roman&#39;;">: Vancouver, Edmonton, Montreal, Halifax, Toronto, Winnipeg, Calgary, </span>和 <span style="font-family:&#39;Times New Roman&#39;;">Vancouver </span>（回到开始城市，但是不算在不同城市之内）。
</p>
<p>
 
</p>
