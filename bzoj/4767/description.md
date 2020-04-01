
# Description

<div class="content"><div>老W是个棋艺高超的棋手，他最喜欢的棋子是马，更具体地，他更加喜欢马所行走的方式。老W下棋时觉得无聊，便</div>
<div>决定加强马所行走的方式，更具体地，他有两双手，其中一双手能让马从(u,v)移动到(u+Ax,v+Ay)而另一双手能让</div>
<div>马从(u,v)移动到(u+Bx,v+By)。小W看见老W的下棋方式，觉得非常有趣，他开始思考一个问题：假设棋盘是个无限</div>
<div>大的二维平面，一开始马在原点(0,0)上，若用老W的两种方式进行移动，他有多少种不同的移动方法到达点(Ex,Ey</div>
<div>)呢？两种移动方法不同当且仅当移动步数不同或某一步所到达的点不同。老W听了这个问题，觉得还不够有趣，他</div>
<div>在平面上又设立了n个禁止点，表示马不能走到这些点上，现在他们想知道，这种情况下马有多少种不同的移动方</div>
<div>法呢？答案数可能很大，你只要告诉他们答案模(10^9+7)的值就行。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数Ex,Ey,n分别表示马的目标点坐标与禁止点数目。</div>
<div>第二行四个整数Ax,Ay,Bx,By分别表示两种单步移动的方法，保证Ax*By-Ay*Bx≠0</div>
<div>接下来n行每行两个整数Sxi,Syi，表示一个禁止点。</div>
<div>|Ax|,|Ay|,|Bx|,|By| &lt;= 500, 0 &lt;= n,Ex,Ey &lt;= 500</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>仅一行一个整数，表示所求的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 1<br/>
0 1 1 0<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">40</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

