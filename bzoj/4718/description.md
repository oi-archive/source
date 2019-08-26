
# Description

<div class="content"><div>小Q最近喜欢上了一款游戏，名为《舰队connection》，在游戏中，小Q指挥强大的舰队南征北战，从而成为了一名</div>
<div>dalao。在战斗中，布阵往往是决定胜败的关键，其中梯形阵捉摸不定的攻守能力深受小Q喜爱。</div>
<div>【题意描述】</div>
<div>小Q的舰队有n艘船在海上航行，每艘船都拥有自己的坐标(xi,yi)。我们规定x表示行，y表示列，x从上到下增加，</div>
<div>y从左到右增加，左上角为(1,1)，右下角为(Xmax, Ymax)。梯形阵由舰队中的至少4艘船构成，阵中的所有船只都</div>
<div>在一条直线上，且刚好与坐标轴夹角为45度。阵型中所有船只组成的线段上不能有其他的船只，但延长线上可以有</div>
<div>其他船只。例如，在以下阵列中(.表示海，*表示船)</div>
<div>.*.**.</div>
<div>*.***.</div>
<div>.*.*..</div>
<div>**..*.</div>
<div>*..*.*</div>
<div>....*.</div>
<div>存在6种梯形阵，其中3种如下(被X标注的为阵中的船只)：</div>
<div>.*.**..*.X*..*.*X.</div>
<div>X.***.*.X**.*.*X*.</div>
<div>.X.*...X.*...*.*..</div>
<div>**..*.X*..*.*X..*.</div>
<div>*..X.**..*.*X..*.*</div>
<div>....X.....*.....*.</div>
<div>另外的3种均在同一条直线上，但它们被视为不同的梯形阵，如下：</div>
<div>.X.**..*.**..X.**.</div>
<div>*.X**.*.X**.*.X**.</div>
<div>.*.X...*.X...*.X..</div>
<div>**..X.**..X.**..X.</div>
<div>*..*.**..*.X*..*.X</div>
<div>....*.....*.....*.</div>
<div>需要注意的是，以下三种不被认为是梯形阵，因为它们所在线段上包含了其他船只。</div>
<div>（X表示选出的船只，#表示不合法的其他船只）</div>
<div>.X.**..X.**..X.**.</div>
<div>*.#**.*.X**.*.X**.</div>
<div>.*.X...*.#...*.X..</div>
<div>**..X.**..X.**..#.</div>
<div>*..*.X*..*.X*..*.X</div>
<div>....*.....*.....*.</div>
<div>小Q会不断给出两种询问(type, L, R, k)</div>
<div>询问1：在L&lt;=xi&lt;=R的所有船中，至少由1/k的船组成的梯形阵有多少种</div>
<div>询问2：在L&lt;=yi&lt;=R的所有船中，至少由1/k的船组成的梯形阵有多少种</div>
<div>例如，在上图的舰队中：</div>
<div>.*.**.</div>
<div>*.***.</div>
<div>.*.*..</div>
<div>**..*.</div>
<div>*..*.*</div>
<div>....*.</div>
<div>对于询问(1,1,5,3)来说，1~5行共计15艘船，至少由其中1/3的船即5艘船组成的梯形阵只有1种。</div>
<div>对于询问(1,1,5,4)来说，至少由1/4的船，即15/4艘船组成的梯形阵，由于船必须是整数艘</div>
<div>也即至少4艘船组成，有5种。</div>
<div>对于询问(2,2,5,6)来说，2~5列共计12艘船，至少由1/6的船组成，即至少由2艘船组成</div>
<div>但是梯形阵至少要由4艘船组成，所以只有1种。</div>
<p></p></div>

# Input

<div class="content"><div>第一行三个数，n, Xmax, Ymax，空格分隔，表示船数和最大坐标。</div>
<div>接下来n行，每行两个数Xi, Yi，空格分隔，表示每艘船的位置。</div>
<div>接下来1行，一个数q，表示任务2的询问个数。</div>
<div>接下来q行，每行4个数type, L, R, k，空格分隔，描述一个询问。</div>
<div>n&lt;=200000，1&lt;=Xmax&lt;=500000，1&lt;=Ymax&lt;=500000，1&lt;=q&lt;=100000，1&lt;=k&lt;=n</div>
<div>所有询问k之和不超过200000</div>
<p></p></div>

# Output

<div class="content"><div>共计q行，每行一个数，表示每个询问的答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">16 6 6<br/>
1 2<br/>
1 4<br/>
1 5<br/>
2 1<br/>
2 3<br/>
2 4<br/>
2 5<br/>
3 2<br/>
3 4<br/>
4 1<br/>
4 2<br/>
4 5<br/>
5 1<br/>
5 4<br/>
5 6<br/>
6 5<br/>
3<br/>
1 1 5 3<br/>
1 1 5 4<br/>
2 2 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
5<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

