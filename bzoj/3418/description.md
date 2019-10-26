
# Description

<div class="content"><p><span style="font-size: medium">An exhibition of tapestries is opening in Byteotian Museum of Fine Arts. The main exhibition room, viewed from top, is a polygon (not necessarily convex). A tapestry is hanged on each wall of the room, each tapestry taking all the area of its wall.<br/>
A lamp has been installed in the room in order to illuminate the exhibition. The lamp is glowing uniformly in all directions. However, while some of the tapestries have to be flooded with light, others cannot be exposed to strong light.<br/>
Byteasar, the curator, has been moving the lamp around the room, but so far he is not satisfied with the results. Now he is terrified by the prospect of moving the tapestries around instead - this would require much effort, and the exhibition is to open soon. Perhaps you will be able to tell him if his attempts are doomed or not?<br/>
Your task is to determine if there is such a spot that placing the lamp in it satisfies the following:<br/>
• each wall is to be either completely illuminated or completely shaded, as required by the tapestry hanging on it; there can be no wall that is partly illuminated and partly shaded;<br/>
• if the lamp is located exactly on the wall or its extension, this wall is not illuminated;<br/>
• the lamp can neither be switched off nor taken away from the room; it has to be on while located (strictly) inside the room (i.e., it cannot be placed in a corner or on any wall).<br/>
</span></p>
<p><span style="font-family: 宋体; font-size: 14px; line-height: 20.909090042114258px;">给定一个不自交、无重点、无三点共线的多边形，多边形每条边都被要求必须有灯光直射或者必须没有，只有一部分照射或者没有照射到都是不合法的。求问是否存在一个点能够满足这个条件。</span></p></div>

# Input

<div class="content"><p><font size="4">There is a single integer t (1&lt;=t&lt;=20) in the first line of the standard input, denoting the number of data sets. The following lines describe these data sets.<br/>
The first line of a single description holds a single integer N （3&lt;=N&lt;=1000）, denoting the number of walls in the main exhibition room. Then the following N lines specify the room&#39;s shape. Each of those lines contains a pair of integers Xi and Yi (-30000&lt;=Xi,Yi&lt;=30000) for i=1,2…N, separated by a single space, denoting the coordinates of the room&#39;s corner or, in other words, the vertex of corresponding polygon. The vertices are given clockwise.<br/>
The next n lines specify the tapestries&#39; requirements. Each of those lines contains a single letter, S or C, denoting that the wall has to be illuminated or shaded, respectively. The letter in the i-th of these lines （for 1&lt;=i&lt;=N-1） regards the wall between the  -th and the (i+1)-th vertex. The letter in the last of these lines regards the wall between the last and the first vertex.<br/>
The polygon depicting the room&#39;s shape has no self-crossings, i.e., with the exception of successive sides, which share a common vertex, no two sides of the polygon share a common point. Furthermore, no three vertices of the polygon are collinear.<br/>
</font></p>
<p><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">第一行一个</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">t</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">代表数据组数</span></p>
<p class="MsoNormal" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;"><span style="font-family: 宋体;">每组数据第一行一个</span><span lang="EN-US">n</span><span style="font-family: 宋体;">代表多边形点数</span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;"><span style="font-family: 宋体;">接下来</span><span lang="EN-US">n</span><span style="font-family: 宋体;">行每行一个数代表第</span><span lang="EN-US">i</span><span style="font-family: 宋体;">个点的坐标，点按顺时针顺序给出。</span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;"><span style="font-family: 宋体;">最后</span><span lang="EN-US">n</span><span style="font-family: 宋体;">行每行一个</span><span lang="EN-US">S</span><span style="font-family: 宋体;">（代表需要照射）或者</span><span lang="EN-US">C</span><span style="font-family: 宋体;">（代表不需要照射）。前</span><span lang="EN-US">n-1</span><span style="font-family: 宋体;">行第</span><span lang="EN-US">i</span><span style="font-family: 宋体;">行的边是第</span><span lang="EN-US">i</span><span style="font-family: 宋体;">个给定的点和第</span><span lang="EN-US">i+1</span><span style="font-family: 宋体;">个给定的点的边，最后一行的边是第</span><span lang="EN-US">1</span><span style="font-family: 宋体;">和</span><span lang="EN-US">n</span><span style="font-family: 宋体;">个点之间的边。</span><span lang="EN-US"><o:p></o:p></span></p>
<p></p></div>

# Output

<div class="content"><p><font size="4">For each data set your program should print to the standard output a single line containing a single word:<br/>
• TAK (Polish for yes) if the lamp can be placed so as to satisfy all aforementioned requirements, or<br/>
• NIE (Polish for no) otherwise.<br/>
Example<br/>
In the figures below the examples, the thick sides denote the walls that have to be shaded while the remaining sides - the walls that have to be illuminated. The figure for the first example shows a correct placement of the lamp.<br/>
</font></p>
<p><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">每行一个</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">TAK</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">（代表存在）或</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">NIE</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">（代表不存在）</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
16<br/>
5 -3<br/>
4 -4<br/>
3 -7<br/>
0 -5<br/>
-3 -7<br/>
-4 -4<br/>
-5 -3<br/>
-1 -1<br/>
-4 3<br/>
-2 4<br/>
-1 2<br/>
0 7<br/>
1 2<br/>
2 4<br/>
4 3<br/>
1 -1<br/>
C<br/>
S<br/>
S<br/>
S<br/>
S<br/>
C<br/>
C<br/>
S<br/>
S<br/>
C<br/>
S<br/>
S<br/>
C<br/>
S<br/>
S<br/>
C<br/>
        <br/>
 <br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="265" width="198" alt="" src="/source/bzoj/3418/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS9hZmYoNSkuanBn.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢HJWJBSR提供译文">鸣谢HJWJBSR提供译文</a></p></div>

