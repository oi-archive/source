# 题目描述


<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">题目背景：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">幻想乡的魔法使，雾雨魔理沙，发明了一种有趣的魔法卡片。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">这种魔法卡片为正方形，分成若干个大小相同的方格，每个方格上都有一种印记，印记分为两种：<span>&#34;</span>绮罗印记<span>&#34; </span>和<span> &#34;</span>幽光印记<span>&#34;</span>。卡片上每一行，每一列的方格中都有两个<span> &#34;</span>绮罗印记<span>&#34;</span>，其他方格为<span> &#34;</span>幽光印记<span>&#34;</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">这种卡片的神奇之处就在于，你可以任意次数地交换任意两行的所有方格，或者交换任意两列的所有方格。如果两张卡片可以通过这种行列交换变成相同的卡片，我们就认为它们是相同的。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">琪露诺（<span>⑨</span>），希望知道在一定尺寸下，共有多少种不同的魔法卡片，你能告诉他吗？<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">问题描述：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">给定正整数<span> n </span>，对于一个<span> n*n </span>的<span>01</span>矩阵，如果每行元素之和都为<span> 2</span>，且每列元素之和都为<span> 2</span>，我们就称它是<span>“</span>可调整的<span>”</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">如果两个<span>“</span>可调整的<span>”</span>矩阵可以通过若干次交换矩阵的两行或两列变成相同的，我们认为它们是等价的<span>“</span>可调整的<span>”</span>矩阵。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">求不同的<span>“</span>可调整的<span>”</span>矩阵的个数，输出答案对<span> 998244353 </span>取模的结果。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">注意有多组数据。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">输入格式：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">第一行一个正整数<span> T</span>，表示数据组数。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">接下来<span>T</span>行，每行一个正整数<span> n</span>，表示矩阵的大小。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">输出格式：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">应包含<span>T</span>行，每行一个数，表示你的答案。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例数据<span>1</span>：<span></span></span></b> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="643">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">card.in</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">card.out</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">1</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">2</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">1</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例数据<span>2</span>：<span></span></span></b> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="643">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">card.in</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">card.out</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">2</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">3</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">4</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">1</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">2</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例解释：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">当<span>n = 3 </span>时有<span> 1 </span>种方案：<span></span></span> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="79">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">当<span>n = 4 </span>时有<span> 2 </span>种方案：<span></span></span> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="106">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="106">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="26">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">*</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">数据范围：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 20% </span>的数据，<span>1&lt;= n &lt;= 7</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 40% </span>的数据，<span>1 &lt;= n &lt;= 10</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 70% </span>的数据，<span>1 &lt;= n &lt;= 100</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于<span> 100% </span>的数据，<span>1 &lt;= n &lt;= 1000</span>，<span>T
&lt;= 10</span></span> 
</p>
