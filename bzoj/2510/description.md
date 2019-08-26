
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">有<i>M</i>个球，一开始每个球均有一个初始标号，标号范围为1～<i>N</i>且为整数，标号为<i>i</i>的球有<i>a<sub>i</sub></i>个，并<b>保证</b><b>Σ</b><b><i>a<sub>i</sub></i></b><b> = <i>M</i></b>。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">每次操作<b><u>等概率</u></b>取出一个球（即取出每个球的概率均为1/<i>M</i>），若这个球标号为<i>k</i>（<i>k</i> &lt; <i>N</i>），则将它重新标号为<i>k</i> + 1；若这个球标号为<i>N</i>，则将其重标号为1。<b>（取出球后并不将其丢弃）</b></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">现在你需要求出，经过<i>K</i>次这样的操作后，每个标号的球的期望个数。</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">第1行包含三个<b><u>正整数</u></b><i>N</i>，<i>M</i>，<i>K</i>，表示了标号与球的个数以及操作次数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">第2行包含<i>N</i>个<b><u>非负整数</u></b><i>a<sub>i</sub></i>，表示初始标号为<i>i</i>的球有<i>a<sub>i</sub></i>个。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">应包含<i>N</i>行，第<i>i</i>行为标号为<i>i</i>的球的期望个数，四舍五入保留3位小数。</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 2<br/>
3 0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.667<br/>
1.333<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】<br/><br/>
第1次操作后，由于标号为2球个数为0，所以必然是一个标号为1的球变为标号为2的球。所以有2个标号为1的球，有1个标号为2的球。<br/><br/>
第2次操作后，有1/3的概率标号为2的球变为标号为1的球（此时标号为1的球有3个），有2/3的概率标号为1的球变为标号为2的球（此时标号为1的球有1个），所以标号为1的球的期望个数为1/3*3+2/3*1 = 5/3。同理可求出标号为2的球期望个数为4/3。<br/><br/>
 <br/><br/>
【数据规模与约定】<br/><br/>
对于10%的数据，N ≤ 5, M ≤ 5, K ≤ 10；<br/><br/>
对于20%的数据，N ≤ 20, M ≤ 50, K ≤ 20；<br/><br/>
对于30%的数据，N ≤ 100, M ≤ 100, K ≤ 100；<br/><br/>
对于40%的数据，M ≤ 1000, K ≤ 1000；<br/><br/>
对于100%的数据，N ≤ 1000, M ≤ 100,000,000, K ≤ 2,147,483,647。</p><br/>
<p><br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

