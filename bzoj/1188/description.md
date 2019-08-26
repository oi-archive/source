
# Description

<div class="content"><div>聪聪和睿睿最近迷上了一款叫做分裂的游戏。该游戏的规则试：共有n个瓶子，标号为0,1,2.....n-1,第i个瓶子中</div>
<div>装有p[i]颗巧克力豆，两个人轮流取豆子，每一轮每人选择3个瓶子。标号为i,j,k,并要保证i&lt;j,j&lt;=k且第i个瓶子</div>
<div>中至少要有1颗巧克力豆，随后这个人从第i个瓶子中拿走一颗豆子并在j,k中各放入一粒豆子（j可能等于k）。如</div>
<div>果轮到某人而他无法按规则取豆子，那么他将输掉比赛。胜利者可以拿走所有的巧克力豆！两人最后决定由聪聪先</div>
<div>取豆子，为了能够得到最终的巧克力豆，聪聪自然希望赢得比赛。他思考了一下，发现在有的情况下，先拿的人一</div>
<div>定有办法取胜，但是他不知道对于其他情况是否有必胜策略，更不知道第一步该如何取。他决定偷偷请教聪明的你</div>
<div>，希望你能告诉他，在给定每个瓶子中的最初豆子数后是否能让自己得到所有巧克力豆，他还希望你告诉他第一步</div>
<div>该如何取，并且为了必胜，第一步有多少种取法？</div>
<div>假定 1 &lt; n &lt; = 21,p[i] &lt; = 10000</div></div>

# Input

<div class="content"><div>输入文件第一行是一个整数t表示测试数据的组数，</div>
<div>接下来为t组测试数据（t&lt;=10）。</div>
<div>每组测试数据的第一行是瓶子的个数n，</div>
<div>接下来的一行有n个由空格隔开的非负整数，表示每个瓶子中的豆子数。</div></div>

# Output

<div class="content"><div>对于每组测试数据，输出包括两行，</div>
<div>第一行为用一个空格两两隔开的三个整数，表示要想赢得游戏，</div>
<div>第一步应该选取的3个瓶子的编号i,j,k，</div>
<div>如果有多组符合要求的解，那么输出字典序最小的一组。</div>
<div>如果无论如何都无法赢得游戏，那么输出用一个空格两两隔开的三个-1。</div>
<div>第二行表示要想确保赢得比赛，第一步有多少种不同的取法。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2                          <br/>
4                            <br/>
1 0 1 5000            <br/>
3                            <br/>
0 0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 2 3<br/>
1<br/>
-1 -1 -1<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

