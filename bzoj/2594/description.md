
# Description

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: medium">SC省MY市有着庞大的地下水管网络，嘟嘟是MY市的水管局长（就是管水管的啦），嘟嘟作为水管局长的工作就是：每天供水公司可能要将一定量的水从x处送往y处，嘟嘟需要为供水公司找到一条从A至B的水管的路径，接着通过信息化的控制中心通知路径上的水管进入准备送水状态，等到路径上每一条水管都准备好了，供水公司就可以开始送水了。嘟嘟一次只能处理一项送水任务，等到当前的送水任务完成了，才能处理下一项。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: medium">在处理每项送水任务之前，路径上的水管都要进行一系列的准备操作，如清洗、消毒等等。嘟嘟在控制中心一声令下，这些水管的准备操作同时开始，但由于各条管道的长度、内径不同，进行准备操作需要的时间可能不同。供水公司总是希望嘟嘟能找到这样一条送水路径，路径上的所有管道全都准备就绪所需要的时间尽量短。嘟嘟希望你能帮助他完成这样的一个选择路径的系统，以满足供水公司的要求。另外，由于MY市的水管年代久远，一些水管会不时出现故障导致不能使用，你的程序必须考虑到这一点。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: medium">不妨将MY市的水管网络看作一幅简单无向图（即没有自环或重边）：水管是图中的边，水管的连接处为图中的结点。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: medium">输入文件第一行为3个整数：N, M, Q分别表示管道连接处（结点）的数目、目前水管（无向边）的数目，以及你的程序需要处理的任务数目（包括寻找一条满足要求的路径和接受某条水管坏掉的事实）。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: medium">以下M行，每行3个整数x, y和t，描述一条对应的水管。x和y表示水管两端结点的编号，t表示准备送水所需要的时间。我们不妨为结点从1至N编号，这样所有的x和y都在范围[1, N]内。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: medium">以下Q行，每行描述一项任务。其中第一个整数为k：若k=1则后跟两个整数A和B，表示你需要为供水公司寻找一条满足要求的从A到B的水管路径；若k=2，则后跟两个整数x和y，表示直接连接x和y的水管宣布报废（保证合法，即在此之前直接连接x和y尚未报废的水管一定存在）。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: medium">按顺序对应输入文件中每一项k=1的任务，你需要输出一个数字和一个回车/换行符。该数字表示：你寻找到的水管路径中所有管道全都完成准备工作所需要的时间（当然要求最短）。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 3<br/>
1 2 2<br/>
2 3 3<br/>
3 4 2<br/>
1 4 2<br/>
1 1 4<br/>
2 1 4<br/>
1 1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
 <br/>
【原题数据范围】<br/>
N ≤ 1000<br/>
M ≤ 100000<br/>
Q ≤ 100000<br/>
测试数据中宣布报废的水管不超过5000条；且任何时候我们考虑的水管网络都是连通的，即从任一结点A必有至少一条水管路径通往任一结点B。<br/>
 <br/>
【加强版数据范围】<br/>
N ≤ 100000<br/>
M ≤ 1000000<br/>
Q ≤ 100000<br/>
任何时候我们考虑的水管网络都是连通的，即从任一结点A必有至少一条水管路径通往任一结点B。<br/>
 <br/>
【C/C++选手注意事项】<br/>
由于此题输入规模较大（最大的测试点约20MB），因此即使使用scanf读入数据也会花费较多的时间。为了节省读入耗时，建议使用以下函数读入正整数（返回值为输入文件中下一个正整数）：<br/>
int getint()<br/>
 {<br/>
    char ch = getchar();<br/>
    for ( ; ch &gt; &#39;9&#39; || ch &lt; &#39;0&#39;; ch = getchar());<br/>
    int tmp = 0;<br/>
    for ( ; &#39;0&#39; &lt;= ch &amp;&amp; ch &lt;= &#39;9&#39;; ch = getchar())<br/>
      tmp = tmp * 10 + int(ch) - 48;<br/>
    return tmp;<br/>
 } <br/>
<br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Kac">鸣谢Kac</a></p></div>

