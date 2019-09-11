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
过不了多久，Crash就要迎来他朝思暮想的暑假。在这个暑假里，他计划着到火星上旅游。在火星上有N个旅游景点，Crash用1至N这N个正整数对这些景点标号。旅游景点之间通过双向道路相连。由于火星的环境和地球有很大的差异，建立道路的成本也相对较高。为了节约成本，只有N-1条道路连接着这些旅游景点，不过可以保证任何两个不同的旅游景点都通过路径相连。<br/>
Crash预先在互联网上查阅了这些景点的信息，根据网上的介绍，他对每个景点都有一个印象值，这个印象值为一个整数。在这个旅行中，他会选择一个景点作为旅行的开始，并沿着存在的道路到达其他景点游玩。为了使旅行不显得乏味，Crash不会经过同一个景点超过一次。Crash还给这次旅行定义了一个快乐指数，也就是他经过的所有景点的印象值之和。<br/>
不过Crash是个奇怪的小朋友，他对于景点的印象值会发生改变，并且他也没有决定好应该从哪个景点开始旅行。因此他希望你能写一个程序帮他完成一个简单的任务：根据当前他对每个景点的印象值，计算从某个景点开始旅行所能获得的最大的快乐指数。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含一个字符和一个正整数N，字符为ABC中的一个，用来表示这个测试数据的类型（详见下面的数据规模和约定）。<br/>
第二行包含N个用空格隔开的整数，第i个整数表示Crash对i号景点的初始印象值。<br/>
接着有N-1行，每行两个正整数a、b(1 ≤a, b≤N)，表示从a号景点到b号景点有一条无向道路相连。<br/>
最后是一些指令，指令只会是以下三种格式：<br/>
1． Change ux (1 ≤u≤N)将u号景点的印象值修改为x。<br/>
2． Query u (1 ≤u≤N) 询问从u号景点开始能获得的最大的快乐指数。<br/>
3． Done收到这个指令后，你的程序应该结束。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每条Query指令，输出对应的最大快乐指数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
A 6<br/>
6 5 -4 3 -2 1<br/>
1 2<br/>
1 3<br/>
1 4<br/>
3 5<br/>
3 6<br/>
Query 3<br/>
Query 4<br/>
Change 6 10<br/>
Query 3<br/>
Change 2 -5<br/>
Query 3<br/>
Query 4<br/>
Done
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
7<br/>
14<br/>
7<br/>
6<br/>
15
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
B 5<br/>
5 -4 3 -2 1<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
Query 3<br/>
Change 5 10<br/>
Query 3<br/>
Query 2<br/>
Change 2 2<br/>
Query 3<br/>
Done
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
4<br/>
11<br/>
7<br/>
11
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
测试数据分为ABC三类，对于所有的测试数据都满足：在任何时候一个景点印象值的绝对值不超过10000，并且输入的道路一定能满足题目描述的要求，即使得任意两个不同的景点都能通过路径相连。<br/>
对于A类数据（占20%的分数）满足：N和指令的条数都不超过1000。<br/>
对于B类数据（占40%的分数）满足：N和指令的条数都不超过100000，且输入的第i条道路，连接着i号景点和i+1号景点（详见样例2）。<br/>
对于C类数据（占40%的分数）满足：N和指令的条数都不超过100000，且任何一个景点到1号景点需要通过的道路条数不超过40。
</div>
<h3>
【特别说明】
</h3>
<div class="pdcont">
由于数据大小限制为5MB，我只好对测试时的输入文件进行压缩处理。下面的函数可以将压缩的输入文件转化为原始输入文件。（函数从infile中读入压缩的输入文件，将解压缩后的输入文件输出到outfile中）<br/>
C/C++版本：<br/>
void Uncompress(FILE *infile, FILE *outfile)<br/>
{<br/>
int N, M, L, now, A, B, Q, tmp, i;<br/>
char type = getc(infile);<br/>
fscanf(infile, &#34;%d%d%d&#34;, &amp;N, &amp;M, &amp;L);<br/>
fscanf(infile, &#34;%d%d%d%d&#34;, &amp;now, &amp;A, &amp;B, &amp;Q);<br/>
fprintf(outfile, &#34;%c %d\n&#34;, type, N);<br/>
for (i = 1; i &lt;= N; i ++)<br/>
{<br/>
now = (now * A + B) % Q, tmp = now % 10000;<br/>
now = (now * A + B) % Q;<br/>
if (now * 2 &lt; Q) tmp *= -1;<br/>
if (i &lt; N)<br/>
fprintf(outfile, &#34;%d &#34;, tmp);<br/>
else<br/>
fprintf(outfile, &#34;%d\n&#34;, tmp);<br/>
}<br/>
for (i = 1; i &lt; N; i ++)<br/>
{<br/>
now = (now * A + B) % Q;<br/>
tmp = (i &lt; L) ? i : L;<br/>
fprintf(outfile, &#34;%d %d\n&#34;, i - now % tmp, i + 1);<br/>
}<br/>
for (i = 1; i &lt; M; i ++)<br/>
{<br/>
now = (now * A + B) % Q;<br/>
if (now * 3 &lt; Q)<br/>
{<br/>
now = (now * A + B) % Q;<br/>
fprintf(outfile, &#34;Query %d\n&#34;, now % N + 1);<br/>
}<br/>
else<br/>
{<br/>
now = (now * A + B) % Q, tmp = now % 10000;<br/>
now = (now * A + B) % Q;<br/>
if (now * 2 &lt; Q) tmp *= -1;<br/>
now = (now * A + B) % Q;<br/>
fprintf(outfile, &#34;Change %d %d\n&#34;, now % N + 1, tmp);<br/>
}<br/>
}<br/>
fprintf(outfile, &#34;Done\n&#34;);<br/>
}<br/>
<br/>
Pascal版本：<br/>
procedure Uncompress(varinfile, outfile : text);<br/>
var<br/>
N, M, L, now, A, B, Q, tmp, i : longint;<br/>
ch : char;<br/>
begin<br/>
read(infile, ch, N, M, L, now, A, B, Q);<br/>
writeln(outfile, ch, &#39; &#39;, N);<br/>
for i := 1 to N do<br/>
begin<br/>
now := (now * A + B) mod Q;<br/>
tmp := now mod 10000;<br/>
now := (now * A + B) mod Q;<br/>
if now * 2 &lt; Q then tmp := -tmp;<br/>
if i &lt; n then<br/>
write(outfile, tmp, &#39; &#39;)<br/>
else<br/>
writeln(outfile, tmp);<br/>
end;<br/>
for i := 1 to N - 1 do<br/>
begin<br/>
now := (now * A + B) mod Q;<br/>
if i &lt; L then tmp := i else tmp := L;<br/>
writeln(outfile, i - now mod tmp, &#39; &#39;, i + 1);<br/>
end;<br/>
for i := 1 to M - 1 do<br/>
begin<br/>
now := (now * A + B) mod Q;<br/>
if now * 3 &lt; Q then<br/>
begin<br/>
now := (now * A + B) mod Q;<br/>
writeln(outfile, &#39;Query &#39;, now mod N + 1);<br/>
end<br/>
else<br/>
begin<br/>
now := (now * A + B) mod Q;<br/>
tmp := now mod 10000;<br/>
now := (now * A + B) mod Q;<br/>
if now * 2 &lt; Q then tmp := -tmp;<br/>
now := (now * A + B) mod Q;<br/>
writeln(outfile, &#39;Change &#39;, now mod N + 1, &#39; &#39;, tmp);<br/>
end;<br/>
end;<br/>
writeln(outfile, &#39;Done&#39;);<br/>
end;<br/>
<br/>
下面给出一个具体的例子。travel_compressed.in表示压缩的输入文件，travel.in表示解压缩后的输入文件。<br/>
travel_compressed.in<br/>
A 5 7 3<br/>
17627 543 14278 380043<br/>
<br/>
travel.in<br/>
A 5<br/>
-4664 7653 -3584 -210 5852<br/>
1 2<br/>
1 3<br/>
2 4<br/>
3 5<br/>
Change 5 -3724<br/>
Query 4<br/>
Change 3 -5628<br/>
Query 2<br/>
Change 5 569<br/>
Query 5<br/>
Done
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<h3>
【问题描述】
</h3>
<div class="probcontent">
过不了多久，Crash就要迎来他朝思暮想的暑假。在这个暑假里，他计划着到火星上旅游。在火星上有N个旅游景点，Crash用1至N这N个正整数对这些景点标号。旅游景点之间通过双向道路相连。由于火星的环境和地球有很大的差异，建立道路的成本也相对较高。为了节约成本，只有N-1条道路连接着这些旅游景点，不过可以保证任何两个不同的旅游景点都通过路径相连。<br/>
Crash预先在互联网上查阅了这些景点的信息，根据网上的介绍，他对每个景点都有一个印象值，这个印象值为一个整数。在这个旅行中，他会选择一个景点作为旅行的开始，并沿着存在的道路到达其他景点游玩。为了使旅行不显得乏味，Crash不会经过同一个景点超过一次。Crash还给这次旅行定义了一个快乐指数，也就是他经过的所有景点的印象值之和。<br/>
不过Crash是个奇怪的小朋友，他对于景点的印象值会发生改变，并且他也没有决定好应该从哪个景点开始旅行。因此他希望你能写一个程序帮他完成一个简单的任务：根据当前他对每个景点的印象值，计算从某个景点开始旅行所能获得的最大的快乐指数。<br/>
<br/>
 
</div>
<h3>
【输入格式】
</h3>
<div class="probcontent">
输入的第一行包含一个字符和一个正整数N，字符为ABC中的一个，用来表示这个测试数据的类型（详见下面的数据规模和约定）。<br/>
第二行包含N个用空格隔开的整数，第i个整数表示Crash对i号景点的初始印象值。<br/>
接着有N-1行，每行两个正整数a、b(1 ≤a, b≤N)，表示从a号景点到b号景点有一条无向道路相连。<br/>
最后是一些指令，指令只会是以下三种格式：<br/>
1． Change ux (1 ≤u≤N)将u号景点的印象值修改为x。<br/>
2． Query u (1 ≤u≤N) 询问从u号景点开始能获得的最大的快乐指数。<br/>
3． Done收到这个指令后，你的程序应该结束。<br/>
<br/>
 
</div>
<h3>
【输出格式】
</h3>
<div class="probcontent">
对于每条Query指令，输出对应的最大快乐指数。<br/>
<br/>
 
</div>
<h3>
【样例输入1】
</h3>
<div class="probexample">
A 6<br/>
6 5 -4 3 -2 1<br/>
1 2<br/>
1 3<br/>
1 4<br/>
3 5<br/>
3 6<br/>
Query 3<br/>
Query 4<br/>
Change 6 10<br/>
Query 3<br/>
Change 2 -5<br/>
Query 3<br/>
Query 4<br/>
Done<br/>
<br/>
 
</div>
<h3>
【样例输出1】
</h3>
<div class="probexample">
7<br/>
14<br/>
7<br/>
6<br/>
15<br/>
<br/>
 
</div>
<h3>
【样例输入2】
</h3>
<div class="probexample">
B 5<br/>
5 -4 3 -2 1<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
Query 3<br/>
Change 5 10<br/>
Query 3<br/>
Query 2<br/>
Change 2 2<br/>
Query 3<br/>
Done<br/>
<br/>
 
</div>
<h3>
【样例输出2】
</h3>
<div class="probexample">
4<br/>
11<br/>
7<br/>
11<br/>
<br/>
 
</div>
<h3>
【数据范围】
</h3>
<div class="probcontent">
测试数据分为ABC三类，对于所有的测试数据都满足：在任何时候一个景点印象值的绝对值不超过10000，并且输入的道路一定能满足题目描述的要求，即使得任意两个不同的景点都能通过路径相连。<br/>
对于A类数据（占20%的分数）满足：N和指令的条数都不超过1000。<br/>
对于B类数据（占40%的分数）满足：N和指令的条数都不超过100000，且输入的第i条道路，连接着i号景点和i+1号景点（详见样例2）。<br/>
对于C类数据（占40%的分数）满足：N和指令的条数都不超过100000，且任何一个景点到1号景点需要通过的道路条数不超过40。<br/>
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
    int N, M, L, now, A, B, Q, tmp, i;<br/>
    char type = getc(infile);<br/>
    fscanf(infile, &#34;%d%d%d&#34;, &amp;N, &amp;M, &amp;L);<br/>
    fscanf(infile, &#34;%d%d%d%d&#34;, &amp;now, &amp;A, &amp;B, &amp;Q);<br/>
    fprintf(outfile, &#34;%c %d\n&#34;, type, N);<br/>
    for (i = 1; i &lt;= N; i ++)<br/>
    {<br/>
        now = (now * A + B) % Q, tmp = now % 10000;<br/>
        now = (now * A + B) % Q;<br/>
        if (now * 2 &lt; Q) tmp *= -1;<br/>
        if (i &lt; N)<br/>
            fprintf(outfile, &#34;%d &#34;, tmp);<br/>
        else<br/>
        fprintf(outfile, &#34;%d\n&#34;, tmp);<br/>
    }<br/>
    for (i = 1; i &lt; N; i ++)<br/>
    {<br/>
        now = (now * A + B) % Q;<br/>
        tmp = (i &lt; L) ? i : L;<br/>
        fprintf(outfile, &#34;%d %d\n&#34;, i - now % tmp, i + 1);<br/>
    }<br/>
    for (i = 1; i &lt; M; i ++)<br/>
    {<br/>
        now = (now * A + B) % Q;<br/>
        if (now * 3 &lt; Q)<br/>
        {<br/>
            now = (now * A + B) % Q;<br/>
            fprintf(outfile, &#34;Query %d\n&#34;, now % N + 1);<br/>
        }<br/>
        else<br/>
        {<br/>
            now = (now * A + B) % Q, tmp = now % 10000;<br/>
            now = (now * A + B) % Q;<br/>
            if (now * 2 &lt; Q) tmp *= -1;<br/>
            now = (now * A + B) % Q;<br/>
            fprintf(outfile, &#34;Change %d %d\n&#34;, now % N + 1, tmp);<br/>
        }<br/>
    }<br/>
    fprintf(outfile, &#34;Done\n&#34;);<br/>
}<br/>
<br/>
Pascal版本：<br/>
procedure Uncompress(varinfile, outfile : text);<br/>
var<br/>
N, M, L, now, A, B, Q, tmp, i : longint;<br/>
ch : char;<br/>
begin<br/>
    read(infile, ch, N, M, L, now, A, B, Q);<br/>
    writeln(outfile, ch, &#39; &#39;, N);<br/>
    for i := 1 to N do<br/>
        begin<br/>
            now := (now * A + B) mod Q;<br/>
            tmp := now mod 10000;<br/>
            now := (now * A + B) mod Q;<br/>
            if now * 2 &lt; Q then tmp := -tmp;<br/>
            if i &lt; n then<br/>
                write(outfile, tmp, &#39; &#39;)<br/>
            else<br/>
                writeln(outfile, tmp);<br/>
        end;<br/>
    for i := 1 to N - 1 do<br/>
        begin<br/>
            now := (now * A + B) mod Q;<br/>
            if i &lt; L then tmp := i else tmp := L;<br/>
            writeln(outfile, i - now mod tmp, &#39; &#39;, i + 1);<br/>
        end;<br/>
    for i := 1 to M - 1 do<br/>
        begin<br/>
            now := (now * A + B) mod Q;<br/>
            if now * 3 &lt; Q then<br/>
                begin<br/>
                    now := (now * A + B) mod Q;<br/>
                    writeln(outfile, &#39;Query &#39;, now mod N + 1);<br/>
                end<br/>
            else<br/>
                begin<br/>
                    now := (now * A + B) mod Q;<br/>
                    tmp := now mod 10000;<br/>
                    now := (now * A + B) mod Q;<br/>
                    if now * 2 &lt; Q then tmp := -tmp;<br/>
                    now := (now * A + B) mod Q;<br/>
                    writeln(outfile, &#39;Change &#39;, now mod N + 1, &#39; &#39;, tmp);<br/>
                end;<br/>
        end;<br/>
    writeln(outfile, &#39;Done&#39;);<br/>
end;<br/>
<br/>
下面给出一个具体的例子。travel_compressed.in表示压缩的输入文件，travel.in表示解压缩后的输入文件。<br/>
travel_compressed.in<br/>
A 5 7 3<br/>
17627 543 14278 380043<br/>
<br/>
travel.in<br/>
A 5<br/>
-4664 7653 -3584 -210 5852<br/>
1 2<br/>
1 3<br/>
2 4<br/>
3 5<br/>
Change 5 -3724<br/>
Query 4<br/>
Change 3 -5628<br/>
Query 2<br/>
Change 5 569<br/>
Query 5<br/>
Done<br/>
<br/>
<p>
 
</p>
</div>
<p>
 
</p>
</div>
</div>
