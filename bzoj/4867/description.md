
# Description

<div class="content"><div>由乃为了吃到最传统最纯净的美食，决定亲自开垦一片菜园。现有一片空地，由乃已经规划n个地点准备种上蔬菜</div>
<div>。最新鲜的蔬菜需有最甘甜井水的灌溉，因此由乃将要打出两口井，分别记为井A、井B。现在问题来了，由乃可是</div>
<div>一周目的神，为何要打井？是谁想出来的这些题面？由乃不善于搞事情，于是提出以下几个方法，再根据这些方法</div>
<div>找出题人。方法如下：</div>
<div>1.<span class="Apple-tab-span" style="white-space:pre">	</span>做完这个出题人出的所有题</div>
<div>2.<span class="Apple-tab-span" style="white-space:pre">	</span>做完所有数据结构题</div>
<div>3.<span class="Apple-tab-span" style="white-space:pre">	</span>出一道奇怪的数据结构题，而且卡常卡死所有做题的</div>
<div>至于为什么这样能找到出题人呢。。。我也不信她能找到我。。。（能找到岂不是更好？）</div>
<div>因为由乃是神，所有她有很多秒时间，她终于做完了世界上左右的数据结构题</div>
<div>于是该她出题了，她左思右想，出了一个简单数据结构题：</div>
<div>给你一个n个点的有根树，1为根，带边权，有m次操作。</div>
<div>1、求x的子树中第k小的深度的值，如果子树中没有k个点则输出-1；</div>
<div>2、将x与x父亲的边权加上k。</div>
<div>保证每次操作2的k以及原树的边权小于等于一个数len。</div>
<div>如果操作2中x为1，那么视为将x的基础深度加上了k。</div>
<div>由乃能不能找到出题人呢？</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个数n,m,len。</div>
<div>之后n - 1行每行两个数表示2~n每个点的父亲编号，以及他们到父亲的边权。。。</div>
<div>之后m行每行三个数 opt,x,k，opt表示操作种类，x,k意义如题所述。</div>
<div>n,m &lt;= 100000</div>
<p></p></div>

# Output

<div class="content"><div>对于每个操作1，输出一个数表示答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 3<br/>
1 3<br/>
2 3<br/>
1 1 3<br/>
2 3 3<br/>
1 1 3<br/>
2 1 2<br/>
1 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
9<br/>
11</span></div>

# Hint

<div class="content"><p></p><div>对于所有数据，n,m &lt;= 100000，len &lt;= 10</div><br/>
<div>因为出题人是sb，len &lt;= 10，其实没有这个限制也可以解决这个问题</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

