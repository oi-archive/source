
# Description

<div class="content"><div>Leopold十分幸运，买彩票中了大奖，得到了一座庄园。庄园中除了Leopold打算居住的主宅之外，还有一些其他的</div>
<div>建筑。然后，这座庄园缺少围墙保护，这一点让Loepold很担心。于是，Loepold打算在房子周围建围墙，为了省钱</div>
<div>他决定只要围墙能将主宅包围起来就足够了，还有一点就是围墙不能离庄园中的任何一个建筑太近。也就是说，每</div>
<div>个建筑都被一个禁止矩形包围，在这个矩形内部不允许有任何围墙。矩形的边平行于x轴和y轴。围墙的每一部分也</div>
<div>必须平行于x轴或者y轴。 请你帮助Leopold计算包围主宅的围墙的最小长度。</div>
<p><img border="0" src="/source/bzoj/1343/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEzNDMuanBn.jpg" alt=""/></p>
<div>图1：有主宅（黑色）和其他三个建筑，每个建筑外面灰色的矩行是禁止矩形，粗的黑线表示这种情况下最小的围</div>
<div>墙长度。</div></div>

# Input

<div class="content"><div>第一行是一个正整数m（1&lt;=m&lt;= 100），表示庄园中建筑的总数。</div>
<div>接下来的m行，每行描述了一个建筑对应的禁止矩形，</div>
<div>包括4个空格隔开的整数tx，ty，bx和by，(tx，ty)是矩形左上角的坐标，(bx，by)是矩形右下角的坐标。</div>
<div>所有的坐标值满足0 &lt;= tx &lt;= bx &lt;= 10000和 0 &lt;= ty &lt;= by &lt;= 10000。</div>
<div>第一个禁止矩形是包围主宅的。</div></div>

# Output

<div class="content"><p>一个正整数，即包围主宅的围墙的最小长度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
8 4 13 8<br/>
2 1 6 7<br/>
4 7 9 11<br/>
14 7 19 11	</span></div>

# Sample Output

<div class="content"><span class="sampledata">32</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

