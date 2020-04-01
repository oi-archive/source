
# Description

<div class="content">你将要游览一个有N个岛屿的公园。从每一个岛i出发，只建造一座桥。桥的长度以Li表示。公园内总共有N座桥。尽管每座桥由一个岛连到另一个岛，但每座桥均可以双向行走。同时，每一对这样的岛屿，都有一艘专用的往来两岛之间的渡船。 
相对于乘船而言，你更喜欢步行。你希望所经过的桥的总长度尽可能的长，但受到以下的限制。 

• 可以自行挑选一个岛开始游览。 
• 任何一个岛都不能游览一次以上。 
• 无论任何时间你都可以由你现在所在的岛S去另一个你从未到过的岛D。由S到D可以有以下方法： 
o 步行：仅当两个岛之间有一座桥时才有可能。对于这种情况，桥的长度会累加到你步行的总距离；或者 
o 渡船：你可以选择这种方法，仅当没有任何桥和/或以前使用过的渡船的组合可以由S走到D（当检查是否可到达时，你应该考虑所有的路径，包括经过你曾游览过的那些岛）。 

注意，你不必游览所有的岛，也可能无法走完所有的桥。 

任务 
编写一个程序，给定N座桥以及它们的长度，按照上述的规则，计算你可以走过的桥的最大长度。 

限制 
2 &lt;= N &lt;= 1,000,000 公园内的岛屿数目。 
1&lt;= Li &lt;= 100,000,000 桥i的长度。 


</div>

# Input

<div class="content">• 第一行包含N个整数，即公园内岛屿的数目。岛屿由1到N编号。 
• 随后的N行每一行用来表示一个岛。第i 行由两个以单空格分隔的整数，表示由岛i筑的桥。第一个整数表示桥另一端的岛，第二个整数表示该桥的长度Li。你可以假设对於每座桥，其端点总是位于不同的岛上。 

</div>

# Output

<div class="content">你的程序必须向标准输出写出包含一个整数的单一行，即可能的最大步行距离。 
注1：对某些测试，答案可能无法放进32-bit整数，你要取得这道题的满分，可能需要用Pascal的int64或C/C++的long long类型。 
注2：在比赛环境运行Pascal程序，由标准输入读入64-bit数据比32-bit数据要慢得多，即使被读取的数据可以32-bit表示。我们建议把输入数据读入到32-bit数据类型。 

评分 
N不会超过4,000。 


</div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
3 8<br/>
7 2<br/>
4 2<br/>
1 4<br/>
1 9<br/>
3 4<br/>
2 3<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
</span></div>

# Hint

<div class="content"><p><img border="0" src="/source/bzoj/1791/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE3OTEuanBn.jpg"/> </p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

