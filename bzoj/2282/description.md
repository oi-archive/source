
# Description

<div class="content"><div>某个国家有n个城市，这n个城市中任意两个都连通且有唯一一条路径，每条连通两个城市的道路的长度为zi(zi&lt;=1000)。</div>
<div>这个国家的人对火焰有超越宇宙的热情，所以这个国家最兴旺的行业是消防业。由于政府对国民的热情忍无可忍（大量的消防经费开销）可是却又无可奈何（总统竞选的国民支持率），所以只能想尽方法提高消防能力。</div>
<div>现在这个国家的经费足以在一条边长度和不超过s的路径（两端都是城市）上建立消防枢纽，为了尽量提高枢纽的利用率，要求其他所有城市到这条路径的距离的最大值最小。</div>
<div>你受命监管这个项目，你当然需要知道应该把枢纽建立在什么位置上。</div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-size: 12pt; font-family: 宋体;">输入包含</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">n</span><span style="font-size: 12pt; font-family: 宋体;">行：</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;"><br/>
</span><span style="font-size: 12pt; font-family: 宋体;">第</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">1</span><span style="font-size: 12pt; font-family: 宋体;">行，两个正整数</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">n</span><span style="font-size: 12pt; font-family: 宋体;">和</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">s</span><span style="font-size: 12pt; font-family: 宋体;">，中间用一个空格隔开。其中</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">n</span><span style="font-size: 12pt; font-family: 宋体;">为城市的个数，</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">s</span><span style="font-size: 12pt; font-family: 宋体;">为路径长度的上界。设结点编号以此为</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">1</span><span style="font-size: 12pt; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">2</span><span style="font-size: 12pt; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">……</span><span style="font-size: 12pt; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">n</span><span style="font-size: 12pt; font-family: 宋体;">。</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;"><br/>
</span><span style="font-size: 12pt; font-family: 宋体;">从第</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">2</span><span style="font-size: 12pt; font-family: 宋体;">行到第</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">n</span><span style="font-size: 12pt; font-family: 宋体;">行，每行给出</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">3</span><span style="font-size: 12pt; font-family: 宋体;">个用空格隔开的正整数，依次表示每一条边的两个端点编号和长度。例如，</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">“2 4 7”</span><span style="font-size: 12pt; font-family: 宋体;">表示连接结点</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">2</span><span style="font-size: 12pt; font-family: 宋体;">与</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">4</span><span style="font-size: 12pt; font-family: 宋体;">的边的长度为</span><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;;">7</span><span style="font-size: 12pt; font-family: 宋体;">。</span></p>
<p class="HTMLPreformatted" style="margin: 0cm 0cm 0pt; text-indent: 24pt; mso-char-indent-count: 2.0"><span lang="EN-US" style="font-size: 12pt; font-family: &#39;Times New Roman&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p><span style="font-family: 宋体; text-indent: 32px;">输出包含一个非负整数，即所有城市到选择的路径的最大值，当然这个最大值必须是所有方案中最小的。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
5 2<br/>
1 2 5<br/>
2 3 2<br/>
2 4 4<br/>
2 5 3 <br/>
<br/>
<br/>
<br/>
【样例输入2】<br/>
8 6<br/>
1 3 2<br/>
2 3 2 <br/>
3 4 6<br/>
4 5 3<br/>
4 6 4<br/>
4 7 2<br/>
7 8 3  </span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
<br/>
5<br/>
【样例输出2】<br/>
<br/>
5</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，n&lt;=300000，边长小等于1000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=stage 2 day1">stage 2 day1</a></p></div>

