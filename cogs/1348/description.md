# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<div style="margin:0cm 45.3pt 0pt 15.55pt;line-height:13.25pt;" align="left">
<span style="font-size:medium;"><span style="color:black;">煤矿工地可以看成是由隧道连接挖煤点组成的无向图。为安全起见，希望在工地发生事故</span><span style="color:black;">时所有挖煤点的工人都能有一条出路逃到救援出口处。于是矿主决定在某些挖煤点设立救援出</span><span style="color:black;">口，使得无论哪一个挖煤点坍塌之后，其他挖煤点的工人都有一条道路通向救援出口。</span><span style="color:black;">请写一个程序，用来计算至少需要设置几个救援出口，以及不同最少救援出口的设置方案总数。</span></span> 
</div>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;"><span style="color:black;">输入文件有若干组数据，每组数据的第一行是一个正整数</span><span style="color:black;"> N</span><span style="color:black;">（</span><span style="color:black;">N≤500</span><span style="color:black;">），表示工地的隧道数，接下来的</span><span style="color:black;"> N </span><span style="color:black;">行每行是用空格隔开的两个整数</span><span style="color:black;"> S </span><span style="color:black;">和</span><span style="color:black;"> T</span><span style="color:black;">，表示挖煤点</span></span><span style="font-size:medium;"><span style="color:black;"><span style="font:7pt &#39;Times New Roman&#39;;"> </span></span><span style="color:black;">S </span><span style="color:black;">与挖煤点</span><span style="color:black;"> T </span><span style="color:black;">由隧道直接连接。输入数据以</span><span style="color:black;"> 0 </span><span style="color:black;">结尾。</span></span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">输入文件中有多少组数据，输出文件</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> output.txt </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">中就有多少行。每行对应一组输入数据的</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;"> </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">结果。其中第</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> i </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">行以</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> Case i: </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">开始（注意大小写，</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US">Case </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">与</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> i </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">之间有空格，</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US">i </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">与</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US">:</span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">之间无空格，</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US">: </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">之后有空格），其后是用空格隔开的两个正整数，第一个正整数表示对于第</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> i </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">组输入数据至少需</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;"> </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">要设置几个救援出口，第二个正整数表示对于第</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> i </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">组输入数据不同最少救援出口的设置方案总</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;"> </span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">数。输入数据保证答案小于</span><span style="color:black;font-family:&#34;mso-bidi-font-size:12.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;mso-fareast-font-family:宋体;" lang="EN-US"> 2^64</span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">。输出格式参照以下输入输出样例。</span></span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>9                      
1 3                    
4 1
3 5
1 2
2 6
1 5
6 3
1 6
3 2
6
1 2
1 3
2 4
2 5
3 6
3 7
0
</pre>
<h3>
【样例输出】
</h3>
<pre>Case 1: 2 4
Case 2: 4 1
</pre>
<h3>
【提示】
</h3>
<p>
Case 1 的四组解分别是(2,4),(3,4),(4,5),(4,6)；
</p>
<p>
Case 2 的一组解为(4,5,6,7)。
</p>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search=day1">day1</a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=2730">耒阳大世界（衡阳八中） OJ 2730</a>
