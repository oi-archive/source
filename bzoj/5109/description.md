
# Description

<div class="content"><div>最近《绝地求生：大逃杀》风靡全球，皮皮和毛毛也迷上了这款游戏，他们经常组队玩这款游戏。在游戏中，皮皮</div>
<div>和毛毛最喜欢做的事情就是堵桥，每每有一个好时机都能收到不少的快递。当然，有些时候并不能堵桥，皮皮和毛</div>
<div>毛会选择在其他的必经之路上蹲点。K博士作为一个老年人，外加有心脏病，自然是不能玩这款游戏的，但是这并</div>
<div>不能妨碍他对这款游戏进行一些理论分析，比如最近他就对皮皮和毛毛的战士很感兴趣。【题目描述】游戏的地图</div>
<div>可以抽象为一张n个点m条无向边的图，节点编号为1到n，每条边具有一个正整数的长度。假定大魔王都会从S点出</div>
<div>发到达T点（S和T已知），并且只会走最短路，皮皮和毛毛会在A点和B点埋伏大魔王。</div>
<div>为了保证一定能埋伏到大魔王，同时又想留大魔王一条生路，皮皮和毛毛约定A点和B点必须满足：</div>
<div>1.大魔王所有可能路径中，必定会经过A点和B点中的任意一点</div>
<div>2.大魔王所有可能路径中，不存在一条路径同时经过A点和B点</div>
<div>K博士想知道，满足上面两个条件的A,B点对有多少个，交换A,B的顺序算相同的方案</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行输入四个整数n,m,S,T(1≤n≤5×10^4,1≤m≤5×10^4,1≤S,T≤n)，含义见题目描述。</div>
<div>接下来输入m行，每行输入三个整数u,v,w(1≤u,v≤n,1≤w≤10^9)表示存在一条长度为w的边链接u和v。</div>
<div>1≤n≤5×10^4,1≤m≤5×10^4,1≤w≤10^9</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行表示答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 7 1 7<br/>
1 2 2<br/>
2 4 2<br/>
4 6 2<br/>
6 7 2<br/>
1 3 2<br/>
3 5 4<br/>
5 7 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
【样例 1 解释】<br/>
合法的方案为 &lt; 2, 3 &gt;, &lt; 2, 4 &gt;, &lt; 4, 3 &gt;, &lt; 4, 5 &gt;, &lt; 6, 3 &gt;, &lt; 6, 5 &gt; 。</span></div>

# Hint

<div class="content"><p></p><div>来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</div><br/>
<div>Credit：idea/陈宇　命题/陈宇　验题/邢健开</div><br/>
<div>Git Repo：https://git.thusaac.org/publish/CodePlus201711</div><br/>
<div>本次比赛的官方网址：cp.thusaac.org</div><br/>
<div>感谢腾讯公司对此次比赛的支持。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

