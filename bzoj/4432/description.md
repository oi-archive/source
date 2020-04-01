
# Description

<div class="content"><div>你从计算机科学转向农业，你的新工作包括在一个地下温室种植向日葵。在温室中有n个排列在一条直线的向日葵植株，从左向右编号为1到n。有A、B2个照射器为向日葵的生长提供光和热，且照射器A、B分别放置在向日葵的左右两端。</div>
<div>每天只有1个照射器被打开，使所有向日葵转向光源，并使部分向日葵生长。向日葵会生长当且仅当其朝向的相邻植株比它更高，其每天的生长高度为1厘米。请注意，一个植株的生长将使其背后的植株立刻开始生长。</div>
<div></div>
<div>样例数据前三天的生长情况</div>
<div><img src="/source/bzoj/4432/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwMy9hYSgxKS5naWY=.gif" width="653" height="201" alt=""/></div>
<div>你将被给出向日葵的初始高度和接下来m天的光照计划，请计算所有向日葵最终的高度。</div>
<p></p></div>

# Input

<div class="content"><div>第一行有2个整n和m(1&lt;= n, m &lt;=300 000)——植株数和天数。</div>
<div>接下来一行包括n个整数h1, h2,… , hn (1 &lt;= hk &lt;=109)——从左到右向日葵的初始高度。</div>
<div>接下来一行包括一个仅含字母A/B长度为m的字符串——从第一天开始的光照计划。</div>
<p></p></div>

# Output

<div class="content"><div>n个整数——从左到右每株向日葵最终的高度</div></div>

# Sample Input

<div class="content"><span class="sampledata">6 5<br/>
4 3 5 3 6 6<br/>
BABAA<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5 5 6 6 6 6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

