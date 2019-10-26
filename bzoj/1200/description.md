
# Description

<div class="content"><div>King从小就酷爱艺术，他梦想成为一名伟大的艺术家。最近他得到了一块材质不错的木板，木板下侧为直线段，长</div>
<div>为L，平均分为L段，从左到右编号为1，2，……，L。木板的上侧是锯齿形，高度为整数，第i段的高度为Ai，Ai&gt;=</div>
<div>2。（如下所示）</div>
<div><img src="/source/bzoj/1200/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xKDQpLnBuZw==.png" width="284" height="211" alt=""/></div>
<div>这么好的一段材料浪费了怪可惜的，King决定好好加工一番做成一件艺术品。但他不是纯艺术家，他觉得每一件作</div>
<div>品都应该有实用价值（否则只是华而不实），具有实用性的艺术品是他设计的理念。根据这块木板的锯齿状，King</div>
<div>想到了每天起床后都要用到的一件日用品，&#34;对，就把它做成梳子！&#34;他的设想是：用刻刀将某些上端的格子挖掉（</div>
<div>如果把某个格子挖掉，那么这个格子上方的格子也必须被挖掉，但不能把一列中的格子全都挖掉），使得剩下木板</div>
<div>构成&#34;规则锯齿形&#34;（这样才好梳头）。</div>
<div><img src="/source/bzoj/1200/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8yKDMpLnBuZw==.png" width="278" height="178" alt=""/></div>
<div>例如，对于上图，挖掉第3，7，8列最上面1个格子，第5列最上面2个格子后，剩下的区域就构成&#34;规则锯齿形&#34;（如</div>
<div>右图）。一个锯齿形称为&#34;规则锯齿形&#34;当且仅当它的上边界（图中红色曲线所示）的拐弯序列不包含&#34;010&#34;或者&#34;10</div>
<div>1&#34;。图中红色曲线的拐弯序列为：&#34;011001&#34;，（其中0代表往左拐，1代表往右拐）沿着曲线的最左端往右走，先左</div>
<div>拐，再右拐，接着右拐，然后左拐，继续左拐，最后右拐。为了最大限度的减少浪费，King希望做出来的梳子面积</div>
<div>最大。这样一来，设计梳子的任务就变得非常复杂了--不过这是对于艺术家来说，对于你来说，不就是小菜一碟吗</div>
<div>？</div></div>

# Input

<div class="content"><div>第一行为整数L，其中4&lt;=L&lt;=100000，表示木板下侧直线段的长。</div>
<div>第二行为L个正整数A1,A2,…,AL</div></div>

# Output

<div class="content"><p>仅包含一个整数D，表示为使梳子面积最大，需要从木板上挖掉的格子数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">9                            <br/>
4 4 6 5 4 2 3 3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<img border="0" src="/source/bzoj/1200/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEyMDBfMy5qcGc=.jpg"/></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

