# 题目描述


<h3>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">题目描述：</span><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">N<span style="font-family:宋体;">块长度分别为</span><span style="font-family:&#39;Times New Roman&#39;;">1</span><span style="font-family:宋体;">到</span><span style="font-family:&#39;Times New Roman&#39;;">N</span><span style="font-family:宋体;">的木板，</span></span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">现在要将这</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">N</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">条木板排成漂亮的形状，所谓漂亮的形状，是指对于不在最边上的木板，两边相邻的木板要么都比它高，要么都比它低。</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">N</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">条木板有若干种漂亮的排列方法，现将这些排列按字典排序，即第一块木板较短的排前面，若第一条木板相同，则第二条木板较短的排前面，以此类推；最后，从</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">1</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">开始对这些排列方法编号。</span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">（如用<span style="font-family:&#39;Times New Roman&#39;;">3</span><span style="font-family:宋体;">块木板可以排成</span><span style="font-family:&#39;Times New Roman&#39;;">132</span><span style="font-family:宋体;">，</span><span style="font-family:&#39;Times New Roman&#39;;">213</span><span style="font-family:宋体;">，</span><span style="font-family:&#39;Times New Roman&#39;;">312</span><span style="font-family:宋体;">三个不同的序列，编号分别对应</span><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">à</span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">132<span style="font-family:宋体;">；  </span><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">à</span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">213<span style="font-family:宋体;">；</span><span style="font-family:&#39;Times New Roman&#39;;">3</span></span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">à</span><span style="color:#000000;font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">312<span style="font-family:宋体;">），</span></span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">现输入木板块数</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">N</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">和编号</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">C</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">，要求按顺序输出这</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">N</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;">条木板的长度。</span><span style="font-family:&#34;font-size:10.5pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:5pt;margin-bottom:5pt;" class="p0">
<span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">输入：</span><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">输入文件的第一行包括一个整数<span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> (1 &lt;= K &lt;= 100)</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">表示输入数据的组数。</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">接下来是<span style="font-family:&#39;Times New Roman&#39;;">K</span><span style="font-family:宋体;">行，每行表示一组输入数据。每行包括两个用空格分开的整数</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">N</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">，</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> C (1 &lt;= N &lt;= 20),</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">N<span style="font-family:宋体;">表示栅栏中木板的数目，</span><span style="font-family:&#39;Times New Roman&#39;;">C</span><span style="font-family:宋体;">是这个栅栏在目录中的号码。</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">你可以这样设想，有<span style="font-family:&#39;Times New Roman&#39;;">20</span><span style="font-family:宋体;">块木板的所有漂亮栅栏的编号可以用一个</span><span style="font-family:&#39;Times New Roman&#39;;">64</span><span style="font-family:宋体;">位的无符号整数变量表示</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">(long long in C/C++, int64 in FreePascal)</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">。你还可以设想输入数据是正确的，特别是<span style="font-family:&#39;Times New Roman&#39;;">C</span><span style="font-family:宋体;">最少为</span><span style="font-family:&#39;Times New Roman&#39;;">1</span><span style="font-family:宋体;">而且不会超过有</span><span style="font-family:&#39;Times New Roman&#39;;">N</span><span style="font-family:宋体;">块木板的漂亮栅栏编号。</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><br/>
</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">输出：</span><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">每组数据只有一行输出，表示第有<span style="font-family:&#39;Times New Roman&#39;;">N</span><span style="font-family:宋体;">木板的第</span><span style="font-family:&#39;Times New Roman&#39;;">C</span><span style="font-family:宋体;">个栅栏的样子。这行序列的每个数用空格间隔。</span></span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:5pt;margin-bottom:5pt;" class="p0">
<span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">样例输入：</span><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">2</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">2 1</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">3 3</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">样例输出：</span><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">1 2</span><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">2 3 1</span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">提示：</span></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"></span></span></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;">来源：</span></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;"><span style="color:#0000FF;font-family:&#34;font-size:18pt;font-weight:bold;mso-spacerun:&#34;"><span style="font-family:&#34;font-size:12pt;mso-spacerun:&#34;">CEOI2002</span></span></span> 
</p>
<!--EndFragment-->   
</h3>
