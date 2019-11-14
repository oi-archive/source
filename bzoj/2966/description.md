
# Description

<div class="content"><div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">给一个</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">个英文小写单词构成的序列，现在我们有一个操作即尝试在这个数列查找一个单词，我们从序列开头开始判断，每次判断一个单词，对于一个单词，我们从头开始对比每个字母，如果一样则继续对比下一个字母，如果不一样则跳转下一个单词，值得注意的是我们默认每个单词后面的还有一个结束符，也就是说结束符可以作为一个字母进行对比。我们将停止这个过程当且仅当我们对比完两个结束符或者将序列中的单词全部对比完。现在我们进行</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">次这样的操作，求每次对比字母的次数。</span></div></div>

# Input

<div class="content"><div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第一行</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，下接</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">行每行一个单词。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">然后一行一个数</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">，下接</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">行每行一个操作用一个单词表示。</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">共</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">行，每行一个数表示对比字母的次数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
       5<br/>
hobotnica<br/>
robot<br/>
hobi<br/>
hobit<br/>
robi<br/>
4<br/>
robi<br/>
hobi<br/>
hobit<br/>
rakija<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
       12<br/>
       10<br/>
       16<br/>
       7<br/>
数据说明：<br/>
           对于100%的数据，N&lt;=30000，M&lt;=30000，单词长度&lt;=30</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

