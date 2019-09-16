# 题目描述


<div>
<h2 style="text-align:left;">
<span style="font-family:&#34;黑体&#34;;font-size:18pt;font-weight:bold;">Problem 3</span><span style="font-family:&#34;Times New Roman&#34;;font-size:18pt;font-weight:bold;"></span> 
</h2>
<h2 style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">【问题描述】</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;"></span> 
</h2>
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"> </span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">对于</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;">正整数<span>N</span><span>，则</span><span>1</span><span>到</span><span>N</span><span>这</span><span>N</span><span>个数可以构成</span></span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">N!</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;">种排列，把这些排列按照</span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">字典序</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;">从小到大列出</span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">。</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
<p style="text-align:left;text-indent:21pt;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;">如<span>N=3</span><span>时，列出</span><span>1 2 3</span><span>，</span><span>1 3 2</span><span>，</span><span>2 1 3</span><span>，</span><span>2 3 1</span><span>，</span><span>3 1 2</span><span>，</span><span>3 2 1</span><span>六个排列</span></span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">。</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
<p style="text-align:left;text-indent:21pt;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">现在，给你排列<span>{P</span></span><span style="font-family:&#34;宋体&#34;;font-size:12pt;vertical-align:sub;">i</span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">}<span>，请你计算它后面的第</span><span>K</span><span>个排列</span><span>{Q</span></span><span style="font-family:&#34;宋体&#34;;font-size:12pt;vertical-align:sub;">i</span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">}<span>。</span></span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
<p style="text-align:left;text-indent:21pt;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">注意：这<span>N!</span><span>个排列是循环的，例如</span><span>3 1 2</span><span>后面的第</span><span>2</span><span>个排列是</span><span>1 2 3</span><span>。</span></span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
<h2 style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">【输入文件】</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;"></span> 
</h2>
<p style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"> </span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">两行，按如下格式：</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
<table width="452" height="22" align="center" style="padding:0pt 5.4pt;border-collapse:collapse;">
<tbody>
<tr>
<td width="448" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p>
N K
</p>
<p>
P1P2P3... ...PN
</p>
</td>
</tr>
</tbody>
</table>
<h2 style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">【输出文件】</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;"></span> 
</h2>
<p style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"> </span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">一行，按如下格式输出所求排列：</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
<table align="center" style="padding:0pt 5.4pt;border-collapse:collapse;">
<tbody>
<tr>
<td width="448" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:10.5pt;">Q1Q2Q3... ...QN</span> <span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<h2 style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">【输入样例】</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;"></span> 
</h2>
<p style="text-align:left;text-indent:21pt;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">3 2</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
<p style="text-align:left;text-indent:21pt;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1 3 2</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
<h2 style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">【输出样例】</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;"></span> 
</h2>
<p style="text-align:left;text-indent:21pt;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">2 3 1</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
<h2 style="text-align:left;">
<span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">【</span><span style="font-family:&#34;黑体&#34;;font-size:12pt;font-weight:normal;">数据规模</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;">】</span><span style="font-family:&#34;Times New Roman&#34;;font-size:12pt;font-weight:normal;"></span> 
</h2>
<p>
<span style="font-family:&#34;宋体&#34;;font-size:10.5pt;"> </span><span style="font-family:&#34;宋体&#34;;font-size:12pt;">四类测试点</span><span style="font-family:&#34;Times New Roman&#34;;font-size:10.5pt;"></span> 
</p>
<table style="padding:0pt 5.4pt;border-collapse:collapse;">
<tbody>
<tr>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">类别</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">数量</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="462" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">数据描述</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">3</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="462" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1&lt;=N&lt;=10   1&lt;=K&lt;=100000</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">2</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">3</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="462" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1&lt;=N&lt;=1000   1&lt;=K&lt;=100000</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">3</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">3</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="462" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1&lt;=N&lt;=1000   1&lt;=K&lt;=10^18</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">4</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="52" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
<td width="462" valign="top" style="border:0.5pt solid #000000;border-image:none;">
<p style="text-align:left;">
<span style="font-family:&#34;宋体&#34;;font-size:12pt;">1&lt;=N&lt;=100000   1&lt;=K&lt;=10^18</span><span style="font-family:&#34;Courier New&#34;;font-size:12pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<span style="font-family:&#34;Times New Roman&#34;;font-size:10.5pt;"><br/>
</span> 
</p>
</div>
