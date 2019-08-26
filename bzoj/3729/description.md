
# Description

<div class="content"><p>某一天gty在与他的妹子玩游戏。<br/>
妹子提出一个游戏，给定一棵有根树，每个节点有一些石子，每次可以将不多于L的石子移动到父节点，询问<br/>
将某个节点的子树中的石子移动到这个节点先手是否有必胜策略。<br/>
gty很快计算出了策略。<br/>
但gty的妹子十分机智，她决定修改某个节点的石子或加入某个新节点。<br/>
gty不忍心打击妹子，所以他将这个问题交给了你。<br/>
另外由于gty十分绅士，所以他将先手让给了妹子。</p></div>

# Input

<div class="content"><p>第一行两个数字，n和L,n&lt;=5*10^4,L&lt;=10^9<br/>
第二行n个数字，表示每个节点初始石子数。<br/>
接下来n-1行，每行两个整数u和v，表示有一条从u到v的边。<br/>
接下来一行一个数m，表示m组操作。<br/>
接下来m行，每行第一个数字表示操作类型<br/>
若为1，后跟一个数字v，表示询问在v的子树中做游戏先手是否必胜。<br/>
若为2，后跟两个数字x，y表示将节点x的石子数修改为y。<br/>
若为3，后跟三个数字u,v,x，表示为u节点添加一个儿子v，初始石子数为x。<br/>
在任意时刻，节点数不超过5*10^4。</p></div>

# Output

<div class="content"><p>对于每个询问，若先手必胜，输出&#34;MeiZ&#34;,否则输出&#34;GTY&#34;。<br/>
另，数据进行了强制在线处理，对于m组操作，除了类型名以外，都需要异或之前回答为&#34;MeiZ&#34;的个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1000<br/>
0 0<br/>
1 2<br/>
1<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">GTY</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By wangxz">By wangxz</a></p></div>

