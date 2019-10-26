
# Description

<div class="content"><div>期末考试结束了，班主任L老师要将成绩单分发到每位同学手中。L老师共有n份成绩单，按照编号从1到n的顺序叠</div>
<div>放在桌子上，其中编号为i的成绩单分数为w_i。成绩单是按照批次发放的。发放成绩单时，L老师会从当前的一叠</div>
<div>成绩单中抽取连续的一段，让这些同学来领取自己的成绩单。当这批同学领取完毕后，L老师再从剩余的成绩单中</div>
<div>抽取连续的一段，供下一批同学领取。经过若干批次的领取后，成绩单将被全部发放到同学手中。然而，分发成绩</div>
<div>单是一件令人头痛的事情，一方面要照顾同学们的心理情绪，不能让分数相差太远的同学在同一批领取成绩单；另</div>
<div>一方面要考虑时间成本，尽量减少领取成绩单的批次数。对于一个分发成绩单的方案，我们定义其代价为：</div>
<div><img src="/source/bzoj/4897/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNS92djEoMSkuanBn.jpg" width="388" height="97" alt=""/></div>
<div>其中，k是方案中分发成绩单的批次数，对于第i批分发的成绩单，〖max〗_i是最高分数，〖min〗_i是最低分数。</div>
<div>a,b是给定的评估参数。现在，请你帮助L老师找到代价最小的分发成绩单的方案，并将这个最小的代价告诉L老师</div>
<div>。当然，分发成绩单的批次数k是由你决定的。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n，表示成绩单的数量。</div>
<div>第二行包含两个非负整数a,b，表示给定的评估参数。</div>
<div>第三行包含n个正整数w_i，表示第i张成绩单上的分数。</div>
<p></p></div>

# Output

<div class="content"><div>仅一个正整数，表示最小的代价是多少。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
3 1<br/>
7 10 9 10 6 7 10 7 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
【样例数据说明】<br/>
第1批：第2至4份成绩单，落差值为1，剩余成绩单为76710712；<br/>
第2批：第4份成绩单，落差值为0，剩余成绩单为767712；<br/>
第3批：第1至4份成绩单，落差值为1，剩余成绩单为12；<br/>
第4批：剩余的2份成绩单，落差值为1。<br/>
总代价为4×3+(1^2+0^2+1^2+1^2)×1=15。<br/>
</span></div>

# Hint

<div class="content"><p></p><p> n&lt;=50, a&lt;=100, b&lt;=10, w_i&lt;=1000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Sengxian上传">鸣谢Sengxian上传</a></p></div>

