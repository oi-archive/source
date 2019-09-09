# 题目描述


<p>
	<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">题目描述</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">某商品推销员到某小区推销产品，产品推销除了商品质量好之外，还需要客户能影响和带动身边信赖他的人也购买，如果A购买了产品，那么信赖A的B就有可能也购买，那么信赖B的C就也可能成为潜在客户，依据这种信赖关系，就可能构成一个庞大的潜在客户网。聪明的推销员经过细心调查整理了这个小区里N个人的信赖关系，并且用1~N给这N个人编号。另外，这N个人中有P个潜在客户可能会被推销员直接说服购买产品，细心的推销员还估算了说服每个人具体需要花费的时间，那么请你帮推销员计算一下他最少需要花费多长时间来建立起这N个人的潜在客户网？如果不能把这N个人全部纳入潜在客户网，输出不能被纳入网络的人的编号。注意，信赖关系不一定是相互的啊！</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输人格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件第一行只有一个整数</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(n&lt;=3000)。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第二行是整数</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">p</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。表示能被说服的人数，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">p</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来的</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">p</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">行，每行有两个整数，第一个数是一个能被说服的人的编号，第二个数表示他被说服需要花费的时间。这个数不超过</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">20000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个时间单位。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">紧跟着一行只有一个整数</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">r</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">r</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">8000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。然后</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">r</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">行，每行两个正整数，表示数对</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(A, B)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，B信赖A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输出格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如果可以把N个人全部纳入潜在客户网，第一行输出</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">YES</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，并在第二行输出所需要花费的最少说服时间。否则输出</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">NO</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，并在第二行输出不能纳入网络的人编号中，编号最小的。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输入样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Example1:</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">1 10</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">2 100</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">1 3</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">2 3</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Example2:</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">1 100</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">4 200</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">1 2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">3 4</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">出</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Example1:</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">YES</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">110</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">Example2:</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">NO</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-align:justify;">
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">3</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">数据规模</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于30%的输入数据有n&lt;=10。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于100%的输入数据有n&lt;=3000。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
