# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
有N行M列的点组成一个点阵。你通过用水平和竖直的线段连接一些相邻的点画若干闭合的回路，将所有的点连接起来，组成一个图形。连的线被视为是内部和外部的界限。其中，有一些点（用*和#表示）不用被连接，且用*表示的点在必须在图形内部，用#表示的点必须在图形外部。<br/>
例如：（用＋表示点，－和｜表示线，ｘ表示图形内部）<br/>
<img src="/upload/image/20141216/20141216144250_39470.png" alt=""/><br/>
以及<br/>
<img src="/upload/image/20141216/20141216144307_61835.png" alt=""/>注意：这个点是在外部！<br/>
你要写一个程序来计算一共有多少种连线的方法。我们只关心它模一个大质数123456791的余数。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含两个正整数，分别表示行数N和列数M。<br/>
接下来N行，每行M个字符表示点的情况（用.*#来表示三种点）。<br/>
50%的数据满足：<br/>
总的方法数小于220000<br/>
100%的数据满足：<br/>
M≤12，N≤20
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示总方法数模123456791的余数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5 6<br/>
......<br/>
....*.<br/>
..#...<br/>
......<br/>
......
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
117
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI0">
<span style="font-family:黑体;mso-ascii-font-family:Arial;"><strong><span style="font-size:small;">【问题描述】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">有</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">列的点组成一个点阵。你通过用水平和竖直的线段连接一些相邻的点画<u>若干闭合的回路</u>，将所有的点连接起来，组成一个图形。连的线被视为是内部和外部的界限。其中，有一些点（用</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">*</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">#</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示）不用被连接，且用</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">*</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示的点在必须在图形内部，用</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">#</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示的点必须在图形外部。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">例如：（用＋表示点，－和｜表示线，ｘ表示图形内部）</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋－＋－＋－＋－＋－＋ </span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘｘｘｘｘｘｘｘｘ｜ </span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋ｘ＋－＋－＋ｘ﹡ｘ＋ </span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘ｜　　　｜ｘｘｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋－＋　＃　＋ｘ＋－＋ </span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;"> ｜ｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋－＋－＋　＋ｘ＋－＋ </span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘｘｘ｜　｜ｘｘｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋－＋－＋　＋－＋－＋</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">以及</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋－＋－＋－＋－＋</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘｘｘｘｘｘｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋ｘ＋－＋－＋ｘ＋</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘ｜　　　｜ｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋ｘ＋　＃　＋ｘ＋　　　注意：这个点是在外部！</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘ｜　　　｜ｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋ｘ＋－＋－＋ｘ＋</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">｜ｘｘｘｘｘｘｘ｜</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">＋－＋－＋－＋－＋</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">你要写一个程序来计算一共有多少种连线的方法。我们只关心它模一个大质数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">123456791</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的余数。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<span style="font-family:黑体;mso-ascii-font-family:Arial;"><strong><span style="font-size:small;">【输入格式】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输入的第一行包含两个正整数，分别表示行数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和列数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">接下来</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个字符表示点的情况（用</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">.*#</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">来表示三种点）。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">50%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的数据满足：</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">总的方法数小于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">220000</span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的数据满足：</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">12</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">20</span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<span style="font-family:黑体;mso-ascii-font-family:Arial;"><strong><span style="font-size:small;">【输出格式】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输出一个整数，表示总方法数模</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">123456791</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的余数。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<span style="font-family:黑体;mso-ascii-font-family:Arial;"><strong><span style="font-size:small;">【样例输入】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">5 6</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">......</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">....*.</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">..#...</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">......</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">......</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p><span style="font-size:small;font-family:&#39;Courier New&#39;;"> </span></o:p></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Courier New&#39;;"> </span></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<span style="font-family:黑体;mso-ascii-font-family:Arial;"><strong><span style="font-size:small;">【样例输出】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">117</span></span> 
</p>
</div>
</div>
