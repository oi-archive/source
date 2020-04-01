
# Description

<div class="content"><div>考虑一个由单位立方体构成的立体图形。这个立体图形的底是一个 n 行 m 列的单位平方网</div>
<div>格。每一个单位平方格竖直向上都直立着一些单位立方体（有可能为空）。这个立体图形中每个</div>
<div>单位立方体都属于其竖直向下投影到的单位平方格。每个单位立方体不能架空（即要么底部和另</div>
<div>一个单位立方体接触，要么与底接触）。</div>
<div>你将得到这个立体图形的左视图 (Left View) 和主视图 (Front View)，求可能的立体图形数。</div>
<div>下图对应了 n =4;m =5 的一个合法立体图形。</div>
<div><img src="/source/bzoj/3902/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy9jY2MuUE5H.PNG" width="692" height="261" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行为 n，m。</div>
<div>第二行为 n 个整数，对应左视图，即每一行的最大高度。</div>
<div>第三行为 m 个整数，对应主视图，即每一列的最大高度。</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一个数，为可能的立体图形数的个数模 10^9 +9。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
5 2 4 1<br/>
5 2 4 0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">429287</span></div>

# Hint

<div class="content"><p></p><p>对于 100% 的数据，1 &lt;= n;m &lt;= 50; 每行每列最大高度不超过 10000。</p><br/>
<div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

