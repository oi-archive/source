
# Description

<div class="content"><p>过不了多久，Crash 就要迎来他朝思暮想的暑假。在这个暑假里，他计划着到火星上旅游。在火星上有N 个旅游景点，Crash 用1 至N 这N 个正整数对这些景点标号。旅游景点之间通过双向道路相连。由于火星的环境和地球有很大的差异，建立道路的成本也相对较高。为了节约成本，只有N-1 条道路连接着这些旅游景点，不过可以保证任何两个不同的旅游景点都通过路径相连。 Crash 预先在互联网上查阅了这些景点的信息，根据网上的介绍，他对每个景点都有一个印象值，这个印象值为一个整数。在这个旅行中，他会选择一个景点作为旅行的开始，并沿着存在的道路到达其他景点游玩。为了使旅行不显得乏味，Crash 不会经过同一个景点超过一次。Crash 还给这次旅行定义了一个快乐指数，也就是他经过的所有景点的印象值之和。不过Crash 是个奇怪的小朋友，他对于景点的印象值会发生改变，并且他也没有决定好应该从哪个景点开始旅行。因此他希望你能写一个程序帮他完成一个简单的任务：根据当前他对每个景点的印象值，计算从某个景点开始旅行所能获得的最大的快乐指数。</p></div>

# Input

<div class="content"><p>输入的第一行包含一个字符和一个正整数N，字符为ABC 中的一个，用来表示这个测试数据的类型（详见下面的数据规模和约定）。第二行包含N 个用空格隔开的整数，第i 个整数表示Crash 对i 号景点的初始印象值。接着有N-1 行，每行两个正整数a、b(1 ≤ a, b ≤ N)，表示从a 号景点到b 号景点有一条无向道路相连。最后是一些指令，指令只会是以下三种格式： 1．Change u x (1 ≤ u ≤ N) 将u 号景点的印象值修改为x。 2．Query u (1 ≤ u ≤ N) 询问从u 号景点开始能获得的最大的快乐指数。 3．Done 收到这个指令后，你的程序应该结束。</p></div>

# Output

<div class="content"><p>对于每条Query 指令，输出对应的最大快乐指数。。</p></div>

# Sample Input

<div class="content"><span class="sampledata">[样例输入1]<br/>
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
[样例输入2]<br/>
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
Done</span></div>

# Sample Output

<div class="content"><span class="sampledata">[样例输出1]<br/>
7<br/>
14<br/>
7<br/>
6<br/>
15<br/>
[样例输出2]<br/>
4<br/>
11<br/>
7<br/>
11</span></div>

# Hint

<div class="content"><p></p><p>测试数据分为ABC 三类，对于所有的测试数据都满足：在任何时候一个景点印象值的绝对值不超过10000，并且输入的道路一定能满足题目描述的要求，即使得任意两个不同的景点都能通过路径相连。对于A 类数据（占20%的分数）满足：N 和指令的条数都不超过1000。对于B 类数据（占40%的分数）满足：N 和指令的条数都不超过100000，且输入的第i 条道路，连接着i 号景点和i+1 号景点（详见样例2）。对于C 类数据（占40%的分数）满足：N 和指令的条数都不超过100000，且任何一个景点到1 号景点需要通过的道路条数不超过40。【特别说明】由于数据大小限制为5MB，我只好对测试时的输入文件进行压缩处理。下面的函数可以将压缩的输入文件转化为原始输入文件。（函数从infile 中读入压缩的输入文件，将解压缩后的输入文件输出到outfile 中） C/C++版本： void Uncompress(FILE *infile, FILE *outfile) { int N, M, L, now, A, B, Q, tmp, i; char type = getc(infile); fscanf(infile, &#34;%d%d%d&#34;, &amp;N, &amp;M, &amp;L); fscanf(infile, &#34;%d%d%d%d&#34;, &amp;now, &amp;A, &amp;B, &amp;Q); fprintf(outfile, &#34;%c %d\n&#34;, type, N); for (i = 1; i &lt;= N; i ++) { now = (now * A + B) % Q, tmp = now % 10000; now = (now * A + B) % Q; if (now * 2 &lt; Q) tmp *= -1; if (i &lt; N) fprintf(outfile, &#34;%d &#34;, tmp); else fprintf(outfile, &#34;%d\n&#34;, tmp); } for (i = 1; i &lt; N; i ++) { now = (now * A + B) % Q; tmp = (i &lt; L) ? i : L; fprintf(outfile, &#34;%d %d\n&#34;, i - now % tmp, i + 1); } for (i = 1; i &lt; M; i ++) { now = (now * A + B) % Q; if (now * 3 &lt; Q) { now = (now * A + B) % Q; fprintf(outfile, &#34;Query %d\n&#34;, now % N + 1); } else { now = (now * A + B) % Q, tmp = now % 10000; now = (now * A + B) % Q; if (now * 2 &lt; Q) tmp *= -1; now = (now * A + B) % Q; fprintf(outfile, &#34;Change %d %d\n&#34;, now % N + 1, tmp); } } fprintf(outfile, &#34;Done\n&#34;); } Pascal 版本： procedure Uncompress(var infile, outfile : text); var N, M, L, now, A, B, Q, tmp, i : longint; ch : char; begin read(infile, ch, N, M, L, now, A, B, Q); writeln(outfile, ch, &#39; &#39;, N); for i := 1 to N do begin now := (now * A + B) mod Q; tmp := now mod 10000; now := (now * A + B) mod Q; if now * 2 &lt; Q then tmp := -tmp; if i &lt; n then write(outfile, tmp, &#39; &#39;) else writeln(outfile, tmp); end; for i := 1 to N - 1 do begin now := (now * A + B) mod Q; if i &lt; L then tmp := i else tmp := L; writeln(outfile, i - now mod tmp, &#39; &#39;, i + 1); end; for i := 1 to M - 1 do begin now := (now * A + B) mod Q; if now * 3 &lt; Q then begin now := (now * A + B) mod Q; writeln(outfile, &#39;Query &#39;, now mod N + 1); end else begin now := (now * A + B) mod Q; tmp := now mod 10000; now := (now * A + B) mod Q; if now * 2 &lt; Q then tmp := -tmp; now := (now * A + B) mod Q; writeln(outfile, &#39;Change &#39;, now mod N + 1, &#39; &#39;, tmp); end; end; writeln(outfile, &#39;Done&#39;); end; 下面给出一个具体的例子。travel_compressed.in 表示压缩的输入文件， travel.in 表示解压缩后的输入文件。 travel_compressed.in travel.in A 5 7 3 17627 543 14278 380043 travel.in A 5 -4664 7653 -3584 -210 5852 1 2 1 3 2 4 3 5 Change 5 -3724 Query 4 Change 3 -5628 Query 2 Change 5 569 Query 5 Done</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

