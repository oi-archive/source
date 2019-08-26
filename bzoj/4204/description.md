
# Description

<div class="content"><div>有M个球，一开始每个球均有一个初始标号，标号范围为1～N且为整数，标号为i的球有ai个，并保证Σai = M。</div>
<div>每次操作等概率取出一个球（即取出每个球的概率均为1/M），若这个球标号为k（k &lt; N），则将它重新标号为k + 1；若这个球标号为N，则将其重标号为1。（取出球后并不将其丢弃）</div>
<div>现在你需要求出，经过K次这样的操作后，每个标号的球的期望个数。</div>
<p></p></div>

# Input

<div class="content"><div>第1行包含三个正整数N，M，K，表示了标号与球的个数以及操作次数。</div>
<div>第2行包含N个非负整数ai，表示初始标号为i的球有ai个。</div>
<p></p></div>

# Output

<div class="content"><div>包含N行，第i行为标号为i的球的期望个数，四舍五入保留3位小数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 2<br/>
3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.667<br/>
1.333<br/>
<br/>
【样例说明】<br/>
第1次操作后，由于标号为2球个数为0，所以必然是一个标号为1的球变为标号为2的球。所以有2个标号为1的球，有1个标号为2的球。<br/>
第2次操作后，有1/3的概率标号为2的球变为标号为1的球（此时标号为1的球有3个），有2/3的概率标号为1的球变为标号为2的球（此时标号为1的球有1个），所以标号为1的球的期望个数为1/3*3+2/3*1 = 5/3。同理可求出标号为2的球期望个数为4/3。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N ≤ 1000, M ≤ 100,000,000, K ≤ 2,147,483,647。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

