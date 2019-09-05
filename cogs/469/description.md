# 题目描述


<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【问题描述】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">栋栋有一块长方形的地，他在地上种了一种能量植物，这种植物可以采集太阳光的能量。在这些植物采集能量后，栋栋再使用一个能量汇集机器把这些植物采集到的能量汇集到一起。</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">栋栋的植物种得非常整齐，一共有<span style="font-family:Calibri;">n</span><span style="font-family:宋体;">列，每列有</span><span style="font-family:Calibri;">m</span><span style="font-family:宋体;">棵，植物的横竖间距都一样，因此对于每一棵植物，栋栋可以用一个坐标</span><span style="font-family:Calibri;">(x, y)</span><span style="font-family:宋体;">来表示，其中</span><span style="font-family:Calibri;">x</span><span style="font-family:宋体;">的范围是</span><span style="font-family:Calibri;">1</span><span style="font-family:宋体;">至</span><span style="font-family:Calibri;">n</span><span style="font-family:宋体;">，表示是在第</span><span style="font-family:Calibri;">x</span><span style="font-family:宋体;">列，</span><span style="font-family:Calibri;">y</span><span style="font-family:宋体;">的范围是</span><span style="font-family:Calibri;">1</span><span style="font-family:宋体;">至</span><span style="font-family:Calibri;">m</span><span style="font-family:宋体;">，表示是在第</span><span style="font-family:Calibri;">x</span><span style="font-family:宋体;">列的第</span><span style="font-family:Calibri;">y</span><span style="font-family:宋体;">棵。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">由于能量汇集机器较大，不便移动，栋栋将它放在了一个角上，坐标正好是<span style="font-family:Calibri;">(0, 0)</span><span style="font-family:宋体;">。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">能量汇集机器在汇集的过程中有一定的能量损失。如果一棵植物与能量汇集机器连接而成的线段上有<span style="font-family:Calibri;">k</span><span style="font-family:宋体;">棵植物，则能 量的损失为</span><span style="font-family:Calibri;">2k + 1</span><span style="font-family:宋体;">。例如，当能量汇集机器收集坐标为</span><span style="font-family:Calibri;">(2, 4)</span><span style="font-family:宋体;">的植物时，由于连接线段上存在一棵植物</span><span style="font-family:Calibri;">(1, 2)</span><span style="font-family:宋体;">，会产生</span><span style="font-family:Calibri;">3</span><span style="font-family:宋体;">的能量损失。注意，如果一棵植物与能量汇集机器连接的线段上没有植物，则能量损失为</span><span style="font-family:Calibri;">1</span><span style="font-family:宋体;">。现在要计算总的能量损失。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">下面给出了一个能量采集的例子，其中<span style="font-family:Calibri;">n = 5</span><span style="font-family:宋体;">，</span><span style="font-family:Calibri;">m = 4</span><span style="font-family:宋体;">，一共有</span><span style="font-family:Calibri;">20</span><span style="font-family:宋体;">棵植物，在每棵植物上标明了能量汇集机器收集它的能量时产生的能量损失。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p><img alt="" src="/images/energy2010.png" height="477" width="627"/></o:p></span> 
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">在这个例子中，总共产生了<span style="font-family:Calibri;">36</span><span style="font-family:宋体;">的能量损失。</span></span> 
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
 
</p>
<p>
<br/>
</p>
<p>
 
</p>
<!--EndFragment-->
<p>
<br/>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【输入格式】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><span style="font-family:宋体;">仅包含一行，为两个整数</span><span style="font-family:Calibri;">n</span><span style="font-family:宋体;">和</span><span style="font-family:Calibri;">m</span><span style="font-family:宋体;">。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【输出格式】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><span style="font-family:宋体;">仅包含一个整数，表示总共产生的能量损失。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输入1】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">5 4</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输出1】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">36</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输入2】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">3 4</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输出2】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">20</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【数据规模和约定】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">10%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">1 ≤ n, m ≤ 10</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">50%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">1 ≤ n, m ≤ 100</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">80%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">1 ≤ n, m ≤ 1000</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">90%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">1 ≤ n, m ≤ 10,000</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">100%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">1 ≤ n, m ≤ 100,000</span><span style="font-family:宋体;">。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
