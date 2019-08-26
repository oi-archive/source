
# Description

<div class="content"><p>For the daily milking, Farmer John&#39;s N cows (1 &lt;= N &lt;= 50,000) always line up in the same order. One day Farmer John decides to organize a game of Ultimate Frisbee with some of the cows. To keep things simple, he will take a contiguous range of cows from the milking lineup to play the game. However, for all the cows to have fun they should not differ too much in height.  Farmer John has made a list of Q (1 &lt;= Q &lt;= 200,000) potential groups of cows and their heights (1 &lt;= height &lt;= 1,000,000). For each group, he wants your help to determine the difference in height between the shortest and the tallest cow in the group.</p>
<p><span style="font-family: &#39;Times New Roman&#39;;">每天,农夫 John 的N(1 &lt;= N &lt;= 50,000)头牛总是按同一序列排队. 有一天, John </span><br style="font-family: &#39;Times New Roman&#39;;"/>
<span style="font-family: &#39;Times New Roman&#39;;">决定让一些牛们玩一场飞盘比赛. 他准备找一群在对列中为置连续的牛来进行比赛. </span><br style="font-family: &#39;Times New Roman&#39;;"/>
<span style="font-family: &#39;Times New Roman&#39;;">但是为了避免水平悬殊,牛的身高不应该相差太大. </span><br style="font-family: &#39;Times New Roman&#39;;"/>
<span style="font-family: &#39;Times New Roman&#39;;">John 准备了Q (1 &lt;= Q &lt;= 180,000) 个可能的牛的选择和所有牛的身高 (1 &lt;= </span><br style="font-family: &#39;Times New Roman&#39;;"/>
<span style="font-family: &#39;Times New Roman&#39;;">身高 &lt;= 1,000,000). 他想知道每一组里面最高和最低的牛的身高差别. </span><br style="font-family: &#39;Times New Roman&#39;;"/>
<span style="font-family: &#39;Times New Roman&#39;;">注意: 在最大数据上, 输入和输出将占用大部分运行时间. </span></p></div>

# Input

<div class="content"><p>* Line 1: Two space-separated integers, N and Q.  * Lines 2..N+1: Line i+1 contains a single integer that is the height         of cow i  * Lines N+2..N+Q+1: Two integers A and B (1 &lt;= A &lt;= B &lt;= N),         representing the range of cows from A to B inclusive.</p></div>

# Output

<div class="content"><div>6 3</div>
<div>1</div>
<div>7</div>
<div>3</div>
<div>4</div>
<div>2</div>
<div>5</div>
<div>1 5</div>
<div>4 6</div>
<div>2 2</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">* Lines 1..Q: Each line contains a single integer that is a response<br/>
        to a reply and indicates the difference in height between the<br/>
        tallest and shortest cow in the range.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
3<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

