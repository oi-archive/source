
# Description

<div class="content"><p>身为IOI金牌的gtyzs有自己的一个OJ，名曰GOJ。GOJ上的题目可谓是高质量而又经典，他在他的OJ里面定义了一个树形的分类目录，且两个相同级别的目录是不会重叠的。比如图论的大目录下可能分为最短路，最小生成树，网络流等低一级的分类目录，这些目录下可能还有更低一级的目录，以此类推。现在gtyzs接到了一个任务，要他为SDTSC出题。他准备在自己的OJ题库中找出M道题作为SDTSC的试题，而他深知SDTSC的童鞋们个个都是神犇，所以gtyzs认为自己出的这M道题中，每道题都应该属于不少于L种分类目录；可他又怕自己的题没有人会做，所以每道题也应该属于不超过R种分类目录，并且这些分类目录应该是连续的，不能出现断层。对了，最重要的是，不存在一道题，它属于两个分类目录且这两个目录不是包含关系。（比如不存在一道题它既是一道DP题，又是一道网络流题）gtyzs怕被骂，所以他希望不存在任意的一对题目(u,v)，使得u所属的分类目录与v完全相同。举例来说，gtyzs不能出两道同样的都是动态规划，背包的题，但是却可以出一道属于动态规划，背包和01背包的题和一道属于背包，01背包的题，当然也可以出一个属于图论的题和一个属于数论的题。（注意：一道题所属的分类目录不一定从根开始，如加粗部分所示）<br/>
为了让自己的题目变得更加靠谱，他给每一个分类目录都定了一个靠谱值ai，这个值可正可负。一道题的靠谱度为其从属的分类目录靠谱值的加和。我们假设动态规划的靠谱值为10，插头DP的靠谱值为－5，则一道动态规划插头DP的题的靠谱值就是5。gtyzs希望自己出的这M道题，在满足上述前提条件下，靠谱度总和最大。gtyzs当然会做啦，于是你就看到了这个题。</p></div>

# Input

<div class="content"><div>输入的第一行是一个正整数N，代表分类目录的总数。</div>
<div>接下来的一行，共N个正整数，第i个正整数为fi，表示分类目录i被fi所包含。保证一个分类目录只会被一个分类目录所包含，且包含关系不存在环。特别的，fi＝0表示它是根节点，我们保证这样的点只存在一个。</div>
<div>接下来的一行，共N个整数，第i个数表示ai。</div>
<div>最后一行，三个正整数M,L,R。</div>
<div>对于100%的数据，1≤N≤500,000，1≤M≤500,000，|ai|≤2,000。保证输入数据有解。</div>
<div>为了方便，所有的测试数据中都有f1＝0，且对于任意的i∈[2,N]，有fi&lt;i。</div>
<p></p></div>

# Output

<div class="content"><p>一行一个整数，表示最大的靠谱度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
0 1 1 2 2 3 3<br/>
2 3 4 1 2 3 4<br/>
3 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">26</span></div>

# Hint

<div class="content"><p></p><p>对于样例数据，gtyzs选择这样的3道题：T1属于分类目录1,3,7，T2属于分类目录1,3,6，T3属于分类目录1,2,5。这三道题是满足要求的能取得最大靠谱度26的试题 题解：<a href="/JudgeOnline/upload/201604/Solution-4458.rar">JudgeOnline/upload/201604/Solution-4458.rar</a> By jinlifu1999</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By jinlifu1999">By jinlifu1999</a></p></div>

