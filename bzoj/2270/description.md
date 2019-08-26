
# Description

<div class="content"><p>You are a hunter chasing a monkey in the forest, trying to shoot it down with your all-powerful automatic machine gun. The monkey is hiding somewhere behind the branches of one of the trees, out of your sight. You can aim at one of the trees and shoot; your bullets are capable of going through the branches and killing the monkey instantly if it happens to be in that tree. If it isn&#39;t, the monkey takes advantage of the time it takes you to reload and takes a leap into a neighbouring tree without you noticing. It never stays in the same place after a shot. You would like to find out whether there is an strategy that allows you to capture the monkey for sure, irrespective of its initial location and subsequent jumps. If so, you need to determine the shortest sequence of shots guaranteeing this.</p>
<p><img alt="" src="http://acmicpc-live-archive.uva.es/nuevoportal/data/p4959.jpg"/></p>
<p></p>
<p>As an example, consider the situation in which there are only two neighboring trees in the forest (left hand side of Figure 2). It is then possible to make sure you capture the monkey by shooting twice at the same tree. Your first shot succeeds if the monkey happened to be there in the first place. Otherwise, the monkey was behind the other tree and it will necessarily have moved when you shoot for the second time.</p>
<p>However, depending on the shape of the forest it may not be possible for you to ensure victory. One example of this is if there are three trees, all connected to one another (right hand side of Figure 2). No matter where you aim at, there are always two possible locations for the monkey at any given moment. (Note that here we are concerned with the worst-case scenario where the monkey may consistently guess your next target tree).</p>
<div>你是一个在丛林中追逐猴子的猎人，你想用枪把猴子射下来。猴子藏在某棵树上，你是看不到它的。你可以像某棵树射击，若猴子在这棵树上它就完蛋了。若猴子不在，它就可以趁你装弹药的时候移动到某棵相邻的树上，而你无法发现它已转移。它一定不会在你射击之后停留在树上不动。你想要找到一种不管猴子的起始位置和跳法如何都一定可以杀死猴子的策略。请找出射击次数最少的方法。</div>
<div>举个例子，如果只有两棵相邻的树。你对着同一棵树射击两次就一定可以杀死猴子。如果人品好，第一次就可以杀死猴子。否则，第一次射击之后，猴子就一定会跳到第一次被射击的树上。第二次对着那棵树射击就可以杀死猴子了。</div>
<div>然而，丛林的复杂让你不一定可以获得胜利。一个例子就是有三棵树，互相连接。不管你打那一棵树，猴子总有两个地方可以跳（最坏情况是猴子可以预知你的下一个目标）。</div></div>

# Input

<div class="content"><div style="border-right: 2px dotted; padding-right: 10px; border-top: 2px dotted; padding-left: 10px; padding-bottom: 10px; border-left: 2px dotted; padding-top: 10px; border-bottom: 2px dotted; background-color: rgb(234,235,255); border-top-left-radius: 10px 10px; border-top-right-radius: 10px 10px; border-bottom-right-radius: 10px 10px; border-bottom-left-radius: 10px 10px">
<p>The input consists of several test cases, separated by single blank lines. Each test case begins with a line containing two integers <span><i>n</i></span>and <span><i>m</i></span> ( <span>1<img height="31" alt="$ \le$" width="18" align="middle" border="0" __1303269174265__="ev_9075462147" src="http://acmicpc-live-archive.uva.es/nuevoportal/data/4959img2.png"/><i>n</i><img height="31" alt="$ \le$" width="18" align="middle" border="0" __1303269174265__="ev_7642333942" src="http://acmicpc-live-archive.uva.es/nuevoportal/data/4959img2.png"/>21</span>); <span><i>n</i></span> is the number of trees in the forest, and <span><i>m</i></span> is the number of adjacency relations between trees. Each of the following <span><i>m</i></span> lines contains two distinct integers between <span>0</span> and <span><i>n</i> - 1</span> (inclusive), the identifiers of the trees in an adjacent pair. The order of both trees within a pair carries no meaning, and no pair appears more than once. You may further assume that no tree is adjacent to itself, and there is always a path between any two trees in the forest.</p>
<p>The test cases will finish with a line containing only two zeros (also preceded with a blank line).</p>
</div>
<div>输入文件包含多组测试数据。每两组测试数据用空行隔开。</div>
<div>每个数据的第一行包含两个整数n和m。n表示树的棵数，m代表树之间的关系数。</div>
<div>接下来m行，每行包含两个0到n-1之间的整数表示这两棵树是相邻的。每一对关系不会出现两次，没有树和自己连通，整个树林是连通的。</div>
<div>最后一行用两个零结束。</div></div>

# Output

<div class="content"><p>Print a line for each test case. The line should contain the single word `<tt><font face="新宋体">Impossible</font></tt>&#39; if the task is impossible. Otherwise, it must contain the shortest sequence of shots with the required property, in the format <span><i>L</i></span>: <span> <i>V</i><sub>1</sub><i>V</i><sub>2</sub>...<i>V</i><sub>L</sub></span>, where <span><i>L</i></span> is the length of the sequence, and <span><i>V</i><sub>1</sub>, <i>V</i><sub>2</sub>,..., <i>V</i><sub>L</sub></span> are space-separated integers containing the identifiers of the trees to shoot at in the right order. If several shortest sequences exist, print the lexicographically smallest one. (A sequence is smaller than another in lexicographic order if the first element on which they differ is smaller in the first one).</p>
<div>每个测试数据输出一行。</div>
<div>如果打不死猴子输出“Impossible”。否则，请输出射击次数最少的方案。格式为L：V1,V2…VL。L代表射击次数，V1,V2…VL是每次射击的位置，用空格隔开。</div>
<div>如果有多组最优解，请输出字典序最小的。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
0 1<br/>
<br/>
3 3<br/>
0 1<br/>
1 2<br/>
2 0<br/>
<br/>
4 3<br/>
0 1<br/>
2 3<br/>
1 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2: 0 0<br/>
Impossible<br/>
4: 1 3 3 1<br/>
0 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢李青林">鸣谢李青林</a></p></div>

