
# Description

<div class="content"><div>在Berland，有n个城堡。每个城堡恰好属于一个领主。不同的城堡属于不同的领主。在所有领主中有一个是国王，</div>
<div>其他的每个领主都直接隶属于另一位领主，并且间接隶属于国王。一位领主可以拥有任意数量的下属。这些城堡被</div>
<div>一些双向的道路连接。两个城堡是连接的当且仅当他们的主人中一位直接隶属于另一位。每一年，在Berland会发</div>
<div>生以下两件事中的一件：1．野蛮人攻击了城堡c。这是城堡c第一次也会是最后一次被攻击，因为野蛮人从来不攻</div>
<div>击同一座城堡超过一次。2．一个骑士从城堡a出发前往到城堡b。骑士从不重复经过同一座城堡，因此他的路线是</div>
<div>唯一确定的。现在考虑第二类事件。由于从城堡a到b的路途遥远，每个骑士会在他经过的某个城堡停下来休息一次</div>
<div>。根据规则，骑士不能停留在第 y 年以后受到过攻击的城堡中。所以，骑士选择了途径的第k个从第 y+1 年开始</div>
<div>到现在（当时）没有被攻击过的城堡（不算城堡a和b）。你，伟大的历史学家，知道Berland历史上的所有m个事件</div>
<div>。请你计算，每个骑士是在哪个城堡休息的。如果在从城堡a到城堡b的路上少于k座城堡，那么你可以断定有关这</div>
<div>个骑士的记载是有误的。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数N，表示城堡数目。</div>
<div>第二行包含N个整数，依次表示编号为 1...N 的城堡领主的上级。特别的，国王没有上级，故用 0 表示。</div>
<div>第三行包含一个整数M，表示事件数目。</div>
<div>接下来M行，每行描述一个事件：</div>
<div>若是第1类事件，则包含两个整数，依次是1，ci；</div>
<div>若是第2类事件，则包含五个整数，依次是2，ai，bi，ki，yi。</div>
<div>1 ≤ N, M ≤ 10^5，1 ≤ ai, bi, ci, ki ≤ N，0 ≤ yi  &lt;  i， 每个事件中 ai ≠ bi</div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，每行一个整数，依次表示每个骑士休息的城堡编号。若骑士不可能休息，则输出 -1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 1 2<br/>
5<br/>
2 1 3 1 0<br/>
1 2<br/>
2 1 3 1 0<br/>
2 1 3 1 1<br/>
2 1 3 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
-1<br/>
-1<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

