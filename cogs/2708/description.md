# 题目描述


<h3>
【题目描述】
</h3>
<p>
    _Itachi是一只蒟蒻。
</p>
<p>
    一天，它准备了n道题准备颓题面。但是，由于题面太多了，而_Itachi特别懒，不喜欢做这么多琐碎的事情，于是，他决定：先将这n道题从1开始编上号，然后随机打乱他们的顺序，然后选择一个区间[L,R]（L&lt;R)，若编号在[L,R]之间的题目形成了不超过两个的连续区间，那么_Itachi就会一次性把这些题的题面都写好，否则就不写。现在他想知道自己有多大概率颓题面，请输出答案乘n*(n-1)/2的结果。
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
  第一行两个整数n，m,表示有n个题面要颓，并打乱m次顺序。
</p>
<p>
  接下来四个整数x0,a,b,c，定义
</p>
<p>
  x[i]=(a*x[i-1]*x[i-1]+b*x[i-1]+c)%n+1
</p>
<p>
  接下来四个整数y0,u,v,w,定义
</p>
<p>
  Y[i]=(u*y[i-1]*y[i-1]+v*y[i-1]+w)%n+1
</p>
<p>
  初始时a[i]=i,对于第i次操作，交换a[x[i]],a[y[i]];
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数表示_Itachi颓题面的概率乘n*(n-1)/2的结果。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5 5
</p>

<p>
2 1 2 5
</p>

<p>
2 3 4 4
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
9
</p>
</pre>
<h3>
【提示】
</h3>
<p>
</p><table class="MsoTableGrid" style="border-collapse:collapse;border:none;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">试题编号<span></span></span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">N=</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">M=</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">提示<span></span></span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">1</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">38</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">38</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">2</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">250</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">250</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">3</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">2333</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">2333</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">4</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">3456</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">3456</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">5</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">5678</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">5678</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">6</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">7890</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">7890</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">7</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">12345</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">12345</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">a=b=0</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">8</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">23456</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">23456</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">u=v=0</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">9</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">34567</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">34567</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">wys</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">10</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">45678</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">45678</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">wys</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">11</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">56789</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">10</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">12</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">67890</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">100</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">13</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">100000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">1000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">14</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">100000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">10000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">a=b=u=v=0</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">15</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">100000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">100000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">16</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">200000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">200000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">17</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">300000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">300000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">wys</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">18</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">400000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">400000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">wys </span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">19</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">500000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">500000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:solid windowtext 1.0pt;" width="103" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">20</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">600000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="84" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;">600000</span> 
</p>
</td>
<td style="border:solid windowtext 1.0pt;" width="120" valign="top">
<p class="MsoNormal">
<span style="font-size:16.0pt;font-family:隶书;"></span> 
</p>
<br/>
</td>
</tr>
</tbody>
</table>
<p></p>
<h3>
【来源】
</h3>
<p>
一只名字叫做_Itachi的蒟蒻（哈哈,_Itachi终于出题敢署名了）
</p>
