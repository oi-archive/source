# 题目描述


<p class="MsoNormal">
	<span style="font-family:宋体;"><b>【问题描述</b>】 </span> 
</p>
<p>
	<span class="MsoNormal"></span>一天，TZD想从0号村庄游历到n-1号村庄，这n个村庄由m条有向路连接，某两个村庄间可能有多条路相连。<br/>
当他在处于同一个强连通分支中的两个村庄间游历时，他可以租辆自行车来骑着，否则的话，就只能步行了。说的再详细点，对于从村庄a到村庄b的每一条路，如果这两个村庄处在同一个强连通分支中，（这意味着你可以从a到达b，也可以从b到达a）那么你可以租一辆自行车来骑行，所用时间为time[a][b]分钟，否则你必须步行通过，所用时间为2*time[a][b]分钟。<br/>
TZD想尽快到达目的地，他希望在此过程中步行的路不超过k条。现在你需要为他计算出：在满足步行的路不超过k条的情况下，到达目的地所用的最短时间。
</p>
<br/>
<p>
	【输入格式】<br/>
  输入文件有一组或多组数据每一组数据的第一行有三个整数：n,m,k，含义如上所述（1&lt;=n&lt;=100,  0&lt;=m&lt;=100 000,   0&lt;=k&lt;=10）。<br/>
接下来有m行，每行有3个整数a,b,time[a][b]，表示从村庄a至村庄b有一条路，骑自行车需time[a][b]分钟，而步行则需2*time[a][b]分钟。（0&lt;=a,b&lt;=n-1<span style="white-space:normal;">）</span><time[a][b]<=10,000）<br>
输入文件以单独的一行3个0表示结束。<br/>

</time[a][b]<=10,000）<br></p><p class="MsoNormal">
	<span lang="EN-US"><span lang="EN-US"></span></span><span lang="EN-US"><!--?XML:NAMESPACE PREFIX = O /--><!--?xml:namespace prefix = o /--><!--?xml:namespace prefix = o /--><o:p></o:p></span>【输出格式】
</p>
<br/>
<p class="MsoNormal">
	  对于每一组测试数据，在一行输出其答案，如果TZD无法在步行不超过k条路的情况下到达目的地，则输出-1。<br/>
<br/>
【样例】
</p>
<p class="MsoNormal">
	travela.in<br/>
5 6 3<br/>
0 1 1<br/>
0 2 2<br/>
2 1 1<br/>
1 3 3<br/>
3 1 3<br/>
3 4 2<br/>
0 0 0<br/>
<br/>
travela.out<br/>
9<span lang="EN-US"><o:p> <br/>
</o:p></span> 
</p>
