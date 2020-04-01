
# Description

<div class="content"><div>现在有一大块土地，可以看成N*M的方格。在这块土地上，有些格子内是崎岖的山地，无法建造任何东西；其他格子都是平原。现在打算在这块土地上建设一个游乐园。游乐园由若干条闭合的过山车轨道组成，每个平原格子都要铺一截轨道，为下列 6 种类型中的一种：</div>
<div><img src="/source/bzoj/4261/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOS9mYi5qcGc=.jpg" width="576" height="208" alt=""/></div>
<div>（每张图表示一块平原格子，图内网格线为辅助线，无实际意义。）</div>
<div></div>
<div>其中前 2 种为直轨道，后 4 种为弯轨道。显然对游客来说，弯轨道更加刺激。</div>
<div></div>
<div>由于每块格子风景各不相同，经过一番研究，现给了N*M个方格中的每个格子一个评估值，意义为：如果该格子修建弯轨道，会给游客们带来多少的愉悦值。现需要一名设计师，帮他设计一种最优的轨道建设方案，使所有格子给游客们带来的愉悦值之和尽量大。（如果没有合法方案，输出 -1）</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数 n, m。</div>
<div>接下来 n 行，每行 m 个数，描述了整块土地。其中 1 表示山地，0 表示平原。接下来 n 行，每行 m 个非负整数，第 i 行第 j 个为 Vi,j，表示格子 (i,j) 修建弯轨道能给游客们带来的愉悦值。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行一个数，表示最优设计方案中给游客们带来的愉悦值之和。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 1 1 <br/>
1 0 0 <br/>
1 0 0 <br/>
48 94 1 <br/>
78 78 81 <br/>
1 12 60 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">231</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=150,M&lt;=30,Vi,j&lt;=100</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

