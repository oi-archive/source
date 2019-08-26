
# Description

<div class="content"><div>FJ有N(1 &lt;= N &lt;= 20)头奶牛，编号1至N。FJ提供N种不同的技能供奶牛们学习，每头奶牛只能学习一门技能，每门</div>
<div>技能都要有奶牛学习。 第i头奶牛学习第j门技能，FJ得到的分数S[i][j]，1&lt;=S[i][j]&lt;=1000。此外还有B(1 &lt;= B</div>
<div> &lt;= 20)个奖励，第i个奖励的格式是： Pi 、Ki 、Ai，表示的意义是：如果学习完前Ki门技能后的总得分（包括</div>
<div>额外的奖励得分）不少于Pi，那么FJ还会得到额外的Ai分。那么FJ应该如何安排奶牛学习技能，才能使得最后的总</div>
<div>得分最高？</div></div>

# Input

<div class="content"><div>第一行，N和B。  接下来有B行，每行三个整数：Ki,Pi 、 Ai。</div>
<div>1 &lt;= Pi &lt;= 40000，1 &lt;= Ai &lt;= 1000。    </div>
<div>接下来有N行N列的二维数组，表示S[i][j]。1 &lt;= S[i][j] &lt;= 1000。 </div></div>

# Output

<div class="content"><p><span style="font-family: 宋体;">一个整数，最大得分。</span><span lang="EN-US"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 1<br/>
2 7 6<br/>
5 1 7<br/>
2 2 4<br/>
4 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 17 <br/>
//奶牛1学习技能1，奶牛2学习技能3，奶牛3学习技能2。  </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

