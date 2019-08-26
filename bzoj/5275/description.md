
# Description

<div class="content"><div>Salroey小时候在北方的山里住过一段时间，每当冬末春初，山上冰雪融化的时候，凝结在小溪上的冰雪便会随着</div>
<div>溪水流动起来。在落差较大的地方，还能看见在阳光下晶莹剔透的碎冰倾泻而下，十分美妙。</div>
<div>Salroey那是经常和同学做一种游戏，找一段笔直的小溪，在两端各等距的放Ⅳ块石头，在平面上就是一个2*N的规</div>
<div>整的点阵。现在Salroey从任意一个石头开始，反复做如下操作直到把所有石头捡起来：</div>
<div>1．捡起脚下的石头。</div>
<div>2．选择任意一个石头s，使得当前石头和S的连线段上没有任何其他未捡起的石头，即不能</div>
<div>从正上方跨越未捡起的石头（可以跨越小溪）。</div>
<div>3．若所有石头都被捡起则结束游戏，否则跳到1。</div>
<div>现在Salroey想知道，一共有多少种不同的方案来捡起所有的石头呢，两个方案不同当且</div>
<div>仅当某一步Salroey所在位置不同。方案数对P取模。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数T表示数据组数。</div>
<div>对于每组数据输入一行两个正整数N，P，意义如题所述。</div>
<div>1 ≤ n ≤ 4000; 1 ≤ P ≤ 10^9 + 7; 1 ≤ T ≤ 5</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一行一个整数表示方案数对P取模的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 123456<br/>
2 234567<br/>
3 345678<br/>
200  1000000007</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
24<br/>
504<br/>
183129407</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By C_SUNSHINE">By C_SUNSHINE</a></p></div>

