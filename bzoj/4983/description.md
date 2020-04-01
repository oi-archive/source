
# Description

<div class="content"><div>JK生活的地区有很多南北方向和东西方向的道路相互交叉。南北方向的相邻两条道路间隔1km，东西方向的相邻两</div>
<div>条道路相邻也是1km。JK家所在的路口用(0, 0)表示。这个地区的路口都用两个整数i和j表示，如(i, j)。也就是</div>
<div>说，路口(i, j)是路口(0, 0)以东i km(i&lt;0时为以西-i km)，以北j km(j&lt;0时为以南-j km)的路口。</div>
<div>JK养了一只名狗。JK作出了一个K天内遛狗的计划。计划如以下所述：</div>
<div>●K天里最初的一天的早上，JK在路口(0, 0)。JK的狗会在路口(0, 0)上作了一个标记。</div>
<div>除(0, 0)以外，没有在任何路口上作标记。</div>
<div>●K天里JK会在每天的白天散步。1天的散步由N次跨步组成。每次跨步都会从一个路口移动到相邻的另一个路口，</div>
<div>并在目标路口上作标记。JK每天白天运动是固定的，不会发生变化。</div>
<div>●白天移动完成后，会在当前所在的路口睡到第二天早上。</div>
<div></div>
<div>如果4个路口(a,b),(a + 1,b),(a + 1,b + 1),(a,b + 1)都被JK标记过一次以上，那么这4个路口包围的区域就属</div>
<div>于JK狗的领地。JK请你写一个程序，给定JK的遛狗计划，输出JK的领地包含的区域个数。这个地区的道路都非常长</div>
<div>，同时南北方向和东西方向都有足够多的道路，所以遛狗的途中JK不会到达道路的两端或者地区的边界。</div>
<p></p></div>

# Input

<div class="content"><div>第一行为2个整数N和K。N为每天散步的跨步次数，K为散步计划的总天数。</div>
<div>第二行为长度为N的字符串S。字符串里左数第p个(1&lt;=p&lt;=N)字符Cp为E, N, W, S之一。字符的意思如下：</div>
<div>字符Cp为E表示第p次跨步是向东边的相邻路口移动。</div>
<div>字符Cp为N表示第p次跨步是向北边的相邻路口移动。</div>
<div>字符Cp为W表示第p次跨步是向西边的相邻路口移动。</div>
<div>字符Cp为S表示第p次跨步是向南边的相邻路口移动。</div>
<div>这里，对于路口(i, j)来说，东，北，西，南的路口分别是</div>
<div>路口(i + 1, j)，路口(i, j + 1)，路口(i - 1, j)，路口(i, j - 1)。</div>
<div>1 ≦ N ≦ 100 000，1 ≦ K ≦ 1 000 000 000．</div>
<p></p></div>

# Output

<div class="content"><div>输出为一个整数，为JK的领地包含的区域个数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 2<br/>
EENWSEEESWWS</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

