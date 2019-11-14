
# Description

<div class="content"><div>贝西喜欢棋盘游戏和角色扮演类游戏所以她说服Farmer John把她带到玩具店，在那里，她购买了三个不同的骰子</div>
<div>，这三个质量均匀的骰子，分别有S1,S2,S3个面。(2 &lt;= S1 &lt;= 20; 2 &lt;= S2 &lt;= 20; 2 &lt;= S3 &lt;= 40). 贝西掷啊</div>
<div>掷啊掷啊，想要知道出现几率最大的和是多少。 问题给出三个骰子的面数，让你求出出现几率最大的和是多少。</div>
<div>如果有很多种和出现的几率相同，那么就输出小的那一个。</div></div>

# Input

<div class="content"><p><span style="font-size: medium">*第一行：三个由空格隔开的整数：s1,s2,s3 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">*第一行：所要求的解 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
输出详解:<br/>
这里是所有可能的情况.<br/>
1 1 1 -&gt; 3 1 2 1 -&gt; 4 2 1 1 -&gt; 4 2 2 1 -&gt; 5 3 1 1 -&gt; 5 3 2 1 -&gt; 6<br/>
1 1 2 -&gt; 4 1 2 2 -&gt; 5 2 1 2 -&gt; 5 2 2 2 -&gt; 6 3 1 2 -&gt; 6 3 2 2 -&gt; 7<br/>
1 1 3 -&gt; 5 1 2 3 -&gt; 6 2 1 3 -&gt; 6 2 2 3 -&gt; 7 3 1 3 -&gt; 7 3 2 3 -&gt; 8<br/>
5和6出现的几率都是最大的，所以输出5.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=资格赛">资格赛</a></p></div>

