
# Description

<div class="content"><div class="pdcont"><span style="font-size: medium">S国正在进行核武器试验，数以亿计的科学家们前来观测。试验区位于S国某城市，此城市有n个区域，共有n-1条道路连接它们，任意两片区域可相互到达。其中核弹将于某个区域引爆，科学家们将去往一些度数为1的非引爆点区域，即观测点观察。抽象的说，若将此引爆区域设为有根树的根，科学家们将去往非根叶子节点。所有科学家可以同时行动，每条道路双向通行，且均给出一个所需通过的时间，然而每个观测点容纳人数有限，但是保证观测点容量大于等于科学家数。求科学家们最少所需移动时间，以使试验尽早开始。<br/>
</span></div></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　第一行输入一个正整数n，表示点的数量，接下来n行，每行一条描述。<br/>
　　第i+1行第一个数字a<sub>i</sub>，表示i号节点的儿子数。接下来2a<sub>i</sub>个数，第2j-1个数b<sub>ij</sub>表示i号节点的孩子，第2j个数c<sub>ij</sub>表示其与i之间边权。接下来一个数t<sub>i</sub>，若a<sub>i</sub>等于0，表示此点最多可容纳人数，若a<sub>i</sub>不等于0，则表示此点现有人数。<br/>
</span></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　一个数，表示最少所需时间。<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 2 5 3 3 2<br/>
1 4 2 3<br/>
0 2<br/>
0 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">　　100%的数据1&lt;=n&lt;=10000，0&lt;=cij，ti&lt;=100000，本题均为随机数据（树深度较小）。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

