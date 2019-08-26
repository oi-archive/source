
# Description

<div class="content"><div>小豆报名参加智力竞赛，他带上了n个好朋友作为亲友团一块来参加比赛。</div>
<div>比赛规则如下:</div>
<div>一共有m道题目，每个入都有1次答题机会，每次答题为选择一道题目回答，在回答正确后，可以从这个题目的后续</div>
<div>题目，直达题目答错题目或者没有后续题目。每个问题都会代表一个价值，比赛最后的参赛选手获得奖励价值等价</div>
<div>于该选手和他的亲友团没有回答的问题中的最低价值。我们现在知道小豆和他的亲友团实力非常强，能够做出这次</div>
<div>竞赛中的所有题目。</div>
<div>小豆想知道在知道题目和后续题目的条件下，他最大能获得价值是多少?</div>
<p></p></div>

# Input

<div class="content"><div>第一行有两个整数n, m。(n  ≤ 50, m  ≤ 500)</div>
<div>接下来m行，第i+1行表示编号为i的题目的题目信息;</div>
<div>格式如下vi, ki, ai_1, ai_2, ..., ai_ki 。</div>
<div>其中vi表示该题目的价值，ki  表示这个题目的后续，</div>
<div>ai_1, ai_2, ..., ai_ki 表示这i 个题目的后续题目编号。</div>
<div>1 &lt; n ≤ 50, 1 &lt; m ≤ 500, vi ≤ 10^9, ki, ai_j ≤ m。</div>
<p></p></div>

# Output

<div class="content"><div>如果全部题目都能答对，这输出“AK”，否则输出小豆可以获得的最高奖励价值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 3<br/>
1 0<br/>
2 1 3<br/>
3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">AK<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

