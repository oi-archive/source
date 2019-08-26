
# Description

<div class="content"><div>数字和数学规律主宰着这个世界。</div>
<div></div>
<div>机器的运转，</div>
<div></div>
<div>生命的消长，</div>
<div></div>
<div>宇宙的进程，</div>
<div></div>
<div>这些神秘而又美妙的过程无不可以用数学的语言展现出来。</div>
<div></div>
<div>这印证了一句古老的名言：</div>
<div></div>
<div>“学好数理化，走遍天下都不怕。”</div>
<div></div>
<div>学渣小R被大学的数学课程虐得生活不能自理，微积分的成绩曾是他在教室里上的课的最低分。然而他的某位陈姓室友却能轻松地在数学考试中得到满分。为了提升自己的数学课成绩，有一天晚上（在他睡觉的时候），他来到了数学王国。</div>
<div></div>
<div>数学王国中，每个人的智商可以用一个属于 [0,1]的实数表示。数学王国中有 n 个城市，编号从 0 到 n−1 ，这些城市由若干座魔法桥连接。每个城市的中心都有一个魔法球，每个魔法球中藏有一道数学题。每个人在做完这道数学题之后都会得到一个在 [0,1] 区间内的分数。一道题可以用一个从 [0,1] 映射到 [0,1]的函数 f(x) 表示。若一个人的智商为 x ，则他做完这道数学题之后会得到 f(x)分。函数 f有三种形式：</div>
<div></div>
<div>    正弦函数 sin(ax+b) (a∈[0,1],b∈[0,π],a+b∈[0,π])</div>
<div></div>
<div>    指数函数 e^(ax+b) (a∈[−1,1],b∈[−2,0],a+b∈[−2,0])</div>
<div></div>
<div>    一次函数 ax+b (a∈[−1,1],b∈[0,1],a+b∈[0,1]</div>
<div>数学王国中的魔法桥会发生变化，有时会有一座魔法桥消失，有时会有一座魔法桥出现。但在任意时刻，只存在至多一条连接任意两个城市的简单路径（即所有城市形成一个森林）。在初始情况下，数学王国中不存在任何的魔法桥。</div>
<div>数学王国的国王拉格朗日很乐意传授小R数学知识，但前提是小R要先回答国王的问题。这些问题具有相同的形式，即一个智商为 x 的人从城市 u 旅行到城市 v（即经过 u 到 v 这条路径上的所有城市，包括 u和 v ）且做了所有城市内的数学题后，他所有得分的总和是多少。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数 n,m 和一个字符串 type 。</div>
<div>表示数学王国中共有 n 座城市，发生了 m 个事件，该数据的类型为 type 。 </div>
<div>typet 字符串是为了能让大家更方便地获得部分分，你可能不需要用到这个输入。</div>
<div>其具体含义在【数据范围与提示】中有解释。</div>
<div></div>
<div>接下来 n 行，第 i 行表示初始情况下编号为 i 的城市的魔法球中的函数。</div>
<div>一个魔法用一个整数 f表示函数的类型，两个实数 a,b 表示函数的参数，若</div>
<div>    f=1,则函数为 f(x)=sin(ax+b)(a∈[0,1],b∈[0,π],a+b∈[0,π])</div>
<div>    f=2,则函数为 f(x)=e^(ax+b)(a∈[−1,1],b∈[−2,0],a+b∈[−2,0])</div>
<div>    f=3,则函数为 f(x)=ax+b(a∈[−1,1],b∈[0,1],a+b∈[0,1])</div>
<div>接下来 m行，每行描述一个事件，事件分为四类。</div>
<div>    appear u v 表示数学王国中出现了一条连接 u 和 v 这两座城市的魔法桥 (0≤u,v&lt;n,u≠v) ，保证连接前 u和 v 这两座城市不能互相到达。</div>
<div>    disappear u v 表示数学王国中连接 u 和 v 这两座城市的魔法桥消失了，保证这座魔法桥是存在的。</div>
<div>    magic c f a b 表示城市 c 的魔法球中的魔法变成了类型为 f ，参数为 a,b 的函数</div>
<div>    travel u v x 表示询问一个智商为 x 的人从城市 u 旅行到城市 v </div>
<div>（即经过 u到 v 这条路径上的所有城市，包括 u 和 v ）后，他得分的总和是多少。</div>
<div> 若无法从 u 到达 v ，则输出一行一个字符串 unreachable。</div>
<div>1≤n≤100000,1≤m≤200000</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问，输出一行实数，表示得分的总和。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 7 C1<br/>
1 1 0<br/>
3 0.5 0.5<br/>
3 -0.5 0.7<br/>
appear 0 1<br/>
travel 0 1 0.3<br/>
appear 0 2<br/>
travel 1 2 0.5<br/>
disappear 0 1<br/>
appear 1 2<br/>
travel 1 2 0.5</span></div>

# Sample Output

<div class="content"><span class="sampledata">9.45520207e-001<br/>
1.67942554e+000<br/>
1.20000000e+000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

