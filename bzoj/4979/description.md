
# Description

<div class="content"><div>小Q所在的学校QNU(Quailty Niubi University)的学生公寓由n栋楼组成，这些楼从左往右连成一排，编号依次为1</div>
<div>到n，其中第i栋楼有h_i层。现在已经凌晨三点了，但是小Q和他的队友们仍然在刻苦地刷题，从他们房间窗户透出</div>
<div>的亮光格外醒目。</div>
<div><img src="/source/bzoj/4979/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOC9waWMucG5n.png" width="438" height="320" alt=""/></div>
<div>这时，辛苦了一晚上的小Q饿了，正当他拆完泡面准备倒水的时候，他发现热水壶放在队友那忘记拿回来了。无奈</div>
<div>之下，他只好走路去向队友要回热水壶。在学生公寓里，小Q每分钟可以选择上楼或者下楼，或者往左往右移动到</div>
<div>相邻的房间外面的过道上。因为夜晚的门禁，他不能走出公寓，同时，他也不能登上天台思考人生。你可以认为从</div>
<div>房间到过道不需要任何时间。饥饿的小Q最多只能坚持走k分钟，再之后他就会因为饥饿而昏倒。他历尽艰险终于从</div>
<div>队友那拿回了热水壶，解决了燃眉之急。这时，吃着泡面的小Q开始思考一个问题：如果他和队友的房间距离并没</div>
<div>有那么近，那么他就不会这么走运了。于是现在他想知道有多少对队友的房间之间的最短路程不超过k分钟。小Q正</div>
<div>在吃泡面，于是他把这个问题交给了你。请写一个程序帮助小Q解决这个现实问题。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,k(1&lt;=n&lt;=200000,1&lt;=k&lt;=400000)，分别表示宿舍楼的数量以及路程的上限。</div>
<div>第二行包含n个正整数h_1,h_2,...,h_n(1&lt;=h_i&lt;=200000)，分别表示每栋楼的层数。</div>
<div>接下来一行包含一个正整数m(1&lt;=m&lt;=200000)，表示亮着灯的房间个数。</div>
<div>接下来m行，每行两个正整数x_i,y_i(1&lt;=x_i&lt;=n,1&lt;=y_i&lt;=h_{x_i})，表示这个房间位于x_i号楼的第y_i层。</div>
<div>输入数据保证m个房间不会重复输入。</div></div>

# Output

<div class="content"><p>输出一行一个整数，即最短路程不超过k的房间对数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
4 1 1 3 1<br/>
3<br/>
1 4<br/>
3 1<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
HINT<br/>
样例对应题目描述中的图，房间1和房间3之间的距离为8&gt;7，因此不能计入答案。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

