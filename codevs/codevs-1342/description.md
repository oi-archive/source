<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<ul>
<li>
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>A</span></span></span><span style="">城市有一个巨大的圆形广场，为了绿化环境和净化空气，市政府决定沿圆形广场外圈种一圈树。园林部门得到指令后，初步规划出</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>n</span></span></span><span style="">个种树的位置，顺时针编号</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>1</span></span></span><span style="">到</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>n</span></span></span><span style="">。并且每个位置都有一个美观度</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>Ai</span></span></span><span style="">，如果在这里种树就可以得到这</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>Ai</span></span></span><span style="">的美观度。但由于</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>A</span></span></span><span style="">城市土壤肥力欠佳，两棵树决不能种在相邻的位置（</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>i</span></span></span><span style="">号位置和</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>i+1</span></span></span><span style="">号位置叫相邻位置。值得注意的是</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>1</span></span></span><span style="">号和</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>n</span></span></span><span style="">号也算相邻位置！）。</span></p>
<p><span style="">最终市政府给园林部门提供了</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>m</span></span></span><span style="">棵树苗并要求全部种上，请你帮忙设计种树方案使得美观度总和最大。如果无法将</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>m</span></span></span><span style="">棵树苗全部种上，给出无解信息。</span></p>
</li>
</ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入的第一行包含两个正整数</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>n</span></span></span><span style="">、</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>m</span></span></span><span style="">。</span></p>
<p><span style="">第二行</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>n</span></span></span><span style="">个整数</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>A<sub>i</sub></span></span></span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: small;">输出一个整数，表示最佳植树方案可以得到的美观度。如果无解输出&ldquo;</span><span style="font-family: 'Times New Roman', serif;"><span style="font-size: small;"><span lang="en-US">Error!<span style="font-family: 宋体, SimSun;">&rdquo;</span></span></span></span><span style="font-size: small;">，不包含引号。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<h2>【样例输入<span style="font-family: 'Times New Roman', serif;"><span>1</span></span>】</h2>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span>7 3</span></span></span></p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span>1 2 3 4 5 6 7</span></span></span></p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span><br></span></span></span></p>
<p> </p>
<h2>【样例输入<span style="font-family: 'Times New Roman', serif;"><span>2</span></span>】</h2>
<p> </p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span>7 4</span></span></span></p>
<p> </p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span>1 2 3 4 5 6 7</span></span></span></p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span><br></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<h2>【样例输出<span style="font-family: 'Times New Roman', serif;"><span>1</span></span>】</h2>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span>15</span></span></span></p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span><br></span></span></span></p>
<p> </p>
<h2>【样例输出<span style="font-family: 'Times New Roman', serif;"><span>2</span></span>】</h2>
<p> </p>
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>Error!</span></span></span></p>
<p><span style="font-family: 'Courier New', monospace;"><span style=""><span><br></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<h2>【数据规模】</h2>
<p><span style="">对于全部数据：</span><span style="font-family: 'Times New Roman', serif;"><span style=""><span>m&lt;=n</span></span></span><span style="">；</span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>-1000&lt;=Ai&lt;=1000</span></span></span></p>
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>N</span></span></span><span style="">的大小对于不同数据有所不同：</span></p>
&lt;colgroup&gt;&lt;col width="76"/&gt; &lt;col width="77"/&gt; &lt;col width="77"/&gt; &lt;col width="84"/&gt; &lt;/colgroup&gt;
<table cellpadding="7" cellspacing="0" style=""><tbody>
<tr valign="TOP">
<td width="76">
<p><span style="">数据编号</span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>N</span></span></span><span style="">的大小</span></p>
</td>
<td width="77">
<p><span style="">数据编号</span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>N</span></span></span><span style="">的大小</span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>1</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>30</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>11</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>200</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>35</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>12</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2007</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>3</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>40</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>13</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2008</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>4</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>45</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>14</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2009</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>5</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>50</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>15</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2010</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>6</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>55</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>16</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2011</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>7</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>60</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>17</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>2012</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>8</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>65</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>18</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>199999</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>9</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>200</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>19</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>199999</span></span></span></p>
</td>
</tr>
<tr valign="TOP">
<td width="76">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>10</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>200</span></span></span></p>
</td>
<td width="77">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>20</span></span></span></p>
</td>
<td width="84">
<p><span style="font-family: 'Times New Roman', serif;"><span style=""><span>200000</span></span></span></p>
</td>
</tr>
</tbody>
</table>
</div>
</div>