
# Description

<div class="content"><p> 小强和B君士好朋友。 </p>
<div>小强除了B君还有很多好朋友，比如洁妹。 </div>
<div>B君除了小强也还有很多好朋友，比如R君。他们还有很多共同的好朋友，比如小花，葱娘和其他3个人。 </div>
<div>B君发现，人与人之间的关系可以看成是一个无向图，每个人看成一个点，人与人之间的关系看成一条边。 </div>
<div>不同的人在社会中的号召力不一样，我们用ai来表示第i个人的号召力。 </div>
<div>人与人之间的关系也各不相同，可能非常友好，可能只是泛泛之交；可能天天腻在一起，可能一年才联系一次。为此，我们用长度边权bj来刻画第j条边对应的两个用户的亲密程度，长度约小，双方就越亲密；同时，我们用宽度边权cj来刻画第j条边对应的两个用户的交流频率，宽度越大，两个人沟通的频率也就越高。 </div>
<div>一条路径的长度指的是这条路径上的所有边的长度边权之和，一条路径的宽度指的是这条路径上的所有边的宽度边权的乘积。 </div>
<div>当两个人s和t想要交流的时候，他们会选择长度最短的路径来交流。由于最短路可能有多个，我们称s到t的最短路的宽度为σst，是所有s到t的长度最短的路径的宽度和。同时，我们用σst(v)表示所有从s到t，且经过v的长度最短的路径的宽度和，即v对s,t的影响力。 </div>
<div>一个人v在图中的传播力R(v)可以被定义为如下函数： </div>
<div> <img src="/source/bzoj/4055/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8xLkpQRw==.JPG" width="276" height="85" alt=""/></div>
<div>即对图中所有不包含v的点对，分别计算v对该点对的影响力除以该点对的最短路的宽度，再乘上这个点对中两个点的号召力，最后将所有点对的计算结果加和得到节点在图中的传播力。 </div>
<div>B君想快速知道所有节点在图中的传播力。当他去问小强的时候，小强说：“我有一个绝妙的做法，可惜题面太短，写不下。” </div>
<div>你知道怎么做吗？ </div></div>

# Input

<div class="content"><p>第一行包含2个正整数n,m，分别表示图的点数和边数。 </p>
<div>接下来n行中的第i行有1个非负整数ai，表示第i个人的号召力。 </div>
<div>接下来m行中的第j行有3个整数xj,yj,bj和一个实数cj，表示点xj和点yj之间有一条长度边权为bj，宽度边权为cj的边。 </div></div>

# Output

<div class="content"><p>共n行，每行一个实数R(i)，表示第i个点在图中的传播力。 </p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 3 4 5<br/>
1 2 2 0.7<br/>
3 4 2 0.9<br/>
1 3 1 1.1<br/>
2 4 1 1.3<br/>
4 5 10 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.762887<br/>
8.621053<br/>
9.378947<br/>
67.237113<br/>
0.000000</span></div>

# Hint

<div class="content"><p></p><p> 【评分标准】 </p><br/>
<div>我们会将输出文件的每个数与参考答案进行比较，如果该数与参考答案的相对误差或绝对误差不超过10-6，则判定该数正确。对于参考答案为0的数，必须满足绝对误差不超过10-6才判定为正确。 </div><br/>
<div>如果输出正确数的个数为q，那么你在该测试点上的得分是 </div><br/>
<div><img src="/source/bzoj/4055/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS8yLkpQRw==.JPG" width="115" height="106" alt=""/></div><br/>
<div> </div><br/>
<div></div><br/>
<div>【数据规模和约定】 </div><br/>
<div>对于测试点1,2,3,4，有n&lt;=100。 </div><br/>
<div>对于测试点5,6,7,6，所有bj=1。 </div><br/>
<div>对于测试点9,10,11,12，有m=n-1。 </div><br/>
<div>对于测试点1,3,5,7,9,11,13,15,17,19，所有ai=1。 </div><br/>
<div>对于测试点1,2,5,6,9,10,13,14,17,18，所有cj=1。 </div><br/>
<div>对于所有的数据，有n&lt;=1000，m&lt;=4000，0&lt;aj&lt;=255，0&lt;bj&lt;=15，0.5&lt;=cj&lt;=2，cj的小数部分最多12位。数据保证图是连通的</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

