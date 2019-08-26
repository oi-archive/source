
# Description

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: medium"><span style="color: rgb(68,68,68); line-height: 140%">Byteasar intends to throw up a party. Naturally, he would like it to be a success. Furthermore, Byteasar is quite certain that to make it so it suffices if all invited guests know each other. He is currently trying to come up with a list of his friends he would like to invite. Byteasar has friends, where is divisible by 3. Fortunately, most of Byteasar&#39;s friends know one another. Furthermore, Byteasar recalls that he once attended a party where there were2/3 n of his friends, and where everyone knew everyone else. Unfortunately, Byteasar does not quite remember anything else from that party... In particular, he has no idea which of his friends attended it. Byteasar does not feel obliged to throw a huge party, but he would like to invite at least n/3of his friends. He has no idea how to choose them, so he asks you for help. </span></span></div>
<div style="line-height: 140%" align="left"><span style="font-size: medium">给定一张N（保证N是3的倍数）个节点M条边的图，并且保证该图存在一个大小至少为2N/3的团。</span></div>
<p></p>
<pre style="font-family: arial, verdana, helvetica, sans-serif! important"><span style="font-size: medium">请输出该图的任意一个大小为N/3的团。 一个团的定义为节点的一个子集，该子集中的点两两有直接连边。 输入： 第一行是两个整数N,M。 接下来有M行，每行两个整数A,B，表示A和B有连边。保证无重边。 输出： N/3个整数，表示你找到的团。 数据范围： </span></pre>
<p></p>
<div style="line-height: 140%" align="left"></div>
<p><span style="font-size: medium">3&lt;=N&lt;=3000,[3/2 n(2/3 n -1)]/2&lt;=M&lt;=[n(n-1)/2]</span></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">In the first line of the standard input two integers, n and M(3&lt;=N&lt;=3000,[3/2 n(2/3 n -1)]/2&lt;=M&lt;=[n(n-1)/2]), are given, separated by a single space. These denote the number of Byteasar&#39;s friends and the number of pairs of his friends who know each other, respectively. Byteasar&#39;s friends are numbered from 1 to <v:shapetype id="_x0000_t75" stroked="f" filled="f" path="m@4@5l@4@11@9@11@9@5xe" o:preferrelative="t" o:spt="75" coordsize="21600,21600"><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:connecttype="rect" gradientshapeok="t" o:extrusionok="f"></v:path><o:lock aspectratio="t" v:ext="edit"></o:lock></v:shapetype><v:shape id="_x0000_i1025" type="#_x0000_t75" style="width: 6.75pt; height: 5.25pt; mso-wrap-style: square; mso-position-horizontal-relative: page; mso-position-vertical-relative: page"><v:imagedata o:href="http://main.edu.pl/en/images/OI18/imp-en-tex.9.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image001.gif"></v:imagedata></v:shape>. Each of the following <v:shape id="_x0000_i1026" type="#_x0000_t75" style="width: 10.5pt; height: 5.25pt; mso-wrap-style: square; mso-position-horizontal-relative: page; mso-position-vertical-relative: page"><v:imagedata o:href="http://main.edu.pl/en/images/OI18/imp-en-tex.10.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image002.gif"></v:imagedata></v:shape>lines holds two integers separated by a single space. The numbers in line no.i+1(for i=1,2,...,m) are Ai and Bi(1&lt;=Ai&lt;Bi&lt;=N), separated by a single space, which denote that the persons Ai and Bi now each other. Every pair of numbers appears at most once on the input. <o:p></o:p></span></p>
<p></p></div>

# Output

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: 12pt; color: #444444; line-height: 140%">In the first and only line of the standard output your program should print N/3numbers, separated by single spaces, in increasing order. These number should specify the numbers of Byteasar&#39;s friends whom he should invite to the party. As there are multiple solutions, pick one arbitrarily. </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 10<br/>
2 5<br/>
1 4<br/>
1 5<br/>
2 4<br/>
1 3<br/>
4 5<br/>
4 6<br/>
3 5<br/>
3 4<br/>
3 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 4</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
Explanation of the example: Byteasar&#39;s friends numbered 1, 3, 4, 5 know one another. However, any pair of Byteasar&#39;s friends who know each other, like 2 and 4 for instance, constitutes a correct solution, i.e., such a pair needs not be part of aforementioned quadruple.</p><br/>
<p>请不要提交！</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢 Object022&amp;suhang">鸣谢 Object022&amp;suhang</a></p></div>

