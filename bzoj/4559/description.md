
# Description

<div class="content"><div>G系共有n位同学，M门必修课。这N位同学的编号为0到N-1的整数，其中B神的编号为0号。这M门必修课编号为0到M-</div>
<div>1的整数。一位同学在必修课上可以获得的分数是1到Ui中的一个整数。如果在每门课上A获得的成绩均小于等于B获</div>
<div>得的成绩，则称A被B碾压。在B神的说法中，G系共有K位同学被他碾压（不包括他自己），而其他N-K-1位同学则没</div>
<div>有被他碾压。D神查到了B神每门必修课的排名。这里的排名是指：如果B神某门课的排名为R，则表示有且仅有R-1</div>
<div>位同学这门课的分数大于B神的分数，有且仅有N-R位同学这门课的分数小于等于B神（不包括他自己）。我们需要</div>
<div>求出全系所有同学每门必修课得分的情况数，使其既能满足B神的说法，也能符合D神查到的排名。这里两种情况不</div>
<div>同当且仅当有任意一位同学在任意一门课上获得的分数不同。你不需要像D神那么厉害，你只需要计算出情况数模1</div>
<div>0^9+7的余数就可以了。</div></div>

# Input

<div class="content"><div>第一行包含三个正整数N,M,K，分别表示G系的同学数量（包括B神），必修课的数量和被B神碾压的同学数量。第二</div>
<div>行包含M个正整数，依次表示每门课的最高分Ui。第三行包含M个正整数，依次表示B神在每门课上的排名Ri。保证1</div>
<div>≤Ri≤N。数据保证至少有1种情况使得B神说的话成立。N&lt;=100,M&lt;=100,Ui&lt;=10^9</div></div>

# Output

<div class="content"><p> 仅一行一个正整数，表示满足条件的情况数模10^9+7的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 1 <br/>
2 2 <br/>
1 2 </span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

