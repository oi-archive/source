# 题目描述


<p>
由于上一次的题目过水,出题人把题目彻底改了一下...
</p>
<h1>
【题目描述】
</h1>
<p>
<span style="font-size:18px;">罗马数字是欧洲在阿拉伯数字（实际上是印度数字）传入之前使用的一种数码，现在应用较少。它的产生晚于中国甲骨文中的数码，更晚于埃及人的十进位数字。但是，它的产生标志着一种古代文明的进步。</span> 
</p>
<p>
--------------------------------------------
</p>
<p>
现在有一些罗马数字和阿拉伯数字相互转换
</p>
<h2>
转换规则
</h2>
<p>
</p><table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="84">
<p class="MsoNormal" align="left">
<span style="font-size:12.0pt;font-family:宋体;color:#333333;">基本字符</span><span style="font-size:12.0pt;font-family:Arial;color:#333333;"></span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="48">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">I</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="48">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">V</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="60">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">X</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="60">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">L</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="84">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">C</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="84">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">D</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="109">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">M</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="84">
<p class="MsoNormal" align="left">
<span style="font-size:9.0pt;font-family:宋体;color:#333333;">相应的阿拉伯数字表示为</span><span style="font-size:9.0pt;font-family:Arial;color:#333333;"></span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="48">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">1</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="48">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">5</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="60">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">10</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="60">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">50</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="84">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">100</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="84">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">500</span> 
</p>
</td>
<td style="border:solid #E6E6E6 1.0pt;" valign="top" width="109">
<p class="MsoNormal" align="left">
<span style="font-size:22.0pt;font-family:Arial;color:#333333;">1000</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p></p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>1</span><span style="font-family:宋体;">、相同的数字连写，所表示的数等于这些数字相加得到的数，如：Ⅲ</span><span> = 3</span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>2</span><span style="font-family:宋体;">、小的数字在大的数字的右边，所表示的数等于这些数字相加得到的数。如：Ⅷ</span><span> = 8</span><span style="font-family:宋体;">；Ⅻ</span><span> =
12</span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>3</span><span style="font-family:宋体;">、小的数字</span><span>(</span><span style="font-family:宋体;">限于Ⅰ、</span><span>X </span><span style="font-family:宋体;">和</span><span>C)</span><span style="font-family:宋体;">在大的数字的左边，所表示的数等于大数减小数得到的数，如：Ⅳ</span><span>= 4</span><span style="font-family:宋体;">；Ⅸ</span><span>= 9</span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>4</span><span style="font-family:宋体;">、正常使用时，连写的数字重复不得超过三次。</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>5</span><span style="font-family:宋体;">、在一个数的上面画一条横线，表示这个数扩大</span><span>1000</span><span style="font-family:宋体;">倍。</span> 
</p>
<p class="MsoNormal" style="margin-left:15.8pt;text-indent:-15.8pt;" align="left">
<b><span style="font-family:宋体;">有几条须注意掌握：</span></b><b><span></span></b> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>1</span><span style="font-family:宋体;">、基本数字Ⅰ、</span><span>X </span><span style="font-family:宋体;">、</span><span>C </span><span style="font-family:宋体;">中的任何一个，自身连用构成数目，或者放在大数的右边连用构成数目，都不能超过三个；放在大数的左边只能用一个。</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>2</span><span style="font-family:宋体;">、不能把基本数字</span><span>V </span><span style="font-family:宋体;">、</span><span>L </span><span style="font-family:宋体;">、</span><span>D </span><span style="font-family:宋体;">中的任何一个作为小数放在大数的左边采用相减的方法构成数目；放在大数的右边采用相加的方式构成数目，只能使用一个。</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>3</span><span style="font-family:宋体;">、</span><span>V </span><span style="font-family:宋体;">和</span><span>X </span><span style="font-family:宋体;">左边的小数字只能用Ⅰ。</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>4</span><span style="font-family:宋体;">、</span><span>L </span><span style="font-family:宋体;">和</span><span>C </span><span style="font-family:宋体;">左边的小数字只能用</span><span>X</span><span style="font-family:宋体;">。</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>5</span><span style="font-family:宋体;">、</span><span>D </span><span style="font-family:宋体;">和</span><span>M </span><span style="font-family:宋体;">左边的小数字只能用</span><span>C</span><span style="font-family:宋体;">。</span><span></span> 
</p>
<h4>
<b><span style="font-family:宋体;">对照举例</span></b> 
</h4>
<p class="MsoNormal" style="margin-left:15.8pt;text-indent:-15.8pt;" align="left">
<b><span style="font-family:宋体;">个位数举例</span></b><b><span></span></b> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span style="font-family:宋体;">Ⅰ</span><span> --&gt;1 </span><span style="font-family:宋体;">；Ⅱ</span><span> --&gt;2</span><span style="font-family:宋体;">；</span> <span style="font-family:宋体;">Ⅲ</span><span> --&gt;3</span><span style="font-family:宋体;">；</span> <span style="font-family:宋体;">Ⅳ</span><span> --&gt;4 </span><span style="font-family:宋体;">；Ⅴ</span><span> --&gt;5 </span><span style="font-family:宋体;">；Ⅵ</span><span> --&gt;6</span><span style="font-family:宋体;">；Ⅶ</span><span> --&gt;7</span><span style="font-family:宋体;">；</span> <span style="font-family:宋体;">Ⅷ</span><span> --&gt;8 </span><span style="font-family:宋体;">；Ⅸ</span><span> --&gt;9 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.8pt;text-indent:-15.8pt;" align="left">
<b><span style="font-family:宋体;">十位数举例</span></b><b><span></span></b> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span style="font-family:宋体;">Ⅹ</span><span> --&gt;10</span><span style="font-family:宋体;">；</span> <span style="font-family:宋体;">Ⅺ</span><span> --&gt;11 </span><span style="font-family:宋体;">；Ⅻ</span><span> --&gt;12</span><span style="font-family:宋体;">；</span><span> XIII --&gt;13</span><span style="font-family:宋体;">；</span><span> XIV --&gt;14</span><span style="font-family:宋体;">；</span><span> XV --&gt;15 </span><span style="font-family:宋体;">；</span><span>XVI
--&gt;16 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>XVII
--&gt;17 </span><span style="font-family:宋体;">；</span><span>XVIII --&gt;18</span><span style="font-family:宋体;">；</span><span> XIX --&gt;19</span><span style="font-family:宋体;">；</span><span> XX
--&gt;20</span><span style="font-family:宋体;">；</span><span> XXI --&gt;21 </span><span style="font-family:宋体;">；</span><span>XXII --&gt;22 </span><span style="font-family:宋体;">；</span><span>XXIX
--&gt;29</span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>XXX
--&gt;30</span><span style="font-family:宋体;">；</span><span> XXXIV --&gt;34</span><span style="font-family:宋体;">；</span><span> XXXV --&gt;35 </span><span style="font-family:宋体;">；</span><span>XXXIX
--&gt;39</span><span style="font-family:宋体;">；</span><span> XL --&gt;40</span><span style="font-family:宋体;">；</span><span> L --&gt;50 </span><span style="font-family:宋体;">；</span><span>LI
--&gt;51</span><span style="font-family:宋体;">；</span> <span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>LV
--&gt;55</span><span style="font-family:宋体;">；</span><span> LX --&gt;60</span><span style="font-family:宋体;">；</span><span> LXV --&gt;65</span><span style="font-family:宋体;">；</span><span> LXXX --&gt;80</span><span style="font-family:宋体;">；</span><span> XC --&gt;90 </span><span style="font-family:宋体;">；</span><span>XCIII --&gt;93</span><span style="font-family:宋体;">；</span><span> XCV --&gt;95 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>XCVIII
--&gt;98</span><span style="font-family:宋体;">；</span><span> XCIX --&gt;99 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.8pt;text-indent:-15.8pt;" align="left">
<b><span style="font-family:宋体;">百位数举例</span></b><b><span></span></b> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>C
--&gt;100</span><span style="font-family:宋体;">；</span><span> CC --&gt;200 </span><span style="font-family:宋体;">；</span><span>CCC --&gt;300 </span><span style="font-family:宋体;">；</span><span>CD
--&gt;400</span><span style="font-family:宋体;">；</span><span> D --&gt;500 </span><span style="font-family:宋体;">；</span><span>DC --&gt;600 </span><span style="font-family:宋体;">；</span><span>DCC
--&gt;700</span><span style="font-family:宋体;">；</span> <span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>DCCC
--&gt;800 </span><span style="font-family:宋体;">；</span><span>CM --&gt;900</span><span style="font-family:宋体;">；</span><span> CMXCIX --&gt;999</span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.8pt;text-indent:-15.8pt;" align="left">
<b><span style="font-family:宋体;">千位数举例</span></b><b><span></span></b> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>M
--&gt;1000</span><span style="font-family:宋体;">；</span><span> MC --&gt;1100 </span><span style="font-family:宋体;">；</span><span>MCD --&gt;1400 </span><span style="font-family:宋体;">；</span><span>MD
--&gt;1500 </span><span style="font-family:宋体;">；</span><span>MDC --&gt;1600 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>MDCLXVI
--&gt;1666</span><span style="font-family:宋体;">；</span><span> MDCCCLXXXVIII --&gt;1888 </span><span style="font-family:宋体;">；</span><span>MDCCCXCIX --&gt;1899 </span><span style="font-family:宋体;">；</span><span>MCM --&gt;1900 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>MCMLXXVI
--&gt;1976</span><span style="font-family:宋体;">；</span><span> MCMLXXXIV --&gt;1984</span><span style="font-family:宋体;">；</span><span> MCMXC --&gt;1990 </span><span style="font-family:宋体;">；</span><span>MM
--&gt;2000 </span><span style="font-family:宋体;">；</span><span></span> 
</p>
<p class="MsoNormal" style="margin-left:15.75pt;text-indent:-15.75pt;" align="left">
<span>MMMCMXCIX
--&gt;3999</span><span style="font-family:宋体;">；</span> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
输入数据有许多行
</p>
<p>
每行一个阿拉伯数字或一个罗马数字
</p>
<p>
保证每个数字转化为阿拉伯数字后都<strong>不大于3999</strong> 
</p>
<h3>
【输出格式】
</h3>
<p>
将每行的数字相互转化并输出
</p>
<p>
如果输入为阿拉伯数字，则输出对应的罗马数字。
</p>
<p>
如果输入为罗马数字，则输出相应的阿拉伯数字。
</p>
<h3>
【样例输入】
</h3>
<p>
XI 
</p>
<p>
XII 
</p>
<p>
XIII 
</p>
<p>
XIV 
</p>
<p>
XV 
</p>
<p>
XVI 
</p>
<p>
17 
</p>
<p>
18 
</p>
<p>
19 
</p>
<p>
20 
</p>
<p>
21 
</p>
<p>
22 
</p>
<p>
XXIII 
</p>
<p>
XXIV
</p>
<h3>
【样例输出】
</h3>
<p>
11 
</p>
<p>
12 
</p>
<p>
13 
</p>
<p>
14 
</p>
<p>
15 
</p>
<p>
16 
</p>
<p>
XVII 
</p>
<p>
XVIII 
</p>
<p>
XIX 
</p>
<p>
XX 
</p>
<p>
XXI 
</p>
<p>
XXII 
</p>
<p>
23 
</p>
<p>
24
</p>
<h3>
【萌哒哒】
</h3>
<p>
罗马数字_百度百科 
</p>
<p>
<a href="http://baike.baidu.com/link?url=9H7mjJZBKCQ8yQmbwi8zACa9Rci4Wz_uNMr6G4xQPFKvwu27Ib-w0_onT9i6FyB3VT9o2PFFQaY22WxqwXKS7q" target="_blank">http://baike.baidu.com/link?url=9H7mjJZBKCQ8yQmbwi8zACa9Rci4Wz_uNMr6G4xQPFKvwu27Ib-w0_onT9i6FyB3VT9o2PFFQaY22WxqwXKS7q</a> 
</p>
<h3>
【来源】
</h3>
<p>
Designed by wolf  <img src="http://218.28.19.228/kindeditor/plugins/emoticons/images/29.gif" alt="" border="0"/> 
</p>
