
# Description

<div class="content"><p class="MsoNormal" align="center" style="text-align:center"><font face="宋体" size="5"><br/>
</font></p>
<p class="MsoNormal" style="text-indent:21.0pt"><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">Ryz</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">正在着手于训练一批精锐士兵。</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent:21.0pt"><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">Ryz</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">手下有</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">n*m</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">个士兵，排成一个</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">n</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">行</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">m</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">列的方阵。在一天中，</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">ryz</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">会对士兵下达一些命令，每个命令作用于一个小方阵的所有士兵，并且会增加他们的疲劳值。现在</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt">ryz</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">想知道，在一整天训练中，某些小方阵中的士兵的疲劳值总和是多少。</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt"><o:p></o:p></span></p>
<p class="MsoNormal"><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:
10.0pt"><o:p> </o:p></span></p>
<p class="MsoNormal"><font face="宋体" size="3"><br/>
</font></p>
<p></p></div>

# Input

<div class="content"><p></p>
<div></div>
<div>
<p class="MsoNormal" style="text-indent: 21pt; "><span style="font-size: 12pt; font-family: 宋体; ">第一行有</span><span lang="EN-US" style="font-size: 12pt; ">3</span><span style="font-size: 12pt; font-family: 宋体; ">个整数</span><span lang="EN-US" style="font-size: 12pt; ">n,m,k,q</span><span style="font-size: 12pt; font-family: 宋体; ">。分别表示方阵的行数、列数、指令数和询问数。</span><span lang="EN-US" style="font-size: 12pt; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span style="font-size: 12pt; font-family: 宋体; ">接下来</span><span lang="EN-US" style="font-size: 12pt; ">k</span><span style="font-size: 12pt; font-family: 宋体; ">行，每行</span><span lang="EN-US" style="font-size: 12pt; ">5</span><span style="font-size: 12pt; font-family: 宋体; ">个整数</span><span lang="EN-US" style="font-size: 12pt; ">x1,x2,y1,y2,s</span><span style="font-size: 12pt; font-family: 宋体; ">，描述一个指令，表示这条指令对所有坐标</span><span lang="EN-US" style="font-size: 12pt; ">(x,y)</span><span style="font-size: 12pt; font-family: 宋体; ">满足</span><span lang="EN-US" style="font-size: 12pt; ">x1&lt;=x&lt;=x2</span><span style="font-size: 12pt; font-family: 宋体; ">且</span><span lang="EN-US" style="font-size: 12pt; ">y1&lt;=y&lt;=y2</span><span style="font-size: 12pt; font-family: 宋体; ">的士兵产生了</span><span lang="EN-US" style="font-size: 12pt; ">s</span><span style="font-size: 12pt; font-family: 宋体; ">的疲劳值。</span><span lang="EN-US" style="font-size: 12pt; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span lang="EN-US" style="font-size: 12pt; ">(1&lt;=x1&lt;=x2&lt;=n</span><span style="font-size: 12pt; font-family: 宋体; ">，</span><span lang="EN-US" style="font-size: 12pt; ">1&lt;=y1&lt;=y2&lt;=m</span><span style="font-size: 12pt; font-family: 宋体; ">，</span><span lang="EN-US" style="font-size: 12pt; ">0&lt;=s&lt;=1000)<o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span style="font-size: 12pt; font-family: 宋体; ">接下来</span><span lang="EN-US" style="font-size: 12pt; ">q</span><span style="font-size: 12pt; font-family: 宋体; ">行，每行</span><span lang="EN-US" style="font-size: 12pt; ">2</span><span style="font-size: 12pt; font-family: 宋体; ">个整数</span><span lang="EN-US" style="font-size: 12pt; ">x,y(x,y&lt;=10^9)</span><span style="font-size: 12pt; font-family: 宋体; ">，描述一个询问，询问是被加密的。一个询问的密码是上一个询问的答案</span><span lang="EN-US" style="font-size: 12pt; ">(</span><span style="font-size: 12pt; font-family: 宋体; ">记为</span><span lang="EN-US" style="font-size: 12pt; ">c)</span><span style="font-size: 12pt; font-family: 宋体; ">，第一个询问的密码是</span><span lang="EN-US" style="font-size: 12pt; ">0</span><span style="font-size: 12pt; font-family: 宋体; ">。询问参数的计算方式如下：</span><span lang="EN-US" style="font-size: 12pt; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span lang="EN-US" style="font-size: 12pt; ">x1=c % n+1,x2=(c+x) % n+1</span><span style="font-size: 12pt; font-family: 宋体; ">，如果</span><span lang="EN-US" style="font-size: 12pt; ">x1&gt;x2</span><span style="font-size: 12pt; font-family: 宋体; ">则交换</span><span lang="EN-US" style="font-size: 12pt; ">x1</span><span style="font-size: 12pt; font-family: 宋体; ">和</span><span lang="EN-US" style="font-size: 12pt; ">x2<o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span lang="EN-US" style="font-size: 12pt; ">y1=c % m+1,y2=(c+y) % m +1</span><span style="font-size: 12pt; font-family: 宋体; ">，如果</span><span lang="EN-US" style="font-size: 12pt; ">y1&gt;y2</span><span style="font-size: 12pt; font-family: 宋体; ">则交换</span><span lang="EN-US" style="font-size: 12pt; ">y1</span><span style="font-size: 12pt; font-family: 宋体; ">和</span><span lang="EN-US" style="font-size: 12pt; ">y2<o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span style="font-size: 12pt; font-family: 宋体; ">询问所有坐标</span><span lang="EN-US" style="font-size: 12pt; ">(x,y)</span><span style="font-size: 12pt; font-family: 宋体; ">满足</span><span lang="EN-US" style="font-size: 12pt; ">x1&lt;=x&lt;=x2</span><span style="font-size: 12pt; font-family: 宋体; ">且</span><span lang="EN-US" style="font-size: 12pt; ">y1&lt;=y&lt;=y2</span><span style="font-size: 12pt; font-family: 宋体; ">的士兵的疲劳值总和。</span><span lang="EN-US" style="font-size: 12pt; "><o:p></o:p></span></p>
<p class="MsoNormal" style="text-indent: 21pt; "><span style="font-size: 12pt; font-family: 宋体; ">保证答案</span><span lang="EN-US" style="font-size: 12pt; ">&lt;2^64</span><span style="font-size: 12pt; font-family: 宋体; ">。</span><span lang="EN-US" style="font-size: 12pt; "><o:p></o:p></span></p>
<p class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; "><o:p> </o:p></span></p>
<p class="MsoNormal"><font face="宋体" size="3"><br/>
</font></p>
<p class="MsoNormal"></p>
</div></div>

