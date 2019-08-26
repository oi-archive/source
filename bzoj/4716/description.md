
# Description

<div class="content"><div>【题目背景】</div>
<div>小Q最近喜欢上了一款游戏，名为《舰队connection》，在游戏中，小Q指挥强大的舰队南征北战，从而成为了一名</div>
<div>dalao。在游戏关卡的攻略中，可能由于作战过程中某艘船受到严重损伤，为避免沉没而被迫进行返航，这种情况</div>
<div>大家称为这艘船“假摔”。小Q最喜欢使用的一艘战舰代号为P01，但是最近这艘船总是用各种不同的姿势假摔，于</div>
<div>是小Q打算研究一下原因。</div>
<div>【题意描述】</div>
<div>P01的装甲可以近似看作一个n*m的矩阵，每个位置上的数字代表这个位置装甲的强度。当受到炮击时，防御力为被</div>
<div>炮击的部分的所有位置强度之和。最近小Q发现，敌方有一种船只被称为ENE，它可以发射不同形状的炮弹，以达到</div>
<div>攻击装甲最薄弱处的目的。P01已经被连续k次用不同方式打成了严重损伤(假摔)，于是小Q打算分析一下ENE的攻击</div>
<div>力。为了简单起见，我们作如下假设：</div>
<div>1、ENE的炮弹形状无论如何变化，火力值都为一个定值(整数，未知)</div>
<div>2、ENE的炮弹形状只能是长方形(ENE:呵呵)，且由于口径的限制，炮弹不能太小(具体来说，对于每一发炮弹长xi</div>
<div>宽yi，有xmin&lt;=xi&lt;=n，ymin&lt;=yi&lt;=m)</div>
<div>3、当ENE的炮击命中P01的某处装甲时，被命中部分的强度之和为P01的防御力，此时，ENE的火力必须严格大于P01</div>
<div>的防御力，才能将其击穿并造成严重损伤(假摔)。</div>
<div>然而，小Q并没有得到详细的中弹数据，只知道P01用k种不同的方式假摔过。两种假摔方式不同，当且仅当受到炮</div>
<div>击的位置不完全相同。因此，不同形状的炮弹击穿护甲时必定可以造成不同的假摔方式，而相同形状的炮弹在不同</div>
<div>的位置击穿护甲也能造成不同的假摔方式。现在，小Q想估计ENE的火力最低是多少。于是，这个任务被交给了你。</div>
<div>举例而言，假设P01的护甲为3*4：</div>
<div>0 1 3 7</div>
<div>1 1 5 5</div>
<div>7 6 9 6</div>
<div>如果ENE的口径至少为2*2，那么直接使用2*2的炮弹攻击左上角2*2的装甲时，只要火力&gt;=4即可造成一种假摔。如</div>
<div>果想造成k=3种不同的假摔方式，至少要拥有12的火力，此时可以造成如下三种假摔方式：</div>
<div>1、2*2炮弹，攻击有数字的部分，装甲值为3</div>
<div>0 1 - -</div>
<div>1 1 - -</div>
<div>- - - -</div>
<div>2、2*2炮弹，攻击有数字的部分，装甲值为10</div>
<div>- 1 3 -</div>
<div>- 1 5 -</div>
<div>- - - -</div>
<div>3、2*3炮弹，攻击有数字的部分，装甲值为11</div>
<div>0 1 3 -</div>
<div>1 1 5 -</div>
<div>- - - -</div>
<div>可以证明，火力小于12时，无法造成3种不同的假摔方式，所以ENE的火力至少应为12。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，五个数n, m, xmin, ymin, k，空格分隔。</div>
<div>接下来n行，每行m个数，空格分隔，表示P01的装甲。</div>
<div>1&lt;=n,m&lt;=1000，1&lt;=xmin&lt;=n, 1&lt;=ymin&lt;=m, 1&lt;=k&lt;=250000，装甲值为不超过2000的非负整数。</div>
<div>保证火力为无穷大的ENE可以造成k种不同的假摔方式。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>仅一行，一个数，表示ENE的火力最低值。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 2 2 3<br/>
0 1 3 7<br/>
1 1 5 5<br/>
7 6 9 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

