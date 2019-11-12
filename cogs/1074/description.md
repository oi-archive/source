# 题目描述


<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">POJ 1401</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">求N!中末尾0的个数。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> 
</span></p><table width="100%" class="ke-zeroborder" style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;" border="0">
<tbody>
<tr>
<td style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<div>
Language:Default
</div>
<div style="font-family:Arial, Helvetica, sans-serif;text-align:center;font-size:18pt;font-weight:bold;color:blue;">
Factorial
</div>
<div style="font-family:Arial, Helvetica, sans-serif;text-align:center;font-size:12pt;">
<table align="center" style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<tbody>
<tr>
<td style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<b>Time Limit:</b> 1500MS
</td>
<td width="10" style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<br/>
</td>
<td style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<b>Memory Limit:</b> 65536K
</td>
</tr>
<tr>
<td style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<b>Total Submissions:</b> 12309
</td>
<td width="10" style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<br/>
</td>
<td style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif !important;">
<b>Accepted:</b> 7673
</td>
</tr>
</tbody>
</table>
</div>
<p style="font-family:Arial, Helvetica, sans-serif;font-size:18pt;font-weight:bold;color:blue;">
Description
</p>
<div style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:12pt;">
The most important part of a GSM network is so called Base Transceiver Station (BTS). These transceivers form the areas called cells (this term gave the name to the cellular phone) and every phone connects to the BTS with the strongest signal (in a little simplified view). Of course, BTSes need some attention and technicians need to check their function periodically. <br/>
<br/>
ACM technicians faced a very interesting problem recently. Given a set of BTSes to visit, they needed to find the shortest path to visit all of the given points and return back to the central company building. Programmers have spent several months studying this problem but with no results. They were unable to find the solution fast enough. After a long time, one of the programmers found this problem in a conference article. Unfortunately, he found that the problem is so called &#34;Travelling Salesman Problem&#34; and it is very hard to solve. If we have N BTSes to be visited, we can visit them in any order, giving us N! possibilities to examine. The function expressing that number is called factorial and can be computed as a product 1.2.3.4....N. The number is very high even for a relatively small N. <br/>
<br/>
The programmers understood they had no chance to solve the problem. But because they have already received the research grant from the government, they needed to continue with their studies and produce at least some results. So they started to study behaviour of the factorial function. <br/>
<br/>
For example, they defined the function Z. For any positive integer N, Z(N) is the number of zeros at the end of the decimal form of number N!. They noticed that this function never decreases. If we have two numbers N1 &lt; N2, then Z(N1) &lt;= Z(N2). It is because we can never &#34;lose&#34; any trailing zero by multiplying by any positive number. We can only get new and new zeros. The function Z is very interesting, so we need a computer program that can determine its value efficiently. <br/>
<br/>
</div>
<p style="font-family:Arial, Helvetica, sans-serif;font-size:18pt;font-weight:bold;color:blue;">
Input
</p>
<div style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:12pt;">
There is a single positive integer T on the first line of input. It stands for the number of numbers to follow. Then there is T lines, each containing exactly one positive integer number N, 1 &lt;= N &lt;= 1000000000.
</div>
<p style="font-family:Arial, Helvetica, sans-serif;font-size:18pt;font-weight:bold;color:blue;">
Output
</p>
<div style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:12pt;">
For every number N, output a single line containing the single non-negative integer Z(N).
</div>
<p style="font-family:Arial, Helvetica, sans-serif;font-size:18pt;font-weight:bold;color:blue;">
Sample Input
</p>
<pre class="sio">6
3
60
100
1024
23456
8735373</pre>
<p style="font-family:Arial, Helvetica, sans-serif;font-size:18pt;font-weight:bold;color:blue;">
Sample Output
</p>
<pre class="sio">0
14
24
253
5861
2183837</pre>
<p style="font-family:Arial, Helvetica, sans-serif;font-size:18pt;font-weight:bold;color:blue;">
Source
</p>
<div style="font-family:&#39;Times New Roman&#39;, Times, serif;font-size:12pt;">
<a href="http://poj.org/searchproblem?field=source&amp;key=Central+Europe+2000">Central Europe 2000</a> 
</div>
</td>
</tr>
</tbody>
</table>
 
<p></p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><br/>
</span> 
</p>
