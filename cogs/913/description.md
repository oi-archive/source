# 题目描述


<div>
USACO/betsy(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
一个正方形的镇区分为 N<sup>2</sup> 个小方块（1 &lt;= N &lt;= 7）。农场位于方格的左上角，集市位于左下角。贝茜穿过小镇，从左上角走到左下角，刚好经过每个方格一次。当 N=3 时，贝茜的漫游路径可能如下图所示：
</p>
<pre>----------------
|    |    |    |
| F**********  |
|    |    | *  |
------------*---
|    |    | *  |
|  *****  | *  |
|  * | *  | *  |
---*---*----*---
|  * | *  | *  |
|  M | ******  |
|    |    |    |
----------------
</pre>
写一个程序，对于给出的 N 值，计算贝茜从农场走到集市有多少种唯一的路径。
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: betsy</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT</span> 
</h3>
<p>
行 <span style="font-family:&#39;Times New Roman&#39;;">1: </span>一个整数 <span style="font-family:&#39;Times New Roman&#39;;">N </span>（<span style="font-family:&#39;Times New Roman&#39;;">1 &lt;= N &lt;= 7</span>）
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file betsy.in)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">3</span></pre>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT</span> 
</h3>
只有一行。输出一个整数表示唯一路径的数量。
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file betsy.out)</span> 
</h3>
<pre><span style="font-family:&#39;Times New Roman&#39;;">2</span></pre>
<p>
 
</p>
