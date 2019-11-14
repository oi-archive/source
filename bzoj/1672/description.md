
# Description

<div class="content"><p><span style="font-size: medium">Farmer John&#39;s cows, pampered since birth, have reached new heights of fastidiousness. They now require their barn to be immaculate. Farmer John, the most obliging of farmers, has no choice but hire some of the cows to clean the barn. Farmer John has N (1 &lt;= N &lt;= 10,000) cows who are willing to do some cleaning. Because dust falls continuously, the cows require that the farm be continuously cleaned during the workday, which runs from second number M to second number E during the day (0 &lt;= M &lt;= E &lt;= 86,399). Note that the total number of seconds during which cleaning is to take place is E-M+1. During any given second M..E, at least one cow must be cleaning. Each cow has submitted a job application indicating her willingness to work during a certain interval T1..T2 (where M &lt;= T1 &lt;= T2 &lt;= E) for a certain salary of S (where 0 &lt;= S &lt;= 500,000). Note that a cow who indicated the interval 10..20 would work for 11 seconds, not 10. Farmer John must either accept or reject each individual application; he may NOT ask a cow to work only a fraction of the time it indicated and receive a corresponding fraction of the salary. Find a schedule in which every second of the workday is covered by at least one cow and which minimizes the total salary that goes to the cows. </span></p>
<div><span style="font-size: medium">    约翰的奶牛们从小娇生惯养，她们无法容忍牛棚里的任何脏东西．约翰发现，如果要使这群有洁癖的奶牛满意，他不得不雇佣她们中的一些来清扫牛棚, 约翰的奶牛中有N(1≤N≤10000)头愿意通过清扫牛棚来挣一些零花钱．由于在某个时段中奶牛们会在牛棚里随时随地地乱扔垃圾，自然地，她们要求在这段时间里，无论什么时候至少要有一头奶牛正在打扫．需要打扫的时段从某一天的第M秒开始，到第E秒结束f0≤M≤E≤86399)．注意这里的秒是指时间段而不是时间点，也就是说，每天需要打扫的总时间是E-M+I秒．</span><span style="font-size: medium"> 约翰已经从每头牛那里得到了她们愿意接受的工作计划：对于某一头牛，她每天都愿意在</span><span style="font-size: medium">笫Ti，.T2秒的时间段内工作(M≤Ti≤马≤E)，所要求的报酬是S美元(0≤S≤500000)．与需打扫时段的描述一样，如果一头奶牛愿意工作的时段是每天的第10_20秒，那她总共工作的时间是11秒，而不是10秒．约翰一旦决定雇佣某一头奶牛，就必须付给她全额的工资，而不能只让她工作一段时间，然后再按这段时间在她愿意工作的总时间中所占的百分比来决定她的工资．现在请你帮约翰决定该雇佣哪些奶牛以保持牛棚的清洁，当然，在能让奶牛们满意的前提下，约翰希望使总花费尽量小．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: N, M, and E. * Lines 2..N+1: Line i+1 describes cow i&#39;s schedule with three space-separated integers: T1, T2, and S. </span></p>
<div><span style="font-size: medium">    第1行：3个正整数N，M，E，用空格隔开．</span></div>
<div><span style="font-size: medium">    第2到N+1行：第i+l行给出了编号为i的奶牛的工作计划，即3个用空格隔开的正整数Ti，T2，S．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: a single integer that is either the minimum total salary to get the barn cleaned or else -1 if it is impossible to clean the barn. </span></p>
<div><span style="font-size: medium">    输出一个整数，表示约翰需要为牛棚清理工作支付的最少费用．如果清理工作不可能完成，</span></div>
<div><span style="font-size: medium">那么输出-1.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 0 4  //三头牛,要打扫从0到4号stall<br/>
0 2 3  //一号牛,从0号stall打扫到2号,工资为3<br/>
3 4 2<br/>
0 0 1<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
FJ has three cows, and the barn needs to be cleaned from second 0 to second<br/>
4. The first cow is willing to work during seconds 0, 1, and 2 for a total<br/>
salary of 3, etc.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">约翰有</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">头牛，牛棚在第</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">秒到第</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">秒之间需要打扫．第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">头牛想要在第</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">秒内工作，为此她</span></font><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">要求的报酬是</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">美元．其余的依此类推．</span></font><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">约翰雇佣前两头牛清扫牛棚，可以只花</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">美元就完成一整天的清扫．</span></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

