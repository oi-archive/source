# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">现在，保密成为一个很重要也很困难的问题。如果没有做好，后果是严重的。比如，有个人没有自己去修电脑，又没有拆硬盘，后来的事大家都知道了。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">当然，对保密最需求的当然是军方，其次才是像那个人。为了应付现在天上飞来飞去的卫星，军事基地一般都会建造在地下。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">某</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">国的军事基地是这样子的：地面上两排大天井共</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">n1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">个作为出入口，内部是许多除可以共享出入口外互不连通的空腔，每个空腔有且只有两个出入口，并且这两个出入口不会在同一排。为了方便起见，两排出入口分别编号为</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">1,3,5…</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">和</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">2,4,6…</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">并且最大的编号为</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">n1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">虽然上面扯了那么多关于保密的东西，但是其实解密也是一件很纠结的事情。但其实最简单直接暴力无脑的解密方法就是找个人去看看。。。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">我们有很牛</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">X</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">的特种部队，只需要派出一支特种部队到</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">国基地的某个出入口，那么和这个出入口直接相连的所有空腔都可以被探索，但也只有这些空腔可以被这支部队探索。现在有足够多的特种部队可以供你调遣，你必须使用他们调查完所有的</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:Calibri;">国基地内的空腔。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">当然，你的基地离</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国基地不会太近，周边的地图将会给你，表示为</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">n</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个检查点和</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">m</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">条连接这些点的道路，其中点</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到点</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">n1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">就是</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国基地的出入口，点</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">n</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是你的部队的出发点。对每条道路，有不同的通行时间</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">t</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和安全系数</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">s</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。因为情报部门只对单向的道路安全系数进行了评估，所以这些道路只允许单向通行，并且不会存在环。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">一支特种部队从你的基地出发，通过某条路径，到达某个</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国基地出入口，此时这支部队的危险性表示为总时间和这条路径经过的所有道路的安全系数和的比值。整个行动的危险性表示为你派出的所有部队的危险性之和。你需要使这个值最小的情况下探索整个</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国基地。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#34;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">快点完成这个任务，在</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国的叫兽宣布你是</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国人之前。</span><span lang="EN-US" style="font-size:12pt;font-family:&#34;"><o:p></o:p></span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">第一行</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个正整数</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">n</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">m (4 &lt;= n &lt;= 700, m &lt;= 100000) </span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示整个地区地图上的检查点和道路数。</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">下面</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">m</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">4</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个正整数</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">a, b, t, s(a, b &lt;=n, 1 &lt;= t, s &lt;= 10)</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示一条从</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">a</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">b</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的道路需时为</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">t</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，安全系数为</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">s</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">接下来</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个正整数</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">m1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">n1(m1 &lt;= 40000, n1 &lt; min{n, 161}), m1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国基地空腔的个数，</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">n1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">K</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">国基地出入口的个数。</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">再接下来</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">m1</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个正整数</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">u, v (u, v&lt;=n1, u</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是奇数，</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">v</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是偶数</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">)</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，表示每个空腔的</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个出入口。</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><span style="mso-spacerun:yes;">  </span><o:p></o:p></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p class="NOI" style="margin:13pt 0cm;">
 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><span style="mso-tab-count:1;">       </span></span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">一行，最小的危险性，保留一位小数。或者输出</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;">”-1”</span><span style="font-size:12pt;font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">（无引号）表示此任务不可能完成。</span><span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-size:12pt;font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>5 5
  
  5 1 10 1
  
  5 1 10 1
  
  5 2 9 1
  
  5 3 7 1
  
  5 4 8 1
  
  4 4
  
  1 2
  
  1 4
  
  3 2
  
  3 4
  
   
  
  </pre>
<h3>
【样例输出】
</h3>
<pre>17.0
  
  </pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
<p>
<br/>
<br/>
对30%的数据，n&lt;=30
</p>
<br/>
<p>
对60%的数据，n&lt;=300
</p>
<br/>
<p>
 
</p>
<br/>
<p>
另外 40%的数据n1&lt;=20
</p>
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search=Stage2 day2">Stage2 day2</a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=2285">耒阳大世界（衡阳八中） OJ 2285</a>
