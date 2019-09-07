# 题目描述


<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【问题描述】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">世博期间，上海的航空客运量大大超过了平时，随之而来的航空管制也频频发生。最近，小X就因为航空管制，连续两次在机场被延误超过了两小时。对此，小X表示很不满意。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">在这次来烟台的路上，小X不幸又一次碰上了航空管制。于是小X开始思考关于航空管制的问题。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">假设目前被延误航班共有n个，编号为1至n。机场只有一条起飞跑道，所有的航班需按某个顺序依次起飞（称这个顺序为</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">）。定义一个航班的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序号</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">为该航班在</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">中的位置，即是第几个起飞的航班。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:18pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">起飞序列还存在两类限制条件：</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:-18pt;margin-bottom:0pt;margin-left:36pt;" class="p0">
<span style="font-family:&#39;Symbol&#39;;font-size:10pt;mso-spacerun:&#39;yes&#39;;">· </span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">第一类（</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">最晚起飞时间限制</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">）：编号为i的航班</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序号</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">不得超过$k_i$</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">;</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:-18pt;margin-bottom:0pt;margin-left:36pt;" class="p0">
<span style="font-family:&#39;Symbol&#39;;font-size:10pt;mso-spacerun:&#39;yes&#39;;">· </span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">第二类（</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">相对起飞顺序限制</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">）：存在一些相对起飞顺序限制$(a,b)$，表示航班a的起飞时间必须早于航班b，即航班a的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序号</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">必须小于航班b的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序号</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:18pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">小X思考的第一个问题是，若给定以上两类限制条件，是否可以计算出一个可行的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">。第二个问题则是，在考虑两类限制条件的情况下，如何求出每个航班在所有可行的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">中的最小</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序号</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【输入格式】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">输入文件plane.in第一行包含两个正整数n和m，n表示航班数目，m表示第二类限制条件（</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">相对起飞顺序限制</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">）的数目。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">第二行包含n个正整数$k_1, k_2, …, k_n。$</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">接下来m行，每行两个正整数a和b，表示一对相对起飞顺序限制$(a,b)$，其中$1≤a,b≤n$, 表示航班a必须先于航班b起飞。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【输出格式】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">输出文件plane.out由两行组成。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">第一行包含n个整数，表示一个可行的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">，相邻两个整数用空格分隔。输入数据保证至少存在一个可行的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">。如果存在多个可行的方案，输出任意一个即可。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">第二行包含n个整数t</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;vertical-align:sub;mso-spacerun:&#39;yes&#39;;">1</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">, t</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;vertical-align:sub;mso-spacerun:&#39;yes&#39;;">2</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">, …, t</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;vertical-align:sub;mso-spacerun:&#39;yes&#39;;">n</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">，其中t</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;vertical-align:sub;mso-spacerun:&#39;yes&#39;;">i</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">表示航班i可能的最小</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序号</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">，相邻两个整数用空格分隔。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
 
</p>
<p style="text-align:left;margin-top:0pt;text-indent:-18pt;margin-bottom:0pt;margin-left:36pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p>
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输入1】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p>
 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">5 5</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">4 5 2 5 4</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">1 2</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 2</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">5 1</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 4</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 1</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输出1】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 5 1 4 2</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 4 1 2 1</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输入2】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">5 0</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 3 3 5 5</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输出2】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 2 1 5 4</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">1 1 1 4 4</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例说明】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">在样例1 中：</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 5 1 4 2满足了所有的限制条件，所有满足条件的</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;text-decoration:underline;mso-spacerun:&#39;yes&#39;;">起飞序列</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">有：</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">3 4 5 1 2      3 5 1 2 4      3 5 1 4 2      3 5 4 1 2</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">5 3 1 2 4      5 3 1 4 2      5 3 4 1 2</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">由于存在(5, 1)和(3, 1)两个限制，航班1只能安排在航班5和3之后，故最早起飞时间为3，其他航班类似。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">在样例2 中：</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">虽然航班4、5没有相对起飞顺序限制，但是由于航班1、2、3都必须安排在前3个起飞，所以4、5最早只能安排在第4个起飞。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【数据范围】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">对于30%数据：$n≤10；$</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">对于60%数据：$n≤500；$</span>
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">对于100%数据：$n≤2,000，m≤10,000。$</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【运行时限】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">1秒。</span><span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【运行空限】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;">512M。</span> 
</p>
<p style="text-align:left;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:12pt;mso-spacerun:&#39;yes&#39;;"><o:p><strong>注意：由于没有评测插件，这题只需输出第二问即可</strong></o:p></span> 
</p>
<!--EndFragment-->
