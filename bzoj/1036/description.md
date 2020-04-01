
# Description

<div class="content"><p>　　一棵树上有n个节点，编号分别为1到n，每个节点都有一个权值w。我们将以下面的形式来要求你对这棵树完成<br/>
一些操作： I. CHANGE u t : 把结点u的权值改为t II. QMAX u v: 询问从点u到点v的路径上的节点的最大权值 I<br/>
II. QSUM u v: 询问从点u到点v的路径上的节点的权值和 注意：从点u到点v的路径上的节点包括u和v本身</p></div>

# Input

<div class="content"><p>　　输入的第一行为一个整数n，表示节点的个数。接下来n – 1行，每行2个整数a和b，表示节点a和节点b之间有<br/>
一条边相连。接下来n行，每行一个整数，第i行的整数wi表示节点i的权值。接下来1行，为一个整数q，表示操作<br/>
的总数。接下来q行，每行一个操作，以“CHANGE u t”或者“QMAX u v”或者“QSUM u v”的形式给出。 <br/>
对于100％的数据，保证1&lt;=n&lt;=30000，0&lt;=q&lt;=200000；中途操作中保证每个节点的权值w在-30000到30000之间。</p></div>

# Output

<div class="content"><p>　　对于每个“QMAX”或者“QSUM”的操作，每行输出一个整数表示要求输出的结果。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2<br/>
2 3<br/>
4 1<br/>
4 2 1 3<br/>
12<br/>
QMAX 3 4<br/>
QMAX 3 3<br/>
QMAX 3 2<br/>
QMAX 2 3<br/>
QSUM 3 4<br/>
QSUM 2 1<br/>
CHANGE 1 5<br/>
QMAX 3 4<br/>
CHANGE 3 6<br/>
QMAX 3 4<br/>
QMAX 2 4<br/>
QSUM 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1<br/>
2<br/>
2<br/>
10<br/>
6<br/>
5<br/>
6<br/>
5<br/>
16</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

