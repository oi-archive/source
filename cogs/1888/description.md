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
Crash小朋友最近迷上了一款游戏——文明5(Civilization V)。在这个游戏中，玩家可以建立和发展自己的国家，通过外交和别的国家交流，或是通过战争征服别的国家。<br/>
现在Crash已经拥有了一个N个城市的国家，这些城市之间通过道路相连。由于建设道路是有花费的，因此Crash只修建了N-1条道路连接这些城市，不过可以保证任意两个城市都有路径相通。<br/>
在游戏中，Crash需要选择一个城市作为他的国家的首都，选择首都需要考虑很多指标，有一个指标是这样的：<br/>
<img src="/upload/image/20141217/20141217170221_94257.bmp" alt=""/><br/>
其中S(i)表示第i个城市的指标值，dist(i, j)表示第i个城市到第j个城市需要经过的道路条数的最小值，k为一个常数且为正整数。<br/>
因此Crash交给你一个简单的任务：给出城市之间的道路，对于每个城市，输出这个城市的指标值，由于指标值可能会很大，所以你只需要输出这个数mod10007的值。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包括两个正整数N和k。<br/>
下面有N-1行，每行两个正整数u、v(1 ≤u, v≤N)，表示第u个城市和第v个城市之间有道路相连。这些道路保证能符合题目的要求。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出共N行，每行一个正整数，第i行的正整数表示第i个城市的指标值mod10007的值。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5 2<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
10<br/>
7<br/>
23<br/>
18<br/>
18
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
20%的数据满足N≤ 5000、k≤ 30。<br/>
50%的数据满足N≤ 50000、k≤30。<br/>
100%的数据满足N≤ 50000、k≤ 150。
</div>
<h3>
【特别说明】
</h3>
<div class="pdcont">
由于数据大小限制为5MB，我只好对测试时的输入文件进行压缩处理。下面的函数可以将压缩的输入文件转化为原始输入文件。（函数从infile中读入压缩的输入文件，将解压缩后的输入文件输出到outfile中）<br/>
C/C++版本：<br/>
void Uncompress(FILE *infile, FILE *outfile)<br/>
{<br/>
int N, k, L, i, now, A, B, Q, tmp;<br/>
fscanf(infile, &#34;%d%d%d&#34;, &amp;N, &amp;k, &amp;L);<br/>
fscanf(infile, &#34;%d%d%d%d&#34;, &amp;now, &amp;A, &amp;B, &amp;Q);<br/>
fprintf(outfile, &#34;%d %d\n&#34;, N, k);<br/>
for (i = 1; i &lt; N; i ++)<br/>
{<br/>
now = (now * A + B) % Q;<br/>
tmp = (i &lt; L) ? i : L;<br/>
fprintf(outfile, &#34;%d %d\n&#34;, i - now % tmp, i + 1);<br/>
}<br/>
}<br/>
<br/>
Pascal版本：<br/>
procedure Uncompress(varinfile, outfile : text);<br/>
var<br/>
N, k, L, i, now, A, B, Q, tmp : longint;<br/>
begin<br/>
read(infile, N, k, L, now, A, B, Q);<br/>
writeln(outfile, N, &#39; &#39;, k);<br/>
for i := 1 to N - 1 do<br/>
begin<br/>
now := (now * A + B) mod Q;<br/>
if i &lt; L then tmp := i else tmp := L;<br/>
writeln(outfile, i - now mod tmp, &#39; &#39;, i + 1);<br/>
end;<br/>
end;<br/>
<br/>
下面给出一个具体的例子。civiliazation_compressed.in表示压缩的输入文件，civilization.in表示解压缩后的输入文件。<br/>
civilization_compressed.in<br/>
7 26 4<br/>
29643 2347 5431 54209<br/>
<br/>
civilization.in<br/>
7 26<br/>
1 2<br/>
2 3<br/>
2 4<br/>
3 5<br/>
4 6<br/>
5 7
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<h3>
【问题描述】
</h3>
<div class="probcontent">
Crash小朋友最近迷上了一款游戏——文明5(Civilization V)。在这个游戏中，玩家可以建立和发展自己的国家，通过外交和别的国家交流，或是通过战争征服别的国家。<br/>
现在Crash已经拥有了一个N个城市的国家，这些城市之间通过道路相连。由于建设道路是有花费的，因此Crash只修建了N-1条道路连接这些城市，不过可以保证任意两个城市都有路径相通。<br/>
在游戏中，Crash需要选择一个城市作为他的国家的首都，选择首都需要考虑很多指标，有一个指标是这样的：<br/>
<img width="160" height="64" alt="" src="/RequireFile.do?fid=tJ72G7EF"/><br/>
其中S(i)表示第i个城市的指标值，dist(i, j)表示第i个城市到第j个城市需要经过的道路条数的最小值，k为一个常数且为正整数。<br/>
因此Crash交给你一个简单的任务：给出城市之间的道路，对于每个城市，输出这个城市的指标值，由于指标值可能会很大，所以你只需要输出这个数mod10007的值。<br/>
<br/>
 
</div>
<h3>
【输入格式】
</h3>
<div class="probcontent">
输入的第一行包括两个正整数N和k。<br/>
下面有N-1行，每行两个正整数u、v(1 ≤u, v≤N)，表示第u个城市和第v个城市之间有道路相连。这些道路保证能符合题目的要求。<br/>
<br/>
 
</div>
<h3>
【输出格式】
</h3>
<div class="probcontent">
输出共N行，每行一个正整数，第i行的正整数表示第i个城市的指标值mod10007的值。<br/>
<br/>
 
</div>
<h3>
【样例输入】
</h3>
<div class="probexample">
5 2<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
<br/>
 
</div>
<h3>
【样例输出】
</h3>
<div class="probexample">
10<br/>
7<br/>
23<br/>
18<br/>
18<br/>
<br/>
 
</div>
<h3>
【数据范围】
</h3>
<div class="probcontent">
20%的数据满足N≤ 5000、k≤ 30。<br/>
50%的数据满足N≤ 50000、k≤30。<br/>
100%的数据满足N≤ 50000、k≤ 150。<br/>
<br/>
 
</div>
<h3>
【特别说明】
</h3>
<div class="probcontent">
由于数据大小限制为5MB，我只好对测试时的输入文件进行压缩处理。下面的函数可以将压缩的输入文件转化为原始输入文件。（函数从infile中读入压缩的输入文件，将解压缩后的输入文件输出到outfile中）<br/>
C/C++版本：<br/>
void Uncompress(FILE *infile, FILE *outfile)<br/>
{<br/>
    int N, k, L, i, now, A, B, Q, tmp;<br/>
    fscanf(infile, &#34;%d%d%d&#34;, &amp;N, &amp;k, &amp;L);<br/>
    fscanf(infile, &#34;%d%d%d%d&#34;, &amp;now, &amp;A, &amp;B, &amp;Q);<br/>
    fprintf(outfile, &#34;%d %d\n&#34;, N, k);<br/>
    for (i = 1; i &lt; N; i ++)<br/>
        {<br/>
        now = (now * A + B) % Q;<br/>
        tmp = (i &lt; L) ? i : L;<br/>
        fprintf(outfile, &#34;%d %d\n&#34;, i - now % tmp, i + 1);<br/>
        }<br/>
}<br/>
<br/>
Pascal版本：<br/>
procedure Uncompress(varinfile, outfile : text);<br/>
var<br/>
N, k, L, i, now, A, B, Q, tmp : longint;<br/>
begin<br/>
    read(infile, N, k, L, now, A, B, Q);<br/>
    writeln(outfile, N, &#39; &#39;, k);<br/>
    for i := 1 to N - 1 do<br/>
        begin<br/>
            now := (now * A + B) mod Q;<br/>
            if i &lt; L then tmp := i else tmp := L;<br/>
            writeln(outfile, i - now mod tmp, &#39; &#39;, i + 1);<br/>
        end;<br/>
end;<br/>
<br/>
下面给出一个具体的例子。civiliazation_compressed.in表示压缩的输入文件，civilization.in表示解压缩后的输入文件。<br/>
civilization_compressed.in <br/>
7 26 4<br/>
29643 2347 5431 54209<br/>
<br/>
civilization.in<br/>
7 26<br/>
1 2<br/>
2 3<br/>
2 4<br/>
3 5<br/>
4 6<br/>
5 7<br/>
<br/>
</div>
</div>
</div>
