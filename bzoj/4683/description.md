
# Description

<div class="content"><div>背景</div>
<div>AwD大爷是个神犇</div>
<div></div>
<div>题目</div>
<div>AwD大爷又单手屠了仙人掌辣</div>
<div>蒟蒻HFLSyzx在旁边跪地不起</div>
<div>AwD大爷觉得仙人掌实在是太没有挑战性了，于是便开始yy仙人掌的加强版——仙人图</div>
<div>定义仙人图为每条边至多在两个简单环上的图</div>
<div>现在初始仙人图是空的，你需要支持三个操作</div>
<div>link a b w</div>
<div>添加一条连接a,b的边，权值为w</div>
<div>如果添加完毕之后还是仙人图，输出ok</div>
<div>否则输出failed，并撤销本次操作</div>
<div></div>
<div>cut a b w</div>
<div>删除一条连接a,b权值为w的边</div>
<div>如果有多个删除一个</div>
<div>如果不存在这样的边输出failed，并忽略本次操作</div>
<div>否则输出ok</div>
<div></div>
<div>distance? a b</div>
<div>询问a,b之间的最短路</div>
<div>如果a,b不连通输出-1</div>
<div></div>
<div>AwD大爷造完题后一眼秒了，把题扔在一边</div>
<div>蒟蒻HFLSyzx看到后直接吓晕过去</div>
<div>为了不在AwD大爷面前丢脸，蒟蒻HFLSyzx必须A掉这道题</div>
<div>可是他完全不会做</div>
<div>于是来求助你辣！</div>
<p></p></div>

# Input

<div class="content"><div>第一行n，m表示有n个节点，m个操作</div>
<div>接下来m行，每行一个操作</div>
<div>保证必定为link cut或者distance?</div>
<div></div>
<div>m &lt;= 300000,<span style="font-family: arial, verdana, helvetica, sans-serif;">所有关于边长的计算在int范围内</span></div>
<p><span style="font-family: arial, verdana, helvetica, sans-serif;">n &lt;= 100000</span></p>
<div>有可能有重边（有可能权值一样的重边）</div>
<div>有可能link自环，此时输出failed</div>
<div>有可能询问两个相同的点的最短路，此时输出0</div>
<p></p></div>

# Output

<div class="content"><div>对每个操作输出一行，代表该操作的结果/答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
5 12<br/>
link 1 2 3<br/>
link 2 3 3<br/>
distance? 1 3<br/>
cut 2 3 3<br/>
distance? 1 3<br/>
cut 2 3 2<br/>
link 2 3 2<br/>
cut 2 3 3<br/>
link 3 4 3<br/>
link 4 1 5<br/>
link 1 3 8<br/>
link 2 4 7<br/>
<br/>
样例输入2<br/>
6 25<br/>
link 1 2 3<br/>
link 1 2 2<br/>
link 1 2 5<br/>
cut 1 2 2<br/>
cut 1 2 5<br/>
link 1 2 3<br/>
link 1 2 3<br/>
cut 1 2 3<br/>
cut 1 2 3<br/>
cut 1 2 3<br/>
cut 1 2 3<br/>
link 1 2 4<br/>
link 1 3 5<br/>
distance? 2 3<br/>
link 2 4 1<br/>
link 3 4 2<br/>
link 2 3 3<br/>
link 1 4 7<br/>
link 1 4 7<br/>
cut 1 4 7<br/>
link 5 6 8<br/>
distance? 3 6<br/>
distance? 2 6<br/>
cut 2 4 1<br/>
distance? 1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
ok<br/>
ok<br/>
6<br/>
ok<br/>
-1<br/>
failed<br/>
ok<br/>
failed<br/>
ok<br/>
ok<br/>
ok<br/>
failed<br/>
<br/>
<br/>
<br/>
样例输出2<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
ok<br/>
failed<br/>
ok<br/>
ok<br/>
9<br/>
ok<br/>
ok<br/>
ok<br/>
failed<br/>
failed<br/>
failed<br/>
ok<br/>
-1<br/>
-1<br/>
ok<br/>
-1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=by AwD &amp; HFLSyzx">by AwD &amp; HFLSyzx</a></p></div>