# Output

<div class="content"><p></p>
<div></div>
<div>
<p class="MsoNormal" style="text-indent: 21pt; "><span style="font-size: 12pt; font-family: 宋体; ">对于每个询问，输出一行答案。</span><span lang="EN-US" style="font-size: 12pt; "><o:p></o:p></span></p>
<p class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; "><o:p> </o:p></span></p>
<p class="MsoNormal"></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
输入样例1<br/>
<br/>
4 5 3 3<br/>
<br/>
1 3 2 2 7<br/>
<br/>
2 4 2 3 5<br/>
<br/>
1 4 4 5 6<br/>
<br/>
1 2<br/>
<br/>
0 3<br/>
<br/>
2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
输出样例1<br/>
<br/>
24<br/>
<br/>
12<br/>
<br/>
46<br/>
<br/>
 <br/>
<br/>
第一次询问的是左上角坐标为(1,1),右下角坐标为(2,3)的这个矩形<br/>
<br/>
第二次询问的是左上角坐标为(1,3),右下角坐标为(1,5)的这个矩形<br/>
<br/>
第三次询问的是左上角坐标为(1,3)，右下角坐标为(3,5)这个矩形<br/>
<br/>
 <br/>
<br/>
 <br/>
<br/>
 <br/>
<br/>
 <br/>
<br/>
输入样例2<br/>
<br/>
5 5 5 5<br/>
<br/>
1 1 1 3 242<br/>
<br/>
1 4 4 5 83<br/>
<br/>
3 5 3 3 221<br/>
<br/>
2 2 1 3 254<br/>
<br/>
5 5 2 2 105<br/>
<br/>
0 1<br/>
<br/>
0 4<br/>
<br/>
2 1<br/>
<br/>
1 3<br/>
<br/>
0 1<br/>
<br/>
 <br/>
<br/>
输出样例2<br/>
<br/>
484<br/>
<br/>
0<br/>
<br/>
992<br/>
<br/>
442<br/>
<br/>
304<br/>
<br/>
 <br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;&lt;br /&gt;
font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;;mso-bidi-font-family:&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">对于</span><span lang="EN-US" style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:&#34;Times New Roman&#34;;&lt;br /&gt;
mso-fareast-font-family:宋体;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;&lt;br /&gt;
mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">100%</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;;mso-bidi-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:&lt;br /&gt;
ZH-CN;mso-bidi-language:AR-SA">的数据</span><span lang="EN-US" style="font-size:&lt;br /&gt;
12.0pt;mso-bidi-font-size:10.0pt;font-family:&#34;Times New Roman&#34;;mso-fareast-font-family:&lt;br /&gt;
宋体;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;&lt;br /&gt;
mso-bidi-language:AR-SA"> n,m&lt;=10^8,k&lt;=40000,q&lt;=100000</span><span style="font-size:12.0pt;mso-bidi-font-size:10.0pt;font-family:宋体;mso-ascii-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;;mso-bidi-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:&lt;br /&gt;
ZH-CN;mso-bidi-language:AR-SA">；</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Ryz">By Ryz</a></p></div>

