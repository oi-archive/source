
# Description

<div class="content"><p>小铭铭最近获得了一副新的桌游，游戏中需要用 m 个骑士攻占 n 个城池。</p>
<div>这 n 个城池用 1 到 n 的整数表示。除 1 号城池外，城池 i 会受到另一座城池 fi 的管辖，</div>
<div>其中 fi &lt;i。也就是说，所有城池构成了一棵有根树。这 m 个骑士用 1 到 m 的整数表示，其</div>
<div>中第 i 个骑士的初始战斗力为 si，第一个攻击的城池为 ci。</div>
<div>每个城池有一个防御值 hi，如果一个骑士的战斗力大于等于城池的生命值，那么骑士就可</div>
<div>以占领这座城池；否则占领失败，骑士将在这座城池牺牲。占领一个城池以后，骑士的战斗力</div>
<div>将发生变化，然后继续攻击管辖这座城池的城池，直到占领 1 号城池，或牺牲为止。</div>
<div>除 1 号城池外，每个城池 i 会给出一个战斗力变化参数 ai;vi。若 ai =0，攻占城池 i 以后骑士战斗力会增加 vi；若 ai =1，攻占城池 i 以后，战斗力会乘以 vi。注意每个骑士是单独计算的。也就是说一个骑士攻击一座城池，不管结果如何，均不会影响其他骑士攻击这座城池的结果。</div>
<div>现在的问题是，对于每个城池，输出有多少个骑士在这里牺牲；对于每个骑士，输出他攻占的城池数量。</div></div>

# Input

<div class="content"><p>第 1 行包含两个正整数 n;m，表示城池的数量和骑士的数量。</p>
<div>第 2 行包含 n 个整数，其中第 i 个数为 hi，表示城池 i 的防御值。</div>
<div>第 3 到 n +1 行，每行包含三个整数。其中第 i +1 行的三个数为 fi;ai;vi，分别表示管辖</div>
<div>这座城池的城池编号和两个战斗力变化参数。</div>
<div>第 n +2 到 n + m +1 行，每行包含两个整数。其中第 n + i 行的两个数为 si;ci，分别表</div>
<div>示初始战斗力和第一个攻击的城池。</div></div>

# Output

<div class="content"><p> 输出 n + m 行，每行包含一个非负整数。其中前 n 行分别表示在城池 1 到 n 牺牲的骑士</p>
<div>数量，后 m 行分别表示骑士 1 到 m 攻占的城池数量。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
50 20 10 10 30<br/>
1 1 2<br/>
2 0 5<br/>
2 0 -10<br/>
1 0 10<br/>
20 2<br/>
10 3<br/>
40 4<br/>
20 4<br/>
35 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
0<br/>
0<br/>
0<br/>
1<br/>
1<br/>
3<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p><p> 对于 100% 的数据，1 &lt;= n;m &lt;= 300000; 1 &lt;= fi&lt;i; 1 &lt;= ci &lt;= n; -10^18 &lt;= hi,vi,si &lt;= 10^18;ai等于1或者2；当 ai =1 时，vi &gt; 0；保证任何时候骑士战斗力值的绝对值不超过 10^18。</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

