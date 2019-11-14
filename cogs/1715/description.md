# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<div style="text-indent:21pt;">
<span style="font-size:medium;">对于序列A，它的逆序对数定义为满足<i>i</i>&lt;<i>j</i>，且A<i><sub>i</sub></i>&gt;A<i><sub>j</sub></i>的数对(<i>i</i>,<i>j</i>)的个数。给1到<i>n</i>的一个排列，按照某种顺序依次删除<i>m</i>个元素，你的任务是在每次删除一个元素之前统计整个序列的逆序对数。</span> 
</div>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<div>
<span style="font-size:medium;">输入第一行包含两个整数<i>n</i>和<i>m</i>，即初始元素的个数和删除的元素个数。以下<i>n</i>行每行包含一个1到<i>n</i>之间的正整数，即初始排列。以下<i>m</i>行每行一个正整数，依次为每次删除的元素。</span>
</div>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<div>
<span style="font-size:medium;">输出包含<i>m</i>行，依次为删除每个元素之前，逆序对的个数。</span> 
</div>
</div>
<h3>
【样例输入】
</h3>
<pre>  5 4
  1
  5
  3
  4
  2
  5
  1
  4
  2
  </pre>
<h3>
【样例输出】
</h3>
<pre> 5
  2
  2
  1</pre>
<pre>  
  样例解释
  (1,5,3,4,2)(1,3,4,2)(3,4,2)(3,2)(3)。
  </pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<span lang="EN-US" style="font-size:10.5pt;font-family:&#34;mso-bidi-font-size:12.0pt;mso-fareast-font-family:宋体;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">N&lt;=<st1:chmetcnv w:st="on" tcsc="0" numbertype="1" negative="False" hasspace="True" sourcevalue="100000" unitname="m">100000 M</st1:chmetcnv>&lt;=50000</span>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search="></a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=3295">耒阳大世界（衡阳八中） OJ 3295</a>
