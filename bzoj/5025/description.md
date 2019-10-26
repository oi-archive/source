
# Description

<div class="content"><div>对于一个带权无向图，我们可以考察它的单调上升路径。一条路径被称为单调上升的，如果沿着它走时的权值是单</div>
<div>调递增的。注意，路径由多条首尾相连的边组成，且可经过同一顶点多次。路径的长度为它包含的边数。举例来说</div>
<div>：下图中 v2→v3→v1→v2 是一条单调上升路径，因为每条边的权值为 1,2,4。这条路径的长度为 3。更进一步的</div>
<div>，你可以验证下图中所有的单调上升路径的长度都不超过 3。</div>
<div> <img src="/source/bzoj/5025/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwOS8xMS5wbmc=.png" width="228" height="189" alt=""/></div>
<div>下面的结论指出在某些图中总会存在一个比较长的单调上升路径：</div>
<div>结论：假设带权无向图 G 有 100个节点 1000 条边，且所有权值各不相同。</div>
<div>那么，G 中一定存在一个单调上升路径，它的长度大于等于 20。</div>
<div>证明：假设每个节点上有一个探险家。我们按权值从小到大枚举所有的边，</div>
<div>每次将该边连接的节点中的探险家的位置进行对调。</div>
<div>可以知道，每个探险家都走的是一条单调上升路径。</div>
<div>另外，由于共有 100个探险家，而探险家一共走了 2000 步，所以有人走了 20 步。证毕。</div>
<div>现在，我们的问题是：</div>
<div>给定一个完全图 G，它的顶点个数为一个偶数 N。</div>
<div>你的任务是给每条边选一个不同的权值，要使得最长的单调上升路径最短。</div>
<p></p>
<p></p></div>

# Input

<div class="content"><p> 输入仅一行一个正偶数 N。</p>
<div>2≤N≤500</div></div>

# Output

<div class="content"><p> 输出整数 1 到 N(N-1) / 2 的一个排列，相邻的数之间用一个空格或换行隔开。</p>
<div>第一个数代表你给边 (1,2) 选的权值；第二个数是给 (1,3) 的权值，……，</div>
<div>第 N 个数是给 (1,N)的权值；然后是 (2,3)的权值，(2,4) 的权值，……，(2,N) 的权值；</div>
<div>然后是 (3,4)到 (3,N) 的权值；以此类推；最后是 (N-1,N) 的权值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">Case#1: 4 <br/>
<br/>
Case#2: 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case#1: <br/>
4 6 2<br/>
3 1<br/>
5<br/>
<br/>
Case#2: <br/>
12 8 15 3 5<br/>
6 7 1 13<br/>
10 14 11<br/>
4 2<br/>
9<br/>
<br/>
*以上Case#1和Case#2 分别为一个单独的样例。<br/>
HINT<br/>
本题十分良心地提供了一个附件文件：tab.xlsx 下载地址：http://www.lydsy.com/JudgeOnline/upload/tab.rar<br/>
该文件中有50张表格！每一张表格都满足一个很特别的性质。<br/>
你可以去观察一下这些表格。希望它们对你会有帮助。<br/>
然而表格只是作为提示，不要在代码中直接粘贴该文件或是保存过大的常数表格，否则你的代码长度将会超出OJ代码长度限制而直接不予评测。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

