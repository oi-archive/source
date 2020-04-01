
# Description

<div class="content"><div>
<div>文章是一些单词组成的序列，单词由字母组成。你的任务是将一篇文章的单词填充到一个网格中，其中网格包含W</div>
<div>列和足够多的行。为了布局之美，以下限制都需要满足。</div>
<div>1.文章中的文字需要按照原有的顺序放置。下图表示了将4个单词的文章“This is a pen”放入11列的网格正确和</div>
<div>错误的例子。</div>
<div><img src="/source/bzoj/4692/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8xKDIpLnBuZw==.png" width="616" height="127" alt=""/></div>
<div>2.在同一行的两个相邻单词之间要有至少一个空格。有时你会需要放置多于一个空格来满足其他限制。</div>
<div><img src="/source/bzoj/4692/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8yKDIpLnBuZw==.png" width="573" height="176" alt=""/></div>
<div>3.一个单词必须被放置到连续的列中，一个格子只含一个字符。你不能将通过增加空格或换行将一个单词分成多个</div>
<div>部分。</div>
<div><img src="/source/bzoj/4692/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8zKDEpLnBuZw==.png" width="554" height="120" alt=""/></div>
<div>4.文章必须占据边缘两列的格子，即每行的第一个单词必须占用第一个格子，且除了最后一行之外的每行的最后一</div>
<div>个单词必须占用最后一个格子。</div>
<div><img src="/source/bzoj/4692/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC80KDEpLnBuZw==.png" width="656" height="125" alt=""/></div>
<div>文章拥有最美的布局时，每一行都不会有过多的连续空格，在下图的例子里只有最多2个连续空格，而第一个例子</div>
<div>里有3个连续空格，所以下图的例子比第一个例子美观。给定文章的信息和列数，请你找到一个最优的布局，使得</div>
<div>最长连续空格尽量短。</div>
<div><img src="/source/bzoj/4692/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC81LnBuZw==.png" width="508" height="167" alt=""/></div>
<div></div>
</div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据。每组数据第一行包含两个正整数W和N，其中W表示列数(3≤W≤80000)，N表示文章的单词数量(2≤N≤50000)。</div>
<div>第二行包含N个正整数，按照文章中单词的顺序给出每个单词的字符数量，</div>
<div>对于第i个单词的字符数量xi，有1≤x_i≤(W-1)/2，从而这也使得答案一定存在。</div>
<div>输入以两个零作为结束。</div>
<p></p></div>

# Output

<div class="content"><p>对于每组数据，输出一个正整数表示最长连续空格长度的最小值。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">11 4<br/>
4 2 1 3<br/>
5 7<br/>
1 1 1 2 2 1 2<br/>
11 7<br/>
3 1 3 1 3 3 4<br/>
100 3<br/>
30 30 39<br/>
30 3<br/>
2 5 3<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
2<br/>
40<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

