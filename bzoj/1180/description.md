
# Description

<div class="content"><div>给出n个结点以及每个点初始时对应的权值wi。起始时点与点之间没有连边。有3类操作： </div>
<div>1、bridge A B：询问结点A与结点B是否连通。</div>
<div>如果是则输出“no”。否则输出“yes”，并且在结点A和结点B之间连一条无向边。 </div>
<div>2、penguins A X：将结点A对应的权值wA修改为X。 </div>
<div>3、excursion A B：如果结点A和结点B不连通，则输出“impossible”。</div>
<div>否则输出结点A到结点B的路径上的点对应的权值的和。</div>
<div>给出q个操作，要求在线处理所有操作。</div>
<div>数据范围：1&lt;=n&lt;=30000, 1&lt;=q&lt;=300000, 0&lt;=wi&lt;=1000。</div></div>

# Input

<div class="content"><div>第一行包含一个整数n(1&lt;=n&lt;=30000)，表示节点的数目。</div>
<div>第二行包含n个整数，第i个整数表示第i个节点初始时对应的权值。</div>
<div>第三行包含一个整数q(1&lt;=n&lt;=300000)，表示操作的数目。</div>
<div>以下q行，每行包含一个操作，操作的类别见题目描述。</div>
<div>任意时刻每个节点对应的权值都是1到1000的整数。</div></div>

# Output

<div class="content"><p>输出所有bridge操作和excursion操作对应的输出，每个一行。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
4 2 4 5 6<br/>
10<br/>
excursion 1 1<br/>
excursion 1 2<br/>
bridge 1 2<br/>
excursion 1 2<br/>
bridge 3 4<br/>
bridge 3 5<br/>
excursion 4 5<br/>
bridge 1 3<br/>
excursion 2 4<br/>
excursion 2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
impossible<br/>
yes<br/>
6<br/>
yes<br/>
yes<br/>
15<br/>
yes<br/>
15<br/>
16</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

