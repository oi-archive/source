
# Description

<div class="content"><div>小H在学习“集合与图论”的时候遇到了一个问题，他思考了很久依然无法很好完成这个问题。于是他只好来求助</div>
<div>你了，给出n个点m条边的带权无向图（即每条无向边上都有一个权值），有3个集合A、B、C。一开始无向图中所有</div>
<div>点都属于A集合，有如下9种操作：</div>
<div>MoveA x：表示将第x个点从所在集合中删除，并加入至A集合。</div>
<div>MoveB x：表示将第x个点从所在集合中删除，并加入至B集合。</div>
<div>MoveC x：表示将第x个点从所在集合中删除，并加入至C集合。</div>
<div>AskAA：询问两个端点都属于A集合的所有边中最小的权值是多少。</div>
<div>AskAB：询问两个端点分别属于A集合和B集合的所有边中最小的权值是多少。</div>
<div>AskAC：询问两个端点分别属于A集合和C集合的所有边中最小的权值是多少。</div>
<div>AskBB：询问两个端点都属于B集合的所有边中最小的权值是多少。</div>
<div>AskBC：询问两个端点分别属于B集合和C集合的所有边中最小的权值是多少。</div>
<div>AskCC：询问两个端点都属于C集合的所有边中最小的权值是多少。</div>
<div>你能帮助他解决这个问题吗？</div></div>

# Input

<div class="content"><div>输入的第1行有两个正整数，分别表示n和m。</div>
<div>在第2行至第m+1行中，每行有三个正整数，分别为u、v、w。表示这条无向边的两个端点分别为u和v(u!=v)，</div>
<div>且这个边的权值为w(w&lt;=10^9)。</div>
<div>第m+2行有一个正整数q，表示有q个询问。</div>
<div>在第m+3行至第m+q+2行中，每行的输入方式为题目描述里9种操作中的一种。</div>
<div>n&lt;=100000,m&lt;=500000,q&lt;=100000。且无向图上任意两个点之间至多能选出3条不相交的路径。</div></div>

# Output

<div class="content"><div>对于所有的Ask操作输出最小的权值，如果不存在则输出“NoFound!”。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2 1 <br/>
2 3 2<br/>
3 1 3<br/>
5<br/>
AskAA<br/>
AskAB<br/>
MoveB 2<br/>
AskAA<br/>
AskAB</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
No Found!<br/>
3<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

