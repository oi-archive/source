
# Description

<div class="content"><div>黑恶势力的反攻计划被小C成功摧毁，黑恶势力只好投降。秋之国的人民解放了，举国欢庆。此时，原秋之国总统</div>
<div>因没能守护好国土，申请辞职，并请秋之国人民的大救星小C钦定下一任。作为一名民主人士，小C决定举行全民大</div>
<div>选来决定下一任。为了使最后成为总统的人得到绝大多数人认同，小C认为，一个人必须获得超过全部人总数的一</div>
<div>半的票数才能成为总统。如果不存在符合条件的候选人，小C只好自己来当临时大总统。为了尽可能避免这种情况</div>
<div>，小C决定先进行几次小规模预选，根据预选的情况，选民可以重新决定自己选票的去向。由于秋之国人数较多，</div>
<div>统计投票结果和选票变更也成为了麻烦的事情，小C找到了你，让你帮他解决这个问题。</div>
<div></div>
<div>【问题描述】</div>
<div>秋之国共有n个人，分别编号为1,2,…,n，一开始每个人都投了一票，范围1~n，表示支持对应编号的人当总统。共</div>
<div>有m次预选，每次选取编号[li,ri]内的选民展开小规模预选，在该区间内获得超过区间大小一半的票的人获胜，如</div>
<div>果没有人获胜，则由小C钦定一位候选者获得此次预选的胜利（获胜者可以不在该区间内），每次预选的结果需要</div>
<div>公布出来，并且每次会有ki个人决定将票改投向该次预选的获胜者。全部预选结束后，公布最后成为总统的候选人</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,m，表示秋之国人数和预选次数。</div>
<div>第二行n个整数，分别表示编号1~n的选民投的票。</div>
<div>接下来m行，每行先有4个整数，分别表示li,ri,si,ki，si表示若此次预选无人胜选，视作编号为si的人获得胜利</div>
<div>接下来ki个整数，分别表示决定改投的选民。</div>
<div>1&lt;=n,m&lt;=500,000，Σki&lt;=1,000,000，1&lt;=li&lt;=ri&lt;=n，1&lt;=si&lt;=n。</div>
<p></p></div>

# Output

<div class="content"><div>共m+1行，前m行表示各次预选的结果，最后一行表示最后成为总统的候选人，若最后仍无人胜选，输出-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 2 3 4 5<br/>
1 2 1 1 3<br/>
5 5 1 2 2 4<br/>
2 4 2 0<br/>
3 4 2 1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
5<br/>
5<br/>
2<br/>
-1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

