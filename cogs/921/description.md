# 题目描述


<p>
</p><table style="padding:0pt 5.4pt;border-collapse:collapse;">
<tbody>
<tr>
<td width="111" valign="top" style="background:#C0504D;border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="color:#FFFFFF;font-family:" calibri";font-size:16pt;font-weight:bold;"="">Problem </span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;">4</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
<td width="552" valign="top" style="background:#C0504D;border:1pt solid #CF7B79;">
<p>
<span style="color:#FFFFFF;font-family:" calibri";font-size:16pt;font-weight:bold;"="">上白泽慧音<span>(classroom.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">在幻想乡，上白泽慧音是以知识渊博闻名的老师。春雪异变导致人间之里的很多道路都被大雪堵塞，</span><span style="font-size:10.5pt;">使</span><span style="font-family:" calibri";font-size:10.5pt;"="">有的学生不能顺利地到达慧音所在的村庄。因此慧音决定换一个能够聚集最多人数的村庄作为新的教学地点。人间之里由<span>N</span><span>个村庄（编号为</span><span>1..N</span><span>）和</span><span>M</span><span>条道路组成，道路分为两种一种为单向通行的，一种为双向通行的，分别用</span><span>1</span><span>和</span><span>2</span><span>来标记。如果存在由村庄</span><span>A</span><span>到达村庄</span><span>B</span><span>的通路，那么我们认为可以从村庄</span><span>A</span><span>到达村庄</span><span>B</span></span><span style="font-size:10.5pt;">，记为<span>(A,B)</span><span>。当</span><span>(A,B)</span><span>和</span><span>(B,A)</span><span>同时满足时，我们认为</span><span>A,B</span><span>是绝对连通的，记为</span><span><a,b></a,b></span><span>。绝对连通区域是指一个村庄的集合，在这个集合中任意两个村庄</span><span>X,Y</span><span>都满足</span><span><x,y></x,y></span></span><span style="font-family:" calibri";font-size:10.5pt;"="">。</span><span style="font-size:10.5pt;">现在你的任务是，找出最大的绝对连通区域，并将这个绝对连通区域的村庄按编号依次输出。若存在两个最大的，输出字典序最小的，比如当存在<span>1,3,4</span><span>和</span><span>2,5,6</span><span>这两个最大连通区域时，输出的是</span><span>1,3,4</span><span>。</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="border:1pt solid #CF7B79;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输入格式</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
<td width="581" valign="top" style="border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">第<span>1</span><span>行：两个正整数</span><span>N,M</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">第<span>2..M+1</span><span>行：每行三个正整数</span><span>a,b,t, t = 1</span><span>表示存在从村庄</span><span>a</span><span>到</span><span>b</span><span>的单向道路，</span><span>t = 2</span><span>表示村庄</span><span>a,b</span><span>之间存在双向通行的道路。</span></span><span style="font-size:10.5pt;">保证每条道路只出现一次。</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">第<span>1</span><span>行：</span></span><span style="font-size:10.5pt;"> 1<span>个整数，表示最大的绝对连通区域包含的村庄个数</span></span><span style="font-family:" calibri";font-size:10.5pt;"="">。</span><span style="font-size:10.5pt;"></span> 
</p>
<p>
<span style="font-size:10.5pt;">第<span>2</span><span>行：若干个整数，依次输出最大的绝对连通区域所包含的村庄编号。</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="border:1pt solid #CF7B79;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">5 5</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">1 2 1</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">1 3 2</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">2 4 2</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">5 1 2</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">3 5 1</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="background:#EFD3D2;border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="font-size:10.5pt;">3</span><span style="font-size:10.5pt;"></span> 
</p>
<p>
<span style="font-size:10.5pt;">1 3 5</span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
<tr>
<td width="82" valign="top" style="border:1pt solid #CF7B79;">
<p>
<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
</p>
</td>
<td width="581" valign="top" style="border:1pt solid #CF7B79;" colspan="2">
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">对于<span>60%</span><span>的数据：</span><span>N &lt;= 200</span><span>且</span><span>M &lt;= 10,000</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
</p>
<p>
<span style="font-family:" calibri";font-size:10.5pt;"="">对于<span>100%</span><span>的数据：</span><span>N &lt;= 5,000</span><span>且</span><span>M &lt;= 50,000</span></span><span style="font-size:10.5pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<span><span style="line-height:normal;"><img alt="" src="/images/upload/image/20120715/20120715145928_57326.jpg"/><br/>
</span></span> 
<p></p>
