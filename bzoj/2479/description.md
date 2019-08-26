
# Description

<div class="content"><div style="text-indent: 21pt">XX娱乐公司最近获得了一些古希腊迷宫的拥有权，为了使这些古典式迷宫能够吸引更多的游客，<span>XX公司计划对这些迷宫进行合理的改造。你的任务是根据所给的一个迷宫，针对公司的设计要求，在原有迷宫的基础上设计出一个最佳的新式迷宫。</span></div>
<div style="text-indent: 21pt">迷宫的外形是一个长方形，其在南北方向被划分为<span>N行，在东南方向被划分为M列，于是整个迷宫被划分为N×M个单元。我们用一个有序数对（单元的行号，单元的列号）来表示单元位置。南北或东西方向相邻的两个单元之间存在一堵墙或者一扇门，墙是不可逾越的，而门是双向的且可以任意通过。出于保护文物的目的，XX公司决定只适当地将墙改置为门，而不进行其它改造，并且要求新迷宫是最佳的，即新置的门的总数要最少。</span></div>
<div style="text-indent: 21pt">公司计划推出一个面向家庭的迷宫游戏。</div>
<div style="text-indent: 21pt"><span style="color: blue">游戏规则如下</span>：</div>
<div style="text-indent: 21pt">假定有<span>P（1&lt;=P&lt;=3）个家庭成员，他们分别从P个指定的起点出发，要求他们只能向南或向东移动，分别到达P个指定的终点。</span></div>
<div style="text-indent: 21pt">公司需要你针对上述游戏规则，设计一个最佳的迷宫，使得这样的游戏是可行的，即所有的家庭成员可以从各自的起点出发依照游戏规则到达各自的终点。</div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt"><font size="3">输入文件中的第一行为两个整数<span lang="EN-US">N</span>，<span lang="EN-US">M</span>（<span lang="EN-US">3&lt;=N</span>，<span lang="EN-US">M&lt;=20</span>）。<span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt"><font size="3">第二行中为一个整数<span lang="EN-US">k</span>，表示原迷宫中门的总个数。<span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt"><font size="3">第<span lang="EN-US">i+2</span>（<span lang="EN-US">1&lt;=i&lt;=k</span>）行中为四个整数<span lang="EN-US">X<sub>i</sub>1</span>，<span lang="EN-US">Y<sub>i</sub>1</span>，<span lang="EN-US">X<sub>i</sub>2</span>，<span lang="EN-US">Y<sub>i</sub>2</span>，表示第<span lang="EN-US">X<sub>i</sub>1</span>行第<span lang="EN-US">Y<sub>i</sub>1</span>列的单元与第<span lang="EN-US">X<sub>i</sub>2</span>行<span lang="EN-US">Y<sub>i</sub>2</span>列的单元之间有一扇门，其中：<span lang="EN-US">|X<sub>i</sub>1-Y<sub>i</sub>1|+|X<sub>i</sub>2-Y<sub>i</sub>2|=1</span>。<span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt"><font size="3">第<span lang="EN-US">k+3</span>行中为一个整数，表示<span lang="EN-US">p</span>的值。<span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt"><font size="3">第<span lang="EN-US">k+3+j</span>（<span lang="EN-US">1&lt;=j&lt;=p</span>）行中为四个整数<span lang="EN-US">X<sub>j</sub>1</span>，<span lang="EN-US">Y<sub>j</sub>1</span>，<span lang="EN-US">X<sub>j</sub>2</span>，<span lang="EN-US">Y<sub>j</sub>2</span>，分别表示第<span lang="EN-US">j</span>个家庭成员出发的起点位置（<span lang="EN-US">X<sub>j</sub>1</span>，<span lang="EN-US">Y<sub>j</sub>1</span>）和要到达的终点位置（<span lang="EN-US">X<sub>j</sub>2</span>，<span lang="EN-US">Y<sub>j</sub>2</span>），其中：<span lang="EN-US">X<sub>j</sub>1&lt;=X<sub>j</sub>2</span>，<span lang="EN-US">Y<sub>j</sub>1&lt;=Y<sub>j</sub>2</span>，（<span lang="EN-US">X<sub>j</sub>1</span>，<span lang="EN-US">Y<sub>j</sub>1</span>）<span lang="EN-US">&lt;&gt;</span>（<span lang="EN-US">X<sub>j</sub>2</span>，<span lang="EN-US">Y<sub>j</sub>2</span>）。<span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0"><font size="3"><span style="color: red; font-family: 宋体; mso-bidi-font-size: 10.5pt">注意</span><span style="font-family: 宋体; mso-bidi-font-size: 10.5pt">：输入数据中同一行各相邻整数之间用一空格分隔。<span lang="EN-US"><o:p></o:p></span></span></font></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: 10.5pt; font-family: 宋体; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">为一个整数，表示你所设计的最佳迷宫中新置的门的个数。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
5<br/>
1 1 1 2<br/>
2 1 3 1<br/>
2 2 3 2<br/>
4 2 4 3<br/>
1 4 2 4<br/>
3<br/>
2 1 4 3<br/>
1 2 4 2<br/>
3 1 4 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

