
# Description

<div class="content"><div>在米国有一所大学，名叫万国歌剧与信息大学（UniversalOperaandInformaticasUniversity）。简称UOI大学。UO</div>
<div>I大学的建筑与道路分布很有趣，每对建筑之间有且仅有一条直接或者间接的路径相连，更加明确的说，就是成树</div>
<div>形分布。其实在设计时，对于大学的N个建筑，总共有M条道路可以修建，每条道路都有一个距离值Disti和一个美</div>
<div>学值Valuei。一个设计方案的距离值和美学值定义为该设计方案内包含的道路的距离值与美学值之和。投资方的要</div>
<div>求只有设计方案的距离值最小。大神出于对树的喜爱所以决定设计方案必须是一棵树。因为要参加UOI，所以当时</div>
<div>大神就急急忙忙地随机选择了一个合法的方案。但其实存在很多合法的方案,假设每种设计方案取的概率是均等的</div>
<div>，那么设计方案的美学值期望是多少？</div></div>

# Input

<div class="content"><div>第一行两个整数，N和M，意义如上所述。</div>
<div>第二行到第M+1行，每行4个整数，Xi，Yi，Disti，Valuei，分别表示这条道路连接的</div>
<div>两个建筑的编号，距离值以及美学值。</div>
<div>输入保证至少有一种合法方案。</div>
<div>100%的数据保证N&lt;=10000M&lt;=200000</div>
<div>100%的数据保证距离值相同的道路数小于30，同时不保证没有重边。</div></div>

# Output

<div class="content"><p> 一行一个整数，即满足总道路长度最小的情况下，设计方案的美学值期望。要求保留5位小数</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
1 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.00000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

