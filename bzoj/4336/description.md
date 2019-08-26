
# Description

<div class="content"><div>在一片古老的土地上，有一个繁荣的文明。</div>
<div>这片大地几乎被森林覆盖，有N座城坐落其中。巧合的是，这N座城由恰好N-1条双</div>
<div>向道路连接起来，使得任意两座城都是连通的。也就是说，这些城形成了树的结构，任意两</div>
<div>座城之间有且仅有一条简单路径。</div>
<div>在这个文明中，骑士是尤其受到尊崇的职业。任何一名骑士，都是其家族乃至家乡的荣</div>
<div>耀。Henry从小就渴望成为一名能守护家乡、驱逐敌人的骑士。勤奋训练许多年后，Henry</div>
<div>终于满18岁了。他决定离开家乡，向那些成名已久的骑士们发起挑战！</div>
<div>根据Henry的调查，大陆上一共有M名受封骑士，不妨编号为1到M。</div>
<div>第i个骑士居住在城Pi，武力值为Fi。</div>
<div>Henry计划进行若干次旅行，每次从某座城出发沿着唯一的简单路径前往另一座城，</div>
<div>同时会挑战路线上武力值最高的K个骑士（Henry的体力有限，为了提高水平，当然要挑</div>
<div>战最强的骑士）。如果路线上的骑士不足K人，Henry会挑战遇到的所有人。</div>
<div>每次旅行前，可能会有某些骑士的武力值或定居地发生变化，Henry自然会打听消息，</div>
<div>并对计划做出调整。</div>
<div>为了在每次旅行时做好充分准备，Henry希望你能帮忙在每次旅行前计算出这条路线</div>
<div>上他将挑战哪些对手。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，一个整数N，表示有N座城，编号为1~N。</div>
<div>接下来N-1行，每行两个整数Ui和Vi，表示城Ui和城Vi之间有一条道路相连。</div>
<div>第N+1行，一个整数M，表示有M个骑士。</div>
<div>接下来M行，每行两个整数Fi和Pi。按顺序依次表示编号为1~M的每名骑士的武</div>
<div>力值和居住地。</div>
<div>第N+M+2行，两个整数Q,K，分别表示操作次数和每次旅行挑战的骑士数目上限。</div>
<div>接下来Q行，每行三个整数Ti,Xi,Yi。Ti取值范围为{1,2,3}，表示操作类型。</div>
<div>一共有以下三种类型的操作：</div>
<div>Ti=1时表示一次旅行，Henry将从城Xi出发前往城市Yi；</div>
<div>Ti=2时表示编号为Xi的骑士的居住地搬到城Yi；</div>
<div>Ti=3时表示编号为Xi的骑士的武力值修正为Yi。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，依次为每个旅行的答案。</div>
<div>对每个Ti=1的询问，输出一行，按从大到小的顺序输出Henry在这次旅行中挑战的</div>
<div>所有骑士的武力值。如果路线上没有骑士，输出一行，为一个整数-1。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
1 2 <br/>
1 3 <br/>
2 4 <br/>
2 5 <br/>
4 <br/>
10 1 <br/>
6 1 <br/>
14 5 <br/>
7 3 <br/>
5 3 <br/>
1 2 3 <br/>
1 5 3 <br/>
1 4 4 <br/>
2 1 4 <br/>
1 2 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">10 7 6 <br/>
14 10 7 <br/>
-1 <br/>
7 6 </span></div>

# Hint

<div class="content"><p></p><div>100%的数据中，1 ≤ N, M ≤ 40,000，1 ≤ Ui, Vi, Pi ≤ N，1 ≤ Q ≤ 80,000, 1 ≤ K ≤ </div><br/>
<div>20，旅行次数不超过 40,000 次，武力值为不超过1,000的正整数。 </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

